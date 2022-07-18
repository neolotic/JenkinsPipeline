pipeline {
	agent any 
	stages{
	stage (‘My first Jenkins Pipeline’)
		steps{
			sh echo "hi! I’m Jenkins Pipeline"
			}

		}

}
