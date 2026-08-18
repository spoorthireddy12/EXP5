pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        sh 'javac hello world.java'
      }
    }
    stage('Run'){
      steps{
        sh'java hello world'
      }
    }
  }
}
