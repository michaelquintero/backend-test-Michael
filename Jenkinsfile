pipeline {
    agent any{
        docker{
            image 'node:18-alpine'
            args '-v /var/jenkins_home/cache:/root/.npm'
    }
    stages {
        stage('Instalacion de dependencias') {
            steps {
                sh 'npm install'
            }
        }
        stage('En construccion') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
    }
}
