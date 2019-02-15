pipeline {
    agent any
    environment {
        APP_NANE = "TEST V.1"
    }
    stages {
        stage('Build Image'){
            steps{
                sh "echo ${env.APP_NANE}"
            }
        }
    }
    
}