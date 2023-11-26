pipeline {
    agent any

    options {
        scm {
            pollSCM('*/1 * * * *')
        }
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
