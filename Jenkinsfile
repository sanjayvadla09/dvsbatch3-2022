pipeline {
    agent any
    stages { 
        stage('working with variable') {
            steps {
              script {
                  a = 10
                  println "my variable value is ${a}"
                  println "my build no is ${BUILD_NUMBER}"
                  println "my tag date is ${TAG_DATE}"
              }
            }
        }
    }
}
