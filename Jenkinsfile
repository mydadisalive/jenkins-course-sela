pipeline {
    agent any

    options {
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
