pipeline {
    agent any
    stages {
        stage('Build') { 
            agent {
                // docker { image 'node:20.12-alpine3.18' }
            }
            steps {
                // sh 'node --version'
                // echo 'create fontend finish'
                sh 'npm run build'
            }
        }
    }
    
}