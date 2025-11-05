pipeline {
    agent any
    stages {
        stage('Building') {
            steps {
                echo "Building project..."
            }
        }
        stage('Test') {
            steps {
                echo "Testing project..."
            }
        }
        stage('Deploy') {        // New Deploy stage
            steps {
                echo "Deploying project..."
                // Add your actual deployment commands here
                // Example: sh 'scp target/app.jar user@server:/path/to/deploy'
            }
        }
    }
}
