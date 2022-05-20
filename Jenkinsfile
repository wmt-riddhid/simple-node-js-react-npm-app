pipeline {
    agent {
        any {
            tools {nodejs "node"}
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    // environment {
    //         CI = 'true'
    //     }
    stage {
        stage('check') {
            steps {
            sh 'npm config ls'
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