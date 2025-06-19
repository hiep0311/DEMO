pipeline {
 agent any
 
 stages {
	stage('clone'){
		steps {
			echo 'Cloning source code'
			git branch:'main', url: 'https://github.com/hiep0311/DEMO/'
		}
	} // end clone

  } // end stages
}//end pipeline
