pipeline {
    agent any
    stages {
        stage('Instalacion de dependencias') {
            steps {
                sh 'npm install'
            }
        }
        stage('En construccion') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
