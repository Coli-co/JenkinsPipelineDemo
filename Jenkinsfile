pipeline {
    agent any

    stages {
         stage('Build') {
            steps {
                echo 'Building the application...'
      
            }
        }
         stage('Test') {
            steps {
                echo 'Testing the application...'
                echo 'GitHub webhook test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
