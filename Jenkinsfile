pipeline{
    agent any
    stages{
        stage("Build"){
            options{
                retry(3)
            }
            steps {
                echo "====++++something++++===="
                script{
                    currentBuild.result = 'FAILURE'
                }
                
                echo "====++++nothing++++===="

            }
        }

    }
}