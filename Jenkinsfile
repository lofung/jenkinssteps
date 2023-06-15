pipeline {
    agent any

    stages {
        stage('Build') {
            steps {

                // Build the Maven project
                bat 'mvn clean package'
            }
        }
    }
}
