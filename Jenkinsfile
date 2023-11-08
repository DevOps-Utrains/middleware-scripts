pipeline {
    agent any
    triggers {
  pollSCM ('* * * * *')
}


    stages{
        stage("build"){
            steps{
                echo "build"
            }
        }
        stage("test"){
            steps{
                echo "test"
            }
        }
        stage("deploy"){
            steps{
                echo "deploy"
            }
        }
    }
}