node {

stage('Mvn Package'){

git 'https://github.com/lavakummarr/myapp'

}

stage('Mvn Package'){
	   // Build using maven
script
{

def mvn = tool name: 'Maven 3', type: 'maven'

 sh "${mvn}/bin/mvn clean package "

}

}

}
