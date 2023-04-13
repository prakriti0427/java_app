@Library ('my-shared-library') _
pipeline{

    agent any

    stages {

        stage('Git checkout'){

        
            steps{

                script{

                    gitCheckout{ 
                        branch: "main"
                        url: "https://github.com/prakriti0427/java_app.git"
                    }

                }
            }
    }
        stage('Unit test Maven'){
            steps{
                script{
                    mvnTest
                }

            }
        }
}
}
