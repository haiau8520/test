pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
		sh 'echo 123'
            }
        }
    }
}


