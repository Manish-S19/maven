pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                bat 'mvn compile'
            }
        }
        stage('test') {
            steps {
                echo 'testing'
            }
        }
        stage('Build') {
            steps {
                echo ' Building'
            }
        }
    }
}
