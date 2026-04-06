pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch ${env.BRANCH_NAME}"
                sh 'sleep 3'
            }
        }
        stage('Test') {
            steps {
                echo "Testing branch ${env.BRANCH_NAME}"
                sh 'sleep 3'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying branch ${env.BRANCH_NAME}"
                sh 'sleep 3'
            }
        }
    }
}
