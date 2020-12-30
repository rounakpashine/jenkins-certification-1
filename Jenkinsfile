pipeline {
  agent any
  stages {
    stage('1') {
      agent {
        docker {
          image 'busybox:latest'
        }

      }
      steps {
        sh 'echo "Hello World!!"'
      }
    }

    stage('2') {
      agent any
      steps {
        sh 'echo "step 2"'
      }
    }

  }
}