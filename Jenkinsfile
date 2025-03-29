pipeline{
    agent any

    tools {
         maven 'maven'
//         jdk 'java'
    }

    stages{
        stage('megs-build'){
            steps{
               sh 'mvn package'
            }
        }
    }
}
