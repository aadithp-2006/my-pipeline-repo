pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Fetching latest code from GitHub...'
            }
        }

        stage('Deploy to Web Server') {
            steps {
                echo 'Deploying index.html to Apache...'
                sh 'cp -rf index.html /var/www/html/'
            }
        }
    }
}
