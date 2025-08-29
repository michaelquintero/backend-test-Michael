pipeline {
    agent any{
    stages {
        stage('Instalacion de dependencias') {
            agent{
            docker{
            image 'node:22'
            reuseNode true
    }
            }
        stage{
                steps {
                sh 'npm install'
            }
        }
        }

/*        stage('En construccion') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }*/
    }
}
}