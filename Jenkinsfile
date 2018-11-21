node('master') {

	stage('git clone') {
		git 'https://github.com/rahul619302/spring-boot-with-junit.git'
	}
	stage('maven build') {
		sh 'mvn compile package'
	}

}