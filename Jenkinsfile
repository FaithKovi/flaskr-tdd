pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip3 install requirements.txt
            }
        }
        stage('test') {
            steps {
                sh 'python3 tests/app_test.py'
            }
        }
    }
}
