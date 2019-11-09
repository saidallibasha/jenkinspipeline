pipeline {
    agent any
    environment {
        DEPLOY = "prod"
    }
        stages {
            stage("prod"){
                when {
                    environment name: "DEPLO", value: "prod"
                }
                steps{
                    echo "Deployed to production"
                }
            }
        }

}