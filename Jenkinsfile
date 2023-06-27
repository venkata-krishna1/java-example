pipeline {
    agent any
    stages {
  stage('checkout') {
    steps {
      git branch: 'main', url: 'https://github.com/venkata-krishna1/java-example.git'
    }
  }

  stage('build') {
    steps {
      sh 'mvn clean install'
    }
  }

}

}
