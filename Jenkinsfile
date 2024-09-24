pipeline {
    agent {
        docker {
            image 'gradle:jdk21'
            reuseNode true
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