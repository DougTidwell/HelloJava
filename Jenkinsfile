pipeline {
    agent any
    stages {
        stage('test-environment') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}

