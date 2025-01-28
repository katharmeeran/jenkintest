pipeline {
    agent any  // This means Jenkins can use any available executor/agent

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from the repository'
                checkout scm  // Pull the code from the SCM (GitHub, GitLab, etc.)
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project'
                sh 'echo "Building the project..."'  // Use your actual build commands
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                sh 'echo "Running tests..."'  // Replace with actual test command
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project'
                sh 'echo "Deploying the project..."'  // Replace with deploy command
            }
        }
    }
}
