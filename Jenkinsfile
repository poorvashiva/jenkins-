pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git branch: ‘main’, url: 'https://github.com/poorvashiva/Devops2.git'
            }
        }
        stage('Building  ') {
            steps {
                echo 'Building '
            }
        }
        stage('Deploying') {
            steps {
                echo 'Deploying '
            }
        }
    }
}
