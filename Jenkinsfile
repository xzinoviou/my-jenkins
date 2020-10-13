pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                echo '[--- Building step ---]'
                sleep 8
                echo 'Finished Building'
                echo "STEP : END"
                
            }
    }
    
    stage('Test'){
        steps{
            echo '[--- Running tests ---]'
                sleep 5
                echo 'Finished Running tests'
                echo "STEP : END"
        }
    }
    
    stage('Staging'){
        steps{
            echo '[--- Staging ---]'
                sleep 5
                echo 'Finished Staging'
                echo "STEP : END"
        }
    }
    
    stage('Deploy'){
        steps{
            echo '[--- Deploying ---]'
                sleep 5
                echo 'Finished Deploying'
                echo "STEP : END"
        }
    }
  }
}
