node('built-in') 
{
    stage('Continuous Download_pammu') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_pammu') 
	{
    sh label: '', script: 'mvn package'
	}
}
