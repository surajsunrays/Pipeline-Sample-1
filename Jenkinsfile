pipeline{
    agent any
    stages{
        stage('Initiating'){
            when{
                branch 'master'
            }
            steps
            {
                echo "This will execute master branch ----- Because Test Message is True...."
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
    }    
}
