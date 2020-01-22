pipeline {
  agent any

  stages {
    
    stage ("hello") {

      steps {
        currentBuild.displayName = BUILD_NUMBER + "/" + GIT_BRANCH
        script {
          sh """
            echo "hello wacef"
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
