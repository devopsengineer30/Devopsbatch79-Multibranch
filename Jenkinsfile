pipeline {   
    agent any

    stages {   
        stage('Sprint1 branch new update') { 
            steps { 
               sh 'echo "This is sprint1 branch new update"' 
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
