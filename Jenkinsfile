pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Sankar-018/simple-jenkins-demo.git'
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

