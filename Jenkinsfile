pipeline {
 agent any
	 stages {
		 stage('for the PR'){
			when{
				branch 'PR-*'
			}
			steps{
				echo 'this only runow for the PRs'
			}
		}
	}  
}





