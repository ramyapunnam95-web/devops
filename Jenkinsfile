pipeline {
  agent any
  stages{
    stage('working with fileOperation') {
      steps{
        script{
          File file = new File("/opt/mydata.txt")
          def lines = file.readLines()
          println "Lines\n ${lines}"
          for (line in line) {
            println "myline is ${line}"
          }

                }
            }
        }
    }
}
