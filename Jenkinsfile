pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps{
      echo "Hello World"
      }
    }
    stage('Git Chekout') {
      steps{
      git url:"https://github.com/saibasanta1988/ai-leads", branch:"main"
      }
    }
  }
}
