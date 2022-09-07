pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO Sammy"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO Cespedes"'
      sh '''
        echo "This is testing"
        pwd
        '''
      }
    }
  }
}
