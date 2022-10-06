pipeline {
  agent any
  stages {
    stage('yo') {
      agent {
        node {
          label 'java7'
        }

      }
      steps {
        echo 'a'
      }
    }

  }
}