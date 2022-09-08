pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Test'
          }
        }

        stage('Parallel') {
          steps {
            echo 'Parallel Test'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Build Test'
      }
    }

    stage('Clean Up') {
      steps {
        echo 'Clean Up'
      }
    }

  }
}