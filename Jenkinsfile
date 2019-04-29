pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/home/ranjeet/Downloads/apache-maven-3.6.1/bin/mvn clean'
      }
    }
    stage('Test') {
      steps {
        sh '/home/ranjeet/Downloads/apache-maven-3.6.1/bin/mvn test'
      }
    }
    stage('Deploy') {
      steps {
        sh '/home/ranjeet/Downloads/apache-maven-3.6.1/bin/mvn package'
      }
    }
  }
}
