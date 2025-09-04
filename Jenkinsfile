pipeline {
    agent any
    stages {
        stage ( "checking out the code from github") {
            steps {
                sh 'echo "checking out the code from github"'
            }
        }
        stage ("Building the code using appropriate tools") {
            steps {
                sh 'echo "Here we are building the code using appropriate tools"'
                sh 'echo "Your code is successfully build and ready to test"'
            }
        }
        stage ("Testing the code") {
            steps {
                sh 'echo "Testing the code using SonarQube"'
                sh 'echo "Your code has passed the SonarQube testing and now ready to deploy"'
            }
        }
        stage ("checking github integration") {
            steps {
                sh 'echo "If this build runs it means jenkins is checking it every 5 minute"'
            }
        }
        stage ("Deploy to Production") {
            steps {
                sh 'echo "Now deploying the code to the production"'
                sh 'echo "Your code has been deployed to the production successfully."'
            }
        }
        stage ("DevOps Note") {
            steps {
                sh 'echo "Hello Team, You can check your application on web"'
                sh 'echo "Thank You."'
            }
        }
    }
}
