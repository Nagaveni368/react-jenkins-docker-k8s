pipeline {
<<<<<<< HEAD
    agent any  // Use any available agent or executor

    environment {
        DEPLOY_ENV = 'staging'  // Define the deployment environment
    }

    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                git 'https://github.com/Nagaveni368/react-jenkins-docker-k8s.git'
            }
        }

        stage('Build') {
            steps {
                // Print a message or run actual build commands here
                sh 'echo "Building application..."'
                // Replace the line above with actual build commands, like `mvn clean install` for Maven
            }
        }

        stage('Test') {
            steps {
                // Print a message or run testing commands here
                sh 'echo "Running tests..."'
                // Replace this with commands for running unit tests, e.g., `mvn test`
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application
                sh 'echo "Deploying to ${DEPLOY_ENV} environment..."'
                // Include commands to deploy, like `scp` for file transfer or remote deployment scripts
            }
        }
    }

    post {
        always {
            // Clean up workspace after the pipeline completes
            echo 'Cleaning up...'
            deleteDir()
        }
=======
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
>>>>>>> fdf10e40f86ffe3c7f9c491d743835579c01ca8a
    }
}
