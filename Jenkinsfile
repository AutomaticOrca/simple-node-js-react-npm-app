pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install --verbose' 
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}