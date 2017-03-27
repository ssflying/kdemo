pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh './build.sh'
      }
    }
    stage('deploy-test') {
      steps {
        echo 'echo hello'
      }
    }
    stage('deploy-prd') {
      steps {
        echo 'echo prd'
      }
    }
  }
}