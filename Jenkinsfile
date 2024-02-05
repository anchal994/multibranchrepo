pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact from Branch1"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code from Branch1"
               """
          }
      }
   }
}
