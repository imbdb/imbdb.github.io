pipeline {
  agent {
    node {
      label 'bharat.env'
    }

  }
  stages {
    stage('test') {
      agent {
        node {
          label 'sergerg'
        }

      }
      steps {
        sh 'echo"test"'
      }
    }

  }
}