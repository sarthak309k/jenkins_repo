pipeline{
	agent any	
	stages{
		stage("Clean")
		{
		  steps{echo "clean the project"
			bat "mvn -version"
			bat "java -version"
			echo "Trigger Sample11"
			echo "Updated Trigger"
			bat "javac -version"
			}
		}
  }
}
