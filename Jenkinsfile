pipeline{
    agent any
    stages{
        stage("Build"){
            options{
                retry(3)
            }
            steps {
                echo "====++++something++++===="
                error "====++++super error++++===="
                echo "====++++nothing++++===="

            }
        }

    }
}