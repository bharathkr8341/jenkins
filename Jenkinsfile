pipeline {
    agent1

    stages {
        stage('Checkout') {
            steps {
                echo 'Pulling code from Git...'
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo "Build step here"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Test step here"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deploy step here"'
            }
        }
    }
}

