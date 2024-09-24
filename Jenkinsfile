pipeline {
    agent {
        docker {
            image 'gradle:jdk21'
        }
    }

    stages {
        stage('Builde') {
            steps {
                sh 'java --version'
                sh './gradlew --version'
            }
        }
    }
}