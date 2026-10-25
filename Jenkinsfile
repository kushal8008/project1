
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build HTML Website') {
            steps {
                echo 'Building the HTML website...'
                sh 'ls -la'
                sh 'test -f index.html'
                echo 'index.html found. Build successful!'
            }
        }
    }
}
