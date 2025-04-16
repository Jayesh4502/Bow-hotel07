pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Jayesh4502/Bow-hotel07.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add your build commands here
                // For example, if using npm:
                // sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
                // For example:
                // sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment commands here
                // For example, copying files to the web server directory:
                // sh 'scp -r * user@yourserver:/var/www/html/'
            }
        }
    }
}
