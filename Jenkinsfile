pipeline {
  agent none
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/acorreiaveras/testRelease', branch: 'master', changelog: true)
      }
    }
    stage('Deploy new version') {
      steps {
        sh 'echo version deployed'
      }
    }
  }
}