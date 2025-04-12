pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git url: 'https://github.com/<your-username>/<your-repo>.git'
            }
        }

        stage('Build') {
            steps {
                echo '🛠️ Building the application...'
                sh 'ls -la'  // Replace this with your actual build command
            }
        }
    }
}
