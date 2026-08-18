pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'pyc helloworld.py'
      }
    }
    stage('Run'){
      steps {
        sh'py helloworld'
      }
    }
  }
}
