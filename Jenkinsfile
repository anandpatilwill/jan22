pipeline 
{
        agent none
        stages 
		{
                stage('Build')
			agent ( label 'cnode0203' )
				{
						steps 
						{
							sh 'sleep 5 ; echo "This is a build stage"'
						}
				}
				stage('Test')
					agent ( label 'cnode0203' )
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
					agent ( label 'cnode0203' )
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
					agent ( label 'cnode0203' )
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
