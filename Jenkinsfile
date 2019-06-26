pipeline {
  agent none
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/acorreiaveras/testRelease'
      }
    }
    stage('Deploy new version') {
      steps {
        sh 'echo version deployed'
      }
    }
  }
}