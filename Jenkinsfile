pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building Java App'
          }
        }

        stage('Test') {
          steps {
            echo 'Test Operations'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy the app in server'
      }
    }

  }
}