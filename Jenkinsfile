pipeline {
    agent any
    environment {
        PATH = "/opt/maven/apache-maven-3.6.3/bin:$PATH"
    }
    stages {
        stage("git checkout") {
            steps {
               git credentialsId: '6286d3b8-3a8b-4d84-a2f0-a19abd23e3b9', url: 'https://github.com/HARISHDARA/hello-world.git'
               echo "lhjdjdslo harish"   
            }    
        } 
        stage("maven compilation") {
            steps {
                sh "mvn compile install"
            }
        }
     }
}
