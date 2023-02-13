pipeline {
  agent any
  tools {
    maven 'maven3.8.6'
    jdk 'jdk17'
  }
  stages {
    stage ('Initialize') {
                steps {
                    sh '''
                        echo "PATH = ${PATH}"
                    '''
                }
            }
    stage ('Build') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}