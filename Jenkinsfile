pipeline
    agent { label 'any' } 
    stages {
        stage('version') {
            steps{
                sh 'python3 --version'
            }
        }
        stage('Hello') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
