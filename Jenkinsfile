pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'echo Hello from Jenkins Pipeline'
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }
    }
}
