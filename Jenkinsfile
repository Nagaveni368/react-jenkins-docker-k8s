        pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the repository
                git 'https://github.com/Nagaveni368/react-jenkins-docker-k8s.git'
            }
        }

        stage('Build') {
            steps {
                // Compile/build your code
                sh 'make'  // Replace with your build command
            }
        }

        stage('Test') {
            steps {
                // Run your tests
                sh 'make test'  // Replace with your test command
            }
        }

        stage('Deploy') {
            steps {
                // Deploy your application
                sh 'make deploy'  // Replace with your deploy command
            }
        }
    }
}
