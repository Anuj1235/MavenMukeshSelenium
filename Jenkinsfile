pipeline 
{
    agent any
    
	stages
	{
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
		
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy App'
            }
        }
    }
	
	post
	{
	
	always
	{
	emailext body: '', subject: 'Pipeline Status', to: 'anuj.deo91@gmail.com'
	}
	
	}
}
