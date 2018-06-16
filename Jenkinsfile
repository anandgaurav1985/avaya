pipeline{
    
      agent any
          
  	stages{
		       stage("sonarqube quality check"){
		              steps{
			                sh 'echo "Running localhost sonar server "'

					sh '/home/ec2-user/apache-maven-3.5.3/bin/mvn sonar:sonar'


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
																																																					       
																																																					           
																																																						       

