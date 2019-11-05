pipeline{
    agent any
        stages {
            stage("BUild"){
                tools {
                    maven 'localMaven'
                }
                steps{
                    sh "mvn --version"
                }
            }
        }
}