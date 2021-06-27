pipeline {
  agent any
  stages {
    stage('checkout SCM') {
      steps {
        git(url: 'git@github.com:vishnutheja88/vishnu_pipeline1.git', branch: 'main')
      }
    }

    stage('build') {
      steps {
        sh 'ls -lrt'
      }
    }

    stage('upload') {
      steps {
        sh 'ls'
      }
    }

    stage('deploy') {
      steps {
        sh 'ls'
      }
    }

  }
}