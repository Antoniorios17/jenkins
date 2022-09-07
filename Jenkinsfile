pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO tyrone"'
      sh '''
        echo "Welcome to B2"
        uname -a 
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO sanderson"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
