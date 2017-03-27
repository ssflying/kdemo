pipeline {
  agent any
  stages {
    stage('prepare env') {
      steps {
        tool(name: 'Go 1.8', type: 'go')
      }
    }
    stage('build') {
      steps {
        sh 'bash ./build.sh'
      }
    }
  }
}