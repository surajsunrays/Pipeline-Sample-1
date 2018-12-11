pipeline{
    agent any
    stages{
        stage('Initiating'){
            steps
            {
                script
                {
                    if (env.BRANCH_NAME == 'master') 
                    {
                        echo 'I only execute on the master branch'
                    } 
                    else 
                    {
                        echo 'I execute elsewhere'
                    }
                }
            }
              
            
        }
        stage('Validating'){
            steps
            {
                echo "Starting Validation Process"
            }
            
        }
        stage('Compiling'){
            steps
            {
                echo "Starting Compiling process"
            }
            
        }
        stage('Testing'){
            steps
            {
                echo "Starting Testing Process"
            }
            
        }
        stage('Packaging'){
            steps
            {
                echo "Starting Packaging Process"    
            }
            
        }
        stage('Deploying'){
            steps
            {
                echo "Starting Depolying Process"
            }
            
        }
    }    
}