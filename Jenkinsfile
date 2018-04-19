pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'HELLO'
          }
        }
        stage('test5') {
          steps {
            echo 'CAC'
          }
        }
      }
    }
    stage('test2') {
      steps {
        echo 'WORLD'
      }
    }
    stage('test3') {
      steps {
        echo 'ACCEL'
      }
    }
    stage('test4') {
      steps {
        echo 'JAPAN'
      }
    }
  }
}