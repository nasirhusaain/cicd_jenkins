pipeline{
	agent any
	stages {
		stage('Submit Stack') {
			steps {
			sh "aws cloudformation create-stack --stack-name jenkinsStack8 --template-body file://samtemplate.yaml --capabilities CAPABILITY_AUTO_EXPAND --region 'ap-south-1'"
			}
		}
	}
}
