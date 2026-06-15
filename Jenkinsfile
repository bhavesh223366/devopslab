pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/bhavesh223366/devopslab.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'python python.py'
            }
        }

        stage('Build') {
            steps {
                bat 'python python.py'
            }
        }
    }
}
