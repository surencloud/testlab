pipeline {
  agent any
  tools {
    maven 'maven3.8.6'
    jdk 'jdk17'
  }
  stages {
    stage ('Build') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}