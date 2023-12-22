pipeline {   
    agent any

    stages {   
        stage('Future2 branch') { 
            steps { 
               sh 'echo "This is future2 branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "future2 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
