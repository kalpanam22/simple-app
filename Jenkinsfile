pipeline{
    agent any
    tools{
        maven 'maven-3'
    }
    stages{
        stage('Builld'){
            steps{
                sh  script: 'mvn clean package'
            }
        }
    }
}
