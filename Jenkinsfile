pipeline {
    agent { docker { image 'python:latest' } }
    stages {
        stage('test') {
            steps {
                sh 'python test.py'
            }
        }
    }
}


