pipeline {
   agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('python version') {
            steps {
                sh "python --version"
            }
        }
    }
}
