pipeline { 
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }  
         	    } 

				stage("build") {  
           	    	steps {  
              	    sh "mvn test" 
              	    sh "mvn verify'
					
        }

		}
	
}
	
}
