pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'python3 helloworld.py'
      }
    }
    stage('Run python'){
      steps {
        sh'python helloworld'
      }
    }
  }
}
