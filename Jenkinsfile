pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Helm install command'
                helm install aplikacja .
                
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