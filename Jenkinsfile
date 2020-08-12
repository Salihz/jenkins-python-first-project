pipeline {
    agent { label 'master' { image 'python:alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python hello-world.py'
            }
        }
    }
}