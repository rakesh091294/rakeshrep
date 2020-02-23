pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'hello'
          }
        }

        stage('stage 1.1') {
          steps {
            sh 'echo "pipeline example"'
          }
        }

      }
    }

    stage('stage 2') {
      steps {
        echo 'complete'
      }
    }

  }
}