pipeline {
  agent any
  stages {
       stage('Build Master') {
         when {
           branch 'master'
         }
    steps {
      echo "Building master"
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
