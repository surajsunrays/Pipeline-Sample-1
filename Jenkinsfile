pipeline{
    agent any
    stages{
        stage('Initiating'){
            when 
            {
                not{
                    branch 'master'
                }
            }
            steps
            {
                echo "This will execute master branch ----- Because Test Message is True...."
            }
            
        }
        stage('Validating'){
            when
            {
                expression { def res=1+2 }
            }
            steps
            {
                echo "Starting Validation Process"
                println(res)
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
    }    
}
