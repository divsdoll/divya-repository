#!groovy

node {
   stage ('Git checkout'){
   git credentialsId: 'Git_Credentials', url: 'https://github.com/shrinathmangalore/hackathon.git'
   }
 stage('mavenExecutions'){
        sh 'mvn clean package'
    }
}
