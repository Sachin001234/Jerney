pipeline {
    agent any

    environment {
        DB_PASSWORD = credentials('jerney-db-password')
    }

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Create Environment') {
            steps {
                sh '''
                    cat > docker/.env <<EOF
POSTGRES_USER=jerney_user
POSTGRES_PASSWORD=${DB_PASSWORD}
POSTGRES_DB=jerney_db
EOF
                '''
            }
        }

        stage('SonarQube Analysis') {
            steps {
                script {
                    def scannerHome = tool 'sonar-scanner'

                    withSonarQubeEnv('sonarqube') {
                        sh """
                            ${scannerHome}/bin/sonar-scanner \
                            -Dsonar.projectKey=jerney \
                            -Dsonar.projectName=jerney \
                            -Dsonar.sources=.
                        """
                    }
                }
            }
        }

        stage('Build Docker Images') {
            steps {
                sh 'docker compose --env-file docker/.env -f docker/docker-compose.yml build'
            }
        }

        stage('Deploy') {
            steps {
                sh 'docker compose --env-file docker/.env -f docker/docker-compose.yml up -d'
            }
        }

        stage('Verify Deployment') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
