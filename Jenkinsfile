pipeline{
    agent any

    stages {
        stage {'Git checkout stage'}
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/prakriti0427/java_app.git'
                }
            }
    }
}