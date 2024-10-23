pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
                bat 'npm install'
            }
        }
        stage('Execute tests') {
            steps {
                bat 'npm test'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production'
            }
        }
    }
}
