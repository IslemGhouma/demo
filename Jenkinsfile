pipeline {
  agent any
  stages {
  
    stage ("Build application") {
    parallel {
        stage("Build front") {
			steps {
				script { 
                sh """
                 echo "hi,hello"
                """
				}

			}

        }
        
		
        stage("Build back") {
			steps {
				script {
                //In this stage, we build the application
                sh """
                  echo hi
                """
				}
            
			}
          
        }
	}

      }
    }
  }

