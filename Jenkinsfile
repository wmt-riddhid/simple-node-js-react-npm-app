pipeline {
    agent any

    tools {nodejs "node"}
    // environment {
    //         CI = 'true'
    //     }
    stages {

        stage('check') {
            steps {
                sh 'npm config ls'
            }
        }

        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}