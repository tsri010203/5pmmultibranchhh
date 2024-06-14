node('built-in') 
{
    stage('Continuous Download') 
	{
	git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
	}
}
