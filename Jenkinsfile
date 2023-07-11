pipeline{

    agent any
    
    stages{
    
        stage('Build'){
        
                steps{ 
                    echo "This Pipeline is working"
                }
                steps{
                    echo "The second line of the Main branch"
                    sh 'hostname -i'
                }
            }
        }

}
