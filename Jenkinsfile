pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'npm i'
            }
        }
        stage('Build') {
            steps {
                sh 'npm start'
            }
        }
    }
}
