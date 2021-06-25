pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "hellooo"'
      }
    }

    stage('test') {
      steps {
        sh '''echo "test 1"
echo "test 1.1"'''
        sh 'echo "test 2"'
      }
    }

  }
}