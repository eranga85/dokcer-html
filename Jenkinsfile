pipeline{
    agent any
    tools {dockerTool  "docker" } 
    
    node {
    sh "id"
    sh "echo $PATH"
    sh "docker ps"
    docker.image("node:latest").inside("") { c ->
        sh "npm --version"
        }
    }
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
