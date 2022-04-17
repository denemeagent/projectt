pipeline {
    agent {label 'docker'}
    stages{
        stage("deneme"){
            steps{
                sh 'echo hi'
            }
        }
    }
    post{
        success{
            sh 'git status'
            sh 'echo bitti'
        }
    }
}
