pipeline{
  agent any
  stage {
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
