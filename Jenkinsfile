pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000 -u root'
        }
    }
    environment {
        HOME = '.'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
        
    }
}
