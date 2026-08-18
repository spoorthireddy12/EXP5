pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'pythonc helloworld.py'
      }
    }
    stage('Run'){
      steps {
        sh'python helloworld'
      }
    }
  }
}
