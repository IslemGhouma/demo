pipeline {
  agent any

  stages {
    
    stage ("hello") {

      steps {
        script {
          currentBuild.displayName = BUILD_NUMBER + "/" + GIT_BRANCH
          sh """
            echo "heloo000"
          """
        }
      }
    }  
    stage ("hi") {

      steps {
        script {
          sh """
            echo "hiiiiiiii"
          """
        }
      }
    }

   
  }
}
