pipeline {
    agent { docker { image 'python' } }
    stages {
        stage('test') {
            steps {
                sh 'python test.py'
            }
        }
    }
}


