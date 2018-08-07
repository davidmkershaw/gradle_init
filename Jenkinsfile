pipeline {
    agent {
        docker { image 'library/centos:latest' 
		 registryUrl 'https://nexus.misoenergy.org/repository/releases/'
                 registryCredentialsId 'MISO'

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
