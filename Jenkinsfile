pipeline{
  agent any
  stages {
    stage ("Cleaning Stage"){
      steps {
        echo "Jenkins Clean"
      }
    }
    stage ("Testing Stage") {
      steps {
        echo "jenkins Testing Stage"
      }
    }
    stage ("Packaging Stage") {
      steps {
        echo "Jenkins packaging stage"
      }
    }
	stage ("Email Build status") {
	  steps {
	    mail bcc: '', body: '', cc: '', from: '', replyTo: '', subject: 'Test mail from Jenkins pipeline', to: 'swarnabhd@gmail.com'
		}
		}
  }
}
          
