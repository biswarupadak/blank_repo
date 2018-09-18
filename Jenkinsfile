pipeline {
  agent any
  stages {
    stage('Stage1 Log pull') {
      steps {
        echo 'Starting log pull from Stage1 app servers'
      }
    }
    stage('Input') {
      steps {
        input(message: 'xxxx', id: 'qqqq', submitter: 'Admin')
      }
    }
  }
}