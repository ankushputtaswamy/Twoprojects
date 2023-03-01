pipeline{
    agent any
    
    environment {
  MASTER_URL = "172.31.41.133"
}

    stages {
        stage ('BUILD')
        {
            steps{
                sh'''
                echo "This is to build C-Project in $MASTER_URL"
                '''
            }
        }
        stage ('J-Project')
        {
            steps{
                sh'''
                echo "This is to build J-Project in MASTER_URL"
                '''
            }
        }
      }
    }  
