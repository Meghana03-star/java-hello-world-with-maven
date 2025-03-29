pipeline{
    agent any

    tools {
         maven 'maven'
//         jdk 'java'
    }

    stages{
        stage('megss-build'){
            steps{
               sh 'mvn package'
            }
        }
    }
}
