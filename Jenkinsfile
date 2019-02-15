pipeline {
    agent any
    environment {
        APP_NANE = "TEST"
    }
    stages {
        stage('Build Image'){
            steps{
                sh "echo ${env.APP_NANE}"
            }
        }
    }
    
}