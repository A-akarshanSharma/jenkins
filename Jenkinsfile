pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'  // Use 'bat' for Windows
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
