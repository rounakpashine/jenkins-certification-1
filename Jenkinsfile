pipeline {
  agent any
  stages {
    stage('1a') {
      parallel {
        stage('1') {
          agent any
          steps {
            echo 'Asia'
          }
        }

        stage('1b') {
          steps {
            echo 'Europe'
          }
        }

      }
    }

    stage('2a') {
      parallel {
        stage('2a') {
          agent any
          steps {
            echo 'India'
          }
        }

        stage('2b') {
          steps {
            echo 'Spain'
          }
        }

      }
    }

  }
}