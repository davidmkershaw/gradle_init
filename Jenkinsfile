pipeline {
    agent {
        docker { image 'gradle:alpine' }
    }
    stages {
        stage('Test') {
            steps {
               gradle -v
            }
        }
    }
}
