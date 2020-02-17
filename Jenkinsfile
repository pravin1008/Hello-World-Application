pipeline {
    agent any
    
  stages {
    stage("Build") {
       steps {
        echo 'Hello, World!.....'
           echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE.NAME} and JOB ${env.JOB_NAME}"
           
       }
   }
      stage ("Test") {
          steps {
          echo 'Testing......'
          }
      }
      
      stage ("Deploy"){
          steps {
       echo "deploying......"
          }
      }
 } // End of stages
} // End of pipeline
