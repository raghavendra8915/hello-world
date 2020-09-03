pipeline{
    agent any
    stages{
        stage("git checkout"){
            steps{
                 git credentialsId: '48b9912e-7d71-44bb-9007-916c7f56fa16', url: 'https://github.com/raghavendra8915/hello-world.git'               
            }
        }
    }
}
