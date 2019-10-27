node ('master') {

mavenJob('example') {
    logRotator(-1, 10)
    jdk('Java 8')
    scm {
        github('DougTidwell/HelloJava', 'master')
    }
    triggers {
        githubPush()
    }
    goals('clean verify package')
}

//     stage('Source') { // for display purposes

      // Get some code from our Git repository

//      git 'https://github.com/DougTidwell/HelloJava.git'

//      }
}
