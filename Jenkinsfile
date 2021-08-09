pipeline {
  agent any
  stages {
    stage("Build") { 
      steps {
        echo "run"
     }
    }
    parallel {
      stage ("Test1"){
        steps {
          echo "Testing of Case1"
        }
      }
      stage ("Test2"){
        steps{
          echo "Testing Case2"
        }
      }
    }
    stage("Deploy"){
      steps{
        echo "This is Deploy stage"
      }
    }
  }
}

    
