@Library('my-shared-library') _

pipeline{

    agent any

    stages{
        stage("Git Checkout"){
            steps{
                script{
                    gitCheckout{
                        branch: "main",
                        url: "https://github.com/RutujaPawal/DevOps-Project-2023.git"
                    }
                }
            }
        }
    }
}