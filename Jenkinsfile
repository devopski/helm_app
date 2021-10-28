pipeline {
    agent any

    stages {
        stage('HELM') {
            steps {
                echo 'Helm upgrade command'
                sh 'helm upgrade --set containerImage=${imageName} abcd aplikacja/'  
                
            }
        }


    }
}