pipeline{
    agent any
    tools{
        maven 'maven3'
    }
    stages{
        stage('Builld'){
            steps{
                sh  script: 'mvn clean package'
            }
        }
    }
}