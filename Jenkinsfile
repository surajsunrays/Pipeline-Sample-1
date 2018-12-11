pipeline{
    agent any
    stages{
        stage('Initiating'){
            when{
                branch 'master'
            }
            steps
            {
                echo "This will execute master branch"
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
        stage ('Test 3: Master') {
            when 
                { 
                    branch 'master' 
                }
            steps 
            { 
            echo 'I only execute on the master branch.' 
            }
        }

        stage ('Test 3: Dev') {
            when 
                { 
                    not 
                    { 
                        branch 'master' 
                    } 
                    
                }
            steps 
                {
                    echo 'I execute on non-master branches.'
                }
        }
    }    
}