pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
                cd hello.py
            }
            steps {
            sh "python hello.py"
            }
        }
    }
}
