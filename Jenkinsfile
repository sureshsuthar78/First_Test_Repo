pipeline {
  agent any
  stages {
    stage('Admin') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'hiii this is msg'
            echo 'ths is second msg'
          }
        }

        stage('Stage2') {
          steps {
            echo 'Hi from stage 2'
            echo 'ths is second msg from stage2'
          }
        }

      }
    }

  }
}