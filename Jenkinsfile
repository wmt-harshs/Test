pipeline {
    agent {
        docker {
            image 'node:16'
            args '-p 3000:3000'
        }
    }
    // environment {
    //     CI = 'true'
    // }

    stages {
        stage('build'){
            steps {
                sh 'npm install'
            }
        }
    }
}