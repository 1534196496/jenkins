pipeline {
  agent any
  stages {
    stage('Print Environment Variables') {
      steps {
        script {
          env.each { key, value ->
          echo "${key}=${value}"
        }
      }

    }
  }

}
}