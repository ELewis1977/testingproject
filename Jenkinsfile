pipeline {
	agent any
	
	node {
	  stage ('GIT Test Project Checkout'){
		git 'https://github.com/ELewis1977/RF-testsim.git'
	  }
	  
	  stage ('Testing'){
		echo "Start Testing"
	  }
	  
		
	  stage ('Acceptance Testing'){
			echo "Acceptance Testing"
	  }
	  
	  stage ('Approval'){
		echo "Approval"
	  }
	  
	  stage ('Deployed'){
		  echo "Deploy Completed"
	  }
	}
}