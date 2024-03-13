pipeline {
  agent any
  stages {
    stage('Maven Build') {
      when {
        branch "develop"
      }
      steps {
        sh "mvn clean package"
      }
    }
    stage('Dev Deploy') {
      when {
        brnach "develop"
      }
      steps {
        echo "deploy to Dev server"
      }
    }
    stage('Test Deploy') {
       when {
        brnach "test"
      }
      steps {
        sh "deploy to Test server"
      }
    }
    stage('Prod Deploy') {
       when {
        brnach "main"
      }
      steps {
        sh "deploy to Prod server"
      }
    }
  }
}
