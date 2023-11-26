pipeline {
    agent any

    options {
        // Set up SCM polling to check for changes every minute
        pollSCM('*/1 * * * *')
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Build!'
            }
        }
        stage('Test') {
            steps {
                echo 'Test!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy!'
            }
        }
    }
}
