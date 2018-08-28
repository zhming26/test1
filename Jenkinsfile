pipeline {
  agent any
  stages {
    stage('print 1') {
      steps {
        echo 'ni hao , test 1'
      }
    }
    stage('build') {
      steps {
        sh 'echo \'build start ...\''
      }
    }
    stage('sleep') {
      steps {
        sleep 10
      }
    }
    stage('haha') {
      steps {
        echo 'hahah'
      }
    }
  }
  environment {
    ENV = 'prod'
  }
}