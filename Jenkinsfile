pipeline{
    agent any

    tools {
         maven 'maven'
//         jdk 'java'
    }

    stages{
        stage('checkout'){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: 'megs']],  url: 'https://github.com/sreenivas449/java-hello-world-with-maven.git'])
            }
        }
        stage('build'){
            steps{
               bat 'mvn package'
            }
        }
    }
}
