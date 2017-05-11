pipeline {
  agent none
  stages {
    stage('Buld docker') {
      steps {
        build(propagate: true, job: 'test-job')
      }
    }
  }
}