pipeline {
   agent any

   stages { 
      stage("git checkout")
       {
          steps {
             git branch : 'master', url : 'https://github.com/bmanisha04/mission.git'
 
                 }
 
        }

        stage ("build the code")
		{
		  steps {
		    sh 'mvn clean package -DskipTests'
		  
		  }
		
		}

           }
   }