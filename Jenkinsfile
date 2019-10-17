pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'echo "Database engine is ${DB_ENGINE}"'
                sh 'echo "DISABLE_AUTH is ${DISABLE_AUTH}"'
            }
        }
    }
}