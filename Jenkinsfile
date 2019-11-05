pipeline{
    agent any
        stages{
            stage("Build"){
                steps{
                    retry(3){
                        timeout(time: 1, unit: 'SECONDS')   
                        {
                        sleep2
                        }
                    echo "after timeout"
                }
            }
        }
    }
}