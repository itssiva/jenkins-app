pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'ech "apple"'
                sh 'echo "HELLO"'
            }
        }
    }
}