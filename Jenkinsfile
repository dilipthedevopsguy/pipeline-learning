pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''

pwd






date

'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test step'
          }
        }

        stage('paralell') {
          steps {
            echo 'fu'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}