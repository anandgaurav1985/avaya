pipeline{
    
      agent any
          
  	stages{
		        
																		    

    	        stage( code sonarqube analysis){
																				          
																					    			steps{
																								            
																									    			      sh 'echo "Running sonar web test "'
																												      sh '/home/ec2-user/apache-maven-3.5.3/bin/mvn sonar:sonar -Dsonar.organization=anandgaurav1985-github -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=a677852396f750379fbff56aa49c77fd27a1030b'
																												         
																													 	                }
																																        
																																        }
																						stage(build){

															                                                                        steps {

																																							                                                                                              sh '/home/ec2-user/apache-maven-3.5.3/bin/mvn clean package'

																																																				                                                                                                                                      }

																																																		                                                                                                                                                      }

																																		      
																																		        	      
																					                      stage(Deploy){
																																						                  
																						              steps{
																																							       
																								                                     sh 'echo "Running Deploy"'
																																													        
																					                        }
																																																	  
																							                  }
																																																			    


																							            }
																																																			           
																							   }
																																																					       
																																																					           
																																																						       

