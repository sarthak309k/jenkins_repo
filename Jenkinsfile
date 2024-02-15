pipeline{
	agent any	
	stages{
		stage("Clean")
		{
		  steps{echo "clean the project"
			bat "mvn -version"
			bat "java -version"
			}
		}
  }
}
