pipeline {
    agent any
    environment {
        DEPLOY = "prod"
    }
        stages {
            stage("prod"){
                when {
                    environment name: "DEPLOY", value: "prod"
                }
                steps{
                    echo "Deployed to production"
                }
            }
        }

}