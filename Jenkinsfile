pipeline{
 agent any
  stages {
    stage('loginn') {
      steps{
         sshagent(['Tomcatt']) {
    // some block
}
      }
    }
   stage('create'){
    steps {
     sh "touch test1.txt"
    }
   }
  
  }
 
}
