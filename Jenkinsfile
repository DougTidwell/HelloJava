pipeline {
    agent { docker { image 'maven:3.3.3' } }
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

