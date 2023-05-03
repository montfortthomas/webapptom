pipeline{
 agent 3.110.134.95
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
     sh "pwd"
     sh "ls"
    }
   }
  
  }
 
}
