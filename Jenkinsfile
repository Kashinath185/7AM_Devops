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
        sh 'docker info | grep -i version'
      }
    }

  }
}