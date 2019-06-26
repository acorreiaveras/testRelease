pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/acorreiaveras/testRelease.git'
      }
    }
    stage('Deploy new version') {
      steps {
        sh 'echo version deployed'
      }
    }
  }
}