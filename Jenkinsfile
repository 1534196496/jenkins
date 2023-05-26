pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            echo 'hello step1'
          }
        }

        stage('step2') {
          steps {
            echo 'step2'
          }
        }

      }
    }

  }
}