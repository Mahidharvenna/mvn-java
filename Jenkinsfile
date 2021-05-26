
pipeline {
    agent { docker { image 'linux' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
