pipeline {
    agent any
   
    tools {nodejs "node"}
    
    stages {
        stage('check') {
            steps {
            sh 'npm config ls'
            }
        }
        stage("Install") {
            steps {
                sh "npm install"
            }
        }
        stage("Build") {
            steps {
                sh "npm run build"
            }
        }
    }
}

