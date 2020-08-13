pipeline {
    agent any
    environment {
        PATH = "/opt/maven/apache-maven-3.6.3/bin:$PATH"
    }
    stages {
        stage("git checkout") {
            steps {
               //git credentialsId: 'b8cc2c58-54db-4317-bd77-04a488385e52', url: 'https://github.com/HARISHDARA/test-maven.git'
               git clone 'https://github.com/HARISHDARA/test-maven.git'
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
