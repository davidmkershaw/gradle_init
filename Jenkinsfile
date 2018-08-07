pipeline {
    agent {
        docker { image 'library/centos:latest' 
		 registryUrl 'https://nexus.misoenergy.org:5000'
                 registryCredentialsId '928a74df-a15b-4608-bea3-43f6a49e81e5'

}
    }
    stages {
        stage('Test') {
            steps {
               sh 'echo hi'
            }
        }
    }
}
