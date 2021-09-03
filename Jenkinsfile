pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Checkout'){
            steps {
               checkout scm            
                }
        }
        stage('Build'){
            steps {
                sh "sh shell.sh"
            }
        }
    }
}
