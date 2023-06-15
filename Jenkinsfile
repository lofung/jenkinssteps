pipeline {
  agent any
  stages {
    stage('log tools version') {
      parallel {
        stage('log tools version') {
          steps {
            sh '''mvn --version
git --version
java --verison'''
          }
        }

        stage('Check for POM') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

    stage('build with maven') {
      steps {
        sh 'mvn compile test package'
      }
    }

    stage('Write a file') {
      steps {
        writeFile(file: 'status.txt', text: 'hey it worked')
      }
    }

  }
}