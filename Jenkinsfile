pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Step 1: Checking out the code from SCM...'
            }
        }

        stage('Build') {
            steps {
                echo 'Step 2: Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Step 3: Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Step 4: Deploying the application...'
            }
        }

        stage('Clean Up') {
            steps {
                echo 'Step 5: Cleaning up workspace...'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished.'
        }
    }
}
