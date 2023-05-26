pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                script{
                    git branch: 'main', changelog: false, poll: false, url: 'https://github.com/amirsubhanidevops/demo-counter-app.git'
                }

            }
        }

        
    }
}