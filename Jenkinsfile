pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is Stage1 step"'
      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "This is Stage2 Step"'
      }
    }

    stage('Depoly') {
      steps {
        sh '''
        echo "This is the 3rd stage"
        echo "Third stage is complete"
        '''
      }
    }

  }
}
