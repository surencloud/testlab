pipeline {
  agent any
  tools {
    maven 'MAVEN_HOME'
    jdk 'JAVA_HOME'
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
            sh 'mvn clean package'
      }
    }
  }
}