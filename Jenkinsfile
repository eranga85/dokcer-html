pipeline{
    agent any
    tools {dockerTool  "docker" } 
    stages{
        stage("build"){
            steps{
                echo "========Building the app========"
            }
        }


        stage("test"){
            steps{
                echo "========Testing the app========"
            }
        }

        stage("deploy"){
            steps{
                echo "========Deploying the app========"
            }
        }
    }
}
