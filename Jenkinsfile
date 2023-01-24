pipeline{
  agent any
  stages{
    
    stage('build'){
      steps{
        javac myfile.java
        java myfile
      }
    }

    stage('test'){
      steps{
        echo 'testing phase'
      }
    }

    stage('deploy'){
      steps{
        echo 'deployment phase'
      }
    }

  }
}
