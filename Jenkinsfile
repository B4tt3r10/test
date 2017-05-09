pipeline {
  agent dockerfile
  stages {
    stage('Push') {
      steps {
        parallel(
          "Push": {
            echo 'Pioppo'
            
          },
          "Fail Pioppo": {
            pwd()
            
          }
        )
      }
    }
  }
}