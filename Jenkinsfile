pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
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
