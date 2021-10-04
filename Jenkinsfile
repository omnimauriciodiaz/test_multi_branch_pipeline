pipeline{
    agent any
    stages{
        stage('Stage 1'){
            steps{
                echo 'Init all'
                echo 'Loading'
            }
        }
        stage('Stage 2'){
            steps{
                echo 'Calculating...'
                script{
                    def var = 1 + 1 < 2 ? 'Result True way': 'Result False Way'
                    echo var
                }
            }
        }
        stage('End stage'){
            steps{
                echo 'Close all'
            }
        }
    }
}
