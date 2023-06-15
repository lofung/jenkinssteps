pipeline {
  agent any
  stages {
    stage('Write a file') {
      steps {
        writeFile(file: 'status.txt', text: 'hey it worked')
      }
    }

  }
}