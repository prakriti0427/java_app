@Library('my-shared-library') _
pipeline{

    agent any

    stages {

        stage('Git checkout'){
           steps{
           gitCheckout( 
                        branch: "main",
                        url: "https://github.com/prakriti0427/java_app.git"
           )
                }
            }
        stage('unit maven test'){
            steps{
                script{
                mvnTest()
            }
        }
    }
}