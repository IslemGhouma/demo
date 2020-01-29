pipeline {
  agent any
  options {
		disableConcurrentBuilds()
    }

  stages {
    
    stage ("hello") {

      steps {
        script {
          currentBuild.displayName = BUILD_NUMBER + "/" + GIT_BRANCH
          sh """

            echo "he00"


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
