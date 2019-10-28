node ('master') {
    stage('Source') {
        git 'https://github.com/DougTidwell/HelloJava.git'
    }
    stage('Build') {
        maven 'compile package'
    }
}
