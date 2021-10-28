pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Helm install command'
                sh ' helm install abcd aplikacja/'
                
                
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