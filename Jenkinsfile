pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
    }

  }
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/dougtidwell/hellojava', branch: 'master')
      }
    }
  }
}