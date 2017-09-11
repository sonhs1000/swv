pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "Hello Message": {
            echo 'Hello'
            
          },
          "Time Delay": {
            timeout(time: 10)
            echo 'Ho'
            
          }
        )
      }
    }
    stage('Final Statge') {
      steps {
        echo 'Finall round'
      }
    }
  }
}