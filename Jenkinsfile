pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh './gradlew assemble' // for Unix/Linux/Mac
                // bat 'gradlew assemble' // if you're using Windows with bat support
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './gradlew test' // for Unix/Linux/Mac
                // bat 'gradlew test' // for Windows
            }
        }
    }
}
