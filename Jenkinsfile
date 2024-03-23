pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-clde') {
            steps {
                git branch: 'main', url: 'https://github.com/R005/tweet-trend-new.git'
            }
        }
    }
}