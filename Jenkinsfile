pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'javac App.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java App'
            }
        }
    }
}
