pipeline {
  agent any
  stages {
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