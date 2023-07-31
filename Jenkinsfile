pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                echo "Version check.."
                bat '''
                C:\Users\ZEG\AppData\Local\Programs\Python\Python311\python.exe --version
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
