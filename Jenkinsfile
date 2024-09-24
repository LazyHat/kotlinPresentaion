pipeline {
    agent {
        docker {
            image 'openjdk:21'
        }
    }

    stages {
        stage('Build') {
            steps {
                sh 'java --version'
                sh './gradlew --version'
            }
        }
    }
}