pipeline {
  agent any
  stages {
    stage('Write a file') {
      steps {
        dir(path: '/java-web-project/src/main/webapp/') {
          writeFile(text: '<html> <body> <h2>Good afternoon, LAUKK, Welcome to COMP367</h2> </body> </html>', file: 'index2.jsp')
        }

      }
    }

  }
}