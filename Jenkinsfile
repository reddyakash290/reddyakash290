pipeline {
    agent any

    stages {
        stage('run python script') {
            steps {
                echo 'above script ${env.WORKSPACE}'
                sh 'python3 hello.py'
            }
        }
    }
}
