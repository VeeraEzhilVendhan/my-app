pipeline
{
	agent any
	stages
	{
		stage("--clean--")
		{
			steps
			{
				bat "mvn clean"
			}
		}
		stage("--build--")
		{
			steps
			{
				bat "mvn test"
			}
		}
		stage("--test--")
		{
			steps
			{
				bat "mvn package"
			}
		}
	}
}