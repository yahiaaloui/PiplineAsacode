pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(time: 5, unit: 'SECONDS') {
          sh 'slep 2 seconds'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing completed'
      }
    }

  }
}
