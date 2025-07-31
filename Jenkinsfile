pipeline {
    agent any

    environment {
        PROJECT_NAME = 'Assignment-4---CI-CD-on-K8s'
    }

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/ojaydiddy-git/Assignment-4---CI-CD-on-K8s.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulating build step...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running basic tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Simulated deployment step'
            }
        }
    }
}
