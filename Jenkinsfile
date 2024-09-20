pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/ZulqarnainSarwar3483/jenkin-assignment.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build stage for the HTML page (optional)'
                // No actual build is necessary for a static HTML page, but any pre-processing steps can be added here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy the HTML page'
                // Example: Copy the HTML page to a specific folder on your server
                sh 'cp -r * /var/www/html/'
            }
        }
    }
}
