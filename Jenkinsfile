def myfn(){
    println "Hi all, welcome to dvs"    
}
def myfn(a,b){
    sum=a+b
    println "sum of ${a} & ${b} is, ${sum}"
}
pipeline{
  agent any
  stages {
      stage('working with function') {
        steps {
          script {
            myfn()
            myfn(10,20)
            myfn(300,400)

            }
            }
            
        }
     }   }
