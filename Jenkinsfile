pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        sh 'javac helloworld.jav'
      }
    }
    stage('Run'){
      steps{
        sh'java helloworld'
      }
    }
  }
}
