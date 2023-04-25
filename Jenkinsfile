pipeline {
    agent any
    parameters {
  choice choices: ['dev', 'sit', 'pt'], name: 'ENV'
}
    stages { 
        stage('working with variable') {
            steps {
              script {
                  a = 10
                  println "my variable value is ${a}"
                  println "my build no is ${BUILD_NUMBER}"
                  println "select parameter is ${params.ENV}"
               
              }
            }
        }
    }
}
