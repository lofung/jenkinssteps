pipeline {
    agent any

    stages {
        stage('Build') {
            steps {

                dir('java-web-project') {
                    // Build the Maven project
                    bat 'mvn clean package'
                }
            }
        }
    }
}
