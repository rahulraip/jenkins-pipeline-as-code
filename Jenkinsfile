pipeline {

agent any  

stages {

	stage('SCM') {
		steps {
			echo "step1 git pull my code"
			echo "step2 perform something"
			echo "step3 perform something"
		}
	}

	stage('Deploy') {
		steps {
			echo "deploying my code"
		}
	}

	stage('Test') {
		steps {
			echo "test my final webapp"
		}
	}

}

}

