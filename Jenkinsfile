pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/dasarijyothi86/jenkins-demo.git'
            }
        }

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
