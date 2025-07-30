pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git credentialsId: 'github-creds',
                    url: 'https://github.com/SJK3051/Ansibles-task.git',
                    branch: 'main'
            }
        }
        // your other stages
    }
}

