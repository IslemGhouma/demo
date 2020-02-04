pipeline {
  agent any
  stages {
  
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
    
    stage("Build front") {
		steps {
			script { 
               def regex = "timeout"
               if (manager.logContains(regexp)){
               error ("test skipped")
                   }
				}

			}

        }
        

    }
  }
