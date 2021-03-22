node{
    stage('Git Checkout'){
		git credentialsId: 'github', 
		    url: 'https://github.com/GitHubInfo-India/Java-webapp-test/complete'
	}
	
	stage('Maven Build'){
		sh 'mvn clean package'
	}
}
