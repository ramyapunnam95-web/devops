pipeline {
  agent any
  parameters {
  choice choices: ['dev', 'prod'], description: 'choose the environment ', name: 'ENV'
  string defaultValue: '1.0.0', description: 'select the version', name: 'version', trim: true
  }
  environment {
  JAVA_HOME = "/usr/bin/java11"
}

  stages {
    stage('working with variables') {
      steps {
         script {
          println "welcome to dvs devops"
          println "my workspace ${WORKSPACE}"
          println "my build no ${BUILD_NUMBER}"

          /*consuming values of parameters*/
          println "my selected environment is ${params.ENV}"
          println "my selected version is ${params.version}"
          /*consuming values of environment*/
          println "my java version is ${env.JAVA_HOME}"
      }

      }
     
    }
  }
}
