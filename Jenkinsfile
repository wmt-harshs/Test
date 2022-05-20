pipeline {
    agent any
    // environment {
    //     CI = 'true'
    // }

    stages {
        stage('build'){
            steps {
                sh 'npm install'
            }
        }
        stage('deploy'){
            steps {
                sh 'npm run build'
            }
        }
    }
}
