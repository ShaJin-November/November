pipeline {
  agent {
    node {
      label 'ALDNDEVC'
    }

  }
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            echo 'hello'
          }
        }

        stage('second') {
          steps {
            sh 'system -kpeb dsplibl'
          }
        }

      }
    }

  }
}