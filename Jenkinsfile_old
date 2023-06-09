pipeline {
    agent any
 
    stages {
        stage('Maven Build') {
            steps {
                sh 'echo "build completed"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -la
                    df -h
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
