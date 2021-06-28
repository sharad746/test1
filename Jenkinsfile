pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "hellooo"'
        emailext(subject: 'Build Status', body: 'This is build.', attachLog: true, to: 'sharad@moco.com.np', from: 'documentmanagement07@gmail.com')
      }
    }

    stage('test') {
      steps {
        sh 'echo "test 1"'
        sh 'echo "test 2"'
      }
    }

  }
}