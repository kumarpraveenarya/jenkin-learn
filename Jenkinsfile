pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building'
          }
        }

        stage('Parallel Build') {
          steps {
            echo 'Parrallel'
          }
        }

      }
    }

    stage('Testing') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}