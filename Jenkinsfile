pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO .WORLD after webhook  "'
      sh 'echo "Hello"'
      sh '''
        echo "Thi will list current dir content from latest"
        ls -lh
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO TEST"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
