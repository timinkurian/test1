pipeline {
  agent any
  stages {
    stage('Step1') {
      parallel {
        stage('Step1') {
          steps {
            echo 'execution started'
          }
        }

        stage('stage2') {
          steps {
            echo 'stage 2 completed'
          }
        }

      }
    }

  }
}