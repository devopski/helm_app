pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Helm install command'
                sh 'helm install aplikacja .'
                
                
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