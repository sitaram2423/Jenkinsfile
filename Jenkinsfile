pipeline{
    
    agent any
    
    stages{
        stage('build-job'){
            
            steps{
                sh 'date'
               }
            }

        stage('test-job'){
                 steps{
                     
                     sh 'hostname'
                 }   
        }
        stage('deploy-job'){
            steps{
                sh 'ls -l /tmp'
                }
        }
    }
    }
