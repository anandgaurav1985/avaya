pipeline{
    
      agent any
          
	  	stages{
		        
					stage(build){
					       	   
						     			steps {
									  
									  		      sh '/home/ec2-user/apache-maven-3.5.3/bin/mvn clean package' 
												          
													  		        }
																  
																  	        }
																		    

																		    	        stage(test){
																				          
																					    			steps{
																								            
																									    			      sh 'echo "Running test "'
																												         
																													 	                }
																																        
																																	        }
																																		      
																																		        	      
																																				                      stage(Deploy){
																																						                  
																																								              steps{
																																									       
																																									                                     sh 'echo "Running Deploy"'
																																													        
																																														                        }
																																																	  
																																																	                  }
																																																			    


																																																			            }
																																																				           
																																																					   }
																																																					       
																																																					           
																																																						       

