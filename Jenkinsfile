pipeline {
    agent	any					
    stages	{										
//        stage("Checkout")	{															
//            steps	{																
//                git	url:	
'https://github.com/ulstermg/sturdy-tribble.git'															
//                
  //          }									
   //     }
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
