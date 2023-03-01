pipeline{
    agent any
    
    parameters {
            choice choices: ['C-Project', 'J-Project'], name: 'Job'
                }
    stages {
        stage ('C-Project')
        {
            steps{
                sh'''
                echo "This is to build C-Project"
                '''
            }
        }
        stage ('J-Project')
        {
            steps{
                sh'''
                echo "This is to build J-Project"
                '''
            }
        }
      }
    }  
