pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
               sh 'cat Hello.txt'
            }
        }
        stage('Done') {
            steps {
                echo 'Build complete. you can add more steps here.'
                // Add your deployment steps here
            }
        }
    }
}