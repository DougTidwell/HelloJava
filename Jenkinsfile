pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/dougtidwell/hellojava', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh './var/jenkins_home/tools/hudson.tasks.Maven_MavenInstallation/mvn_3.6.3/bin/mvn clean package'
      }
    }
  }
}