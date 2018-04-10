library 'SharedLibs'

pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('') {
      steps {
        sh 'mvn -v'
      }
    }
   stage('Shared Lib') {
       steps {
           helloWorld("Jenkins")
       }
   }
  }
}
