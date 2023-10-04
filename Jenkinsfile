pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(activity: true, time: 5, unit: 'SECONDS') {
          sh 'slep 10 seconds'
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
