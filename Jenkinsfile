pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo env'
            echo 'stage1  step2'
          }
        }

        stage('stage2') {
          steps {
            echo 'stage2 step1'
            echo 'stage2 step2'
          }
        }

      }
    }

  }
}