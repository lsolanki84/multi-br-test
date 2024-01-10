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
    Stage ('Build Dev') {
          when {
              branch 'dev'
          }
      stage {
        echo "Bulding dev"
      }
    }
  }
  
}
