pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git branch: 'main', url: 'https://github.com/devopsfaisal/demo-counter-app.git'
            }
        }
    }
}