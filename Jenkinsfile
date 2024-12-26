pipeline{
  agent any
  stages{
    stage('Breakfast'){
      steps{
        echo " Its breakfast time"
      }
    }
    stage('Workout'){
      steps{
        echo " Its Workout time"
      }
    }
    stage('Study'){
      steps{
        echo " Its Study time"
      }
    }
    stage('Family time'){
      steps{
        echo " Its family time"
      }
    }
    stage('Play'){
      steps{
        echo " Its playing time"
      }
    }
  }
  post{
    success{
      echo "Day spent well"
    }
    failure{
      echo "Day didn't spend well"
    }
  }
}
