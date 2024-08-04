 pipeline {
    agent {
        node {
        
            label 'maven'
        }
    }

 environment {
     PATH = "$PATH:/opt/apache-maven-3.9.8/bin"
 }

    stages {
        stage {
            steps (build) {
                'sh mvn clean deploy'
            }
             
        }
 
        }
    }
}