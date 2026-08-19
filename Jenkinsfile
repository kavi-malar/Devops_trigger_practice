pipeline {
    agent any

    stages {
        stage('Test Trigger') {
            steps {
                bat 'echo Jenkins trigger worked!'
            }
        }

        stage('Show Information') {
            steps {
                bat 'echo Build Number: %BUILD_NUMBER%'
            }
        }
    }
}