pipeline {
    agent {
       any
    }
    environment {
        APP_NAME = 'jasper-awx-installer'
        APP_VERSION = 'latest'
     }
    stages {
        stage('Build') {
            steps {
                sh '''
                    echo "BUILD"
                '''
            }
        }
        stage('Push') {
            steps {
                sh '''
                     echo "PUSH"
                '''
              }
            }
        }
    }
