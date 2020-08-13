pipeline {
    agent any
    environment {
        PATH = "/opt/maven/apache-maven-3.6.3/bin:$PATH"
    }
    stages {
        stage("git checkout") {
            steps {
               sh 'git clone https://github.com/HARISHDARA/test-maven.git'
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
