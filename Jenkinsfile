pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                echo "Version check.."
                bat '''
                python3 --version
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                bat '''
                python3 helloworld.py
                '''
            }
        }
    }
}
