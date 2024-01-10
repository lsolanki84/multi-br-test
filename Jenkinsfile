pipeline {
  agent any
  stages {
       stage('Build main') {
         when {
           branch 'main'
         }
    steps {
      echo "Building main"
    }
       }
    stage('Build Dev') {
          when {
              branch 'dev'
          }
      steps {
        echo "Bulding dev"
      }
    }
  }
  
}
