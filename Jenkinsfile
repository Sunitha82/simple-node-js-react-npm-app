pipeline {
    agent {
        docker {
            image 'node:latest'
            args '-p 3000:3000 -u root'
        }
    }
   
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
        
    }
}
