pipeline {
  agent any
  stages {
    stage ('Archive artifacts') {
      steps {
        archiveArtifacts artifacts: 'output.txt', fingerprint: true
      }
    }
  }
}
