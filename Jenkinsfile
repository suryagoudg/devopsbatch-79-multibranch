pipeline {   
    agent any

    stages {   
        stage('Master branch latest 123') { 
            steps { 
               sh 'echo "This is master branch latest 123..."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
