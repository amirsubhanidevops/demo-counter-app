pipeline{
    agent any
    stages{
        stage{
            steps{
                script{
                    git branch: 'main', changelog: false, poll: false, url: 'https://github.com/amirsubhanidevops/demo-counter-app.git'
                }

            }
        }
    }
}