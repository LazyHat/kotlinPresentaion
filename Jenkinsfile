pipeline {
    agent {
        docker {
            image 'gradle:jdk21'
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