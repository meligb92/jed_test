pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }
    
  }
  stages {
    stage('Example Build') {
      steps {
        sh 'mvn --version'
        echo 'Hello, Maven'
      }
    }
    stage('Example Test') {
      steps {
        echo 'Hello, JDK'
      }
    }
  }
}