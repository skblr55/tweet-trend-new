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
        stage("build"){
            steps {
                sh 'mvn clean deploy -Dmaven.test.skip=true'
            }
             
         }
 
     }
}
