pipeline {
    agent { any { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}