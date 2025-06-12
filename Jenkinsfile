pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'gradlew assemble' // for Windows 
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'gradlew test' // for Windows
            }
        }
    }
}
