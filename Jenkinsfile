pipeline {
  agent any

  stages {
    
    stage ("hello") {

      steps {
        
        script {
          currentBuild.displayName = BUILD_NUMBER + "/" + GIT_BRANCH
          sh """
            echo "hello wacefff"
          """
        }
      }
    }  
    stage ("hi") {

      steps {
        script {
          sh """
            echo "hi"
          """
        }
      }
    }

   
  }
}
