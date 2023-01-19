pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
withMaven(maven: 'apache-maven-3.8.7') {
       sh 'mvn clean install'
}
      }
    }

  }
}
