pipeline{
    
      agent any
          
	  	stages{
		        
					stage(build){
					       	   
						     			steps {
									  
									  		      sh 'mvn clean package' 
												          
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
																																																					       
																																																					           
																																																						       

