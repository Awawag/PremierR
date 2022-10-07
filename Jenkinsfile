node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/Awawag/PremierR.git'
    
    }
    stage('Build') {
        sh 'javac Main.java'
    
   }
   stage('Run') {
       sh 'java Main'
    
  }
}
