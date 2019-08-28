pipeliene{
	agent any 
		stages {
			stage('One'){
				steps{
					echo 'My name is Saloni '
				     }
				    }
			stage('Two'){
				steps{
					input ('Do you want to proceed further?')
				     }
				    }
			stage('Three'){
				when { 
					not
					{ branch "master" 
					}
				     }
				steps {
					echo "hello everyone"
				      }
				       }
}
}

