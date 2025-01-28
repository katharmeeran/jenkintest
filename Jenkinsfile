node('any') {
    stage('Checkout') {
        checkout scm
    }
    
    stage('Version') {
        sh 'python3 --version'
    }
    
    stage('Hello') {
        sh 'python3 hello.py'
    }
}
