pipeline {
    agent	any					
    stages	{														
	stage("Compile") 	{															
            steps	{
                echo 'hello'

                dir ('demo') {
                    sh 'pwd'
                    sh "ls -l"
                    sh "./gradlew compileJava"	
                }
													
            }									
        }	
        
    } 
}
