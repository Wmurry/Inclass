pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        echo 'Hello World'
      }
    }
    stage('Maven Step') {
      steps {
        sh 'nvm clean package -DskipTests'
      }
    }
  }
}