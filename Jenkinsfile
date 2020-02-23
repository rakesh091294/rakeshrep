pipeline {
  agent any
  stages {
    stage('stage 2') {
      parallel {
        stage('stage 2') {
          steps {
            sh 'echo "done"'
          }
        }

        stage('2.1') {
          steps {
            sh 'echo "how are you"'
          }
        }

      }
    }

  }
}