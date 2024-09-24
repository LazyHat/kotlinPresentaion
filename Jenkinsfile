pipeline {
    agent {
        docker {
            image 'gradle:jdk21'
        }
    }

    stages {
        stage('Build') {
            steps {
                sh './gradlew wasmJsBrowserWebpack'
            }
        }
    }
}