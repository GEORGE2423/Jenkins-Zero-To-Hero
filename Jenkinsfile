pipeline {

agent any

stages{

    stage('Git Checkout'){
        steps{
            git branch: 'main', url: 'https://github.com/GEORGE2423/Jenkins-Zero-To-Hero.git'
        }
    }

    stage('UNIT Testing'){
        steps{
            sh 'mvn test'
        }
    }
}

}