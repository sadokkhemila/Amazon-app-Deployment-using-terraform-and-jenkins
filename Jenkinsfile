pipeline {
    agent any

    stages {
        stage('clean workspace'){
            steps{
                cleanWs()
            }
        }
        stage('checkout from git ') {
            steps {
                git branch: 'main' , URL: 'https://github.com/Aakibgithuber/Amazon-app-Deployment-using-terraform-and-jenkins.git'
            }
        }
    }
}
