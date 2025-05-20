pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running Gradle Build...'
                sh './gradlew assemble'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Unit Tests...'
                sh './gradlew test'
            }
        }
    }
}

