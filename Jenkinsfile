pipeline {
  agent any
  stages {
    stage('Write a file') {
      steps {
        dir(path: '/src/main /webapp/')
        writeFile(file: 'index.jsp', text: '<html> <body> <h2>Good afternoon, LAUKK, Welcome to COMP367</h2> </body> </html>')
      }
    }

  }
}