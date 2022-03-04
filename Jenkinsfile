pipeline 
{
        agent any
        stages 
		{
                stage('Build')
				{
						steps 
						{
							'''
							sh sleep 5 ; echo "This is a build stage"
							echo "learning skeleton of pipeline"							
						}
				}
				stage('Test')
				{
						steps 
						{
							sh '''
								sleep 5
								echo "This is a test stage"	
						    '''	
						}
				}
				stage('Deploy')
				{
						steps 
						{
						sh '''
							sleep 5
							echo "This is deploy stage"
							'''
						}
				}
				
				stage('My-stage')
				{
						steps 
						{
						sh '''
							sleep 5
							echo "This is a my-stage stage"
							'''
						
						}
				}
				
		}

}
