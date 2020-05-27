pipeline {
  agent any
  stages {
    stage('jenkinstage1') {
      parallel {
        stage('jenkinstage1') {
          steps {
            echo 'hi'
          }
        }

        stage('') {
          steps {
            echo 'hello'
          }
        }

      }
    }

    stage('stage2') {
      steps {
        echo 'stage two'
      }
    }

  }
}