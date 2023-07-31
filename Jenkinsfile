pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                echo "Version check.."
                sh '''
                python3 --version
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                python3 helloworld.py
                '''
            }
        }
    }
}
