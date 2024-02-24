pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Lohithreddy-k/Ubuntu_jenkins.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "zip karthi.zip main.py"
				}
			}
		}
	}
