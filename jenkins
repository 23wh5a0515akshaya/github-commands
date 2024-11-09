pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pulls the code from the repository
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Command to build the project, e.g., for Java projects: mvn clean install
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Command to test the project, e.g., for Java projects: mvn test
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                // Deployment steps go here
                echo 'Deploying...'
            }
        }
    }
}
