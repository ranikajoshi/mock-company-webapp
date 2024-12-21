pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Build the project
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // Run tests
                sh './gradlew test'
            }
        }
    }
}
