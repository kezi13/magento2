pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        git(poll: true, url: 'git@github.com:kezi13/magento2.git', branch: 'master')
      }
    }

    stage('hi') {
      steps {
        sh 'echo "hello world"'
      }
    }

  }
}