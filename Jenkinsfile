pipeline {
  agent none
  stages {
    stage('Checkout') {
      steps {
        git(url: 'http://jenkins.kops.0secops.com:8080/blue/organizations/jenkins/pipeline-editor/testRelease.git', branch: 'master', changelog: true)
      }
    }
    stage('Deploy new version') {
      steps {
        sh 'echo version deployed'
      }
    }
  }
}