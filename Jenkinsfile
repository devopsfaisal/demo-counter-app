pipeline{
    agent any
    stage{
        stages("Git Checkout"){
            steps{
                git branch: 'main', url: 'https://github.com/devopsfaisal/demo-counter-app.git'
            }
        }
    }
}