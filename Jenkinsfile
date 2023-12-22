pipeline {   
    agent any

    stages {   
        stage('Future1 branch') { 
            steps { 
               sh 'echo "This is future1 branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "future1 application..."'
            }
        }

        stage("future1 Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
