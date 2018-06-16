pipeline{
    
      agent any
          
  	stages{
		       stage("sonarqube quality check"){
		              steps{
			                sh 'echo "Running sonar web "'

					          sh '/home/ec2-user/apache-maven-3.5.3/bin/mvn sonar:sonar -Dsonar.organization=anandgaurav1985-github -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=a677852396f750379fbff56aa49c77fd27a1030b'


						              }
							                 }

																		    

stage("Quality Gate") {
            steps {
	                    timeout(time: 1, unit: 'HOURS') {
			                        // Parameter indicates whether to set pipeline to UNSTABLE if Quality Gate fails
						                    // true = set pipeline to UNSTABLE, false = don't
								                        // Requires SonarQube Scanner for Jenkins 2.7+
											                    waitForQualityGate abortPipeline: true
													                    }
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
																																																					       
																																																					           
																																																						       

