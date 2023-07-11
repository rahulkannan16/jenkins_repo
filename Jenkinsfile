pipeline{
    agent any

    stages{
    
        stage('Build'){
                steps{
                    echo "This Pipeline is working"
                    }
                 }
        stage('Test'){
            steps{
                sh 'hostname -i'
                echo "This line is in master branch"
                echo "The username of this machine is ${hostname}"
            }
        }
        }

}
