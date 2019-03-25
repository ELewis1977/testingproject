pipeline {
	agent any
	
	stages {
	  stage ('GIT Test Project Checkout'){
		steps {
			git 'https://github.com/ELewis1977/RF-testsim.git'
		}
	  }
	  
	  stage ('Testing'){
		steps {
			echo "Start Testing"
		}
	  }
	  
		
	  stage ('Acceptance Testing'){
		steps {
			echo "Acceptance Testing"
		}
	  }
	  
	  stage ('Approval'){
		steps {
			echo "Approval"
		}
	  }
	  
	  stage ('Deployed'){
		steps { 
		  echo "Deploy Completed"
		 }
	  }
	}
}