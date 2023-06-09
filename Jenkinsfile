pipeline {
    agent any
 
        stage('Maven build') {
            steps {
                echo 'Successfull'
                 sh '''
                    ls -la
                    cat README.md
                '''
    
            }
        }
        
        stage('Sonarqube Code Testing') {
            steps {
                echo 'Successfull'
    
            }
        }
        
        stage('Docker Image Build') {
            steps {
                echo 'Successfull'
    
            }
        }
        
        stage('Coverity Security check ') {
            steps {
                echo 'Successfull'
    
            }
        }
        
         stage('Approval') {
            steps {
                input(message: 'Approve the deployment?', submitter: 'devlopers', submitterParameter: 'APPROVER')
            }
        }
        
         stage('Deploy image') {
            steps {
                echo 'Successfull'
    
            }
        }
        
        stage('Operate Deployments') {
            steps {
                echo 'Successfull'
    
            }
        }
        
        stage('Monitor Deployments') {
            steps {
                echo 'Successfull'
    
            }
        }
    }
}       
