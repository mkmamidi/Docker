pipeline {
  agent any
  stages {
    stage('docker file') {
      steps {
        sh 'docker build -t tomcat .'
      }
    }

  }
}