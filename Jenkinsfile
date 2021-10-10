pipeline {
    agent {
        docker {
            image 'node:lts-busterslim'
            args '-p 3000:3000'
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