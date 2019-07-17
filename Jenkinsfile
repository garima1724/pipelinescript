pipeline {
    agent any

    stages {
        stage('Git-Checkout') {
            steps{
                git 'https://github.com/garima1724/pipelinescript.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                bat label: '', script: 'calc.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
