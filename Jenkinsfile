pipeline {
    agent {
        docker { image 'gradle:jre10' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'gradle -version'
            }
        }
    }
}
