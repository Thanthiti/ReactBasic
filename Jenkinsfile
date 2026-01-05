pipeline{
    agent any
    stages{
        stage('Hello word'){
            steps {
                bat 'echo hello word'
            }
        }
        stage('Build'){
            steps{
                bat 'mvn clean install'
            }
        
        }
    }
}