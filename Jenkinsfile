pipeline{
    agent any
    stages{
        stage('Initiating'){
            when{
                branch 'master'
            }
            steps
            {
                echo "Current branch is Master branch...."
            }
            echo "Current branch is not a master Branch"
            
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