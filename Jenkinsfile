pipeline {
	agent any
		stages {
			stage('One') {
				steps {
					env.VARIABLE="value"
				}
			}


			stage('Two') {
				steps {
					echo ${VARIABLE}
				}
			} 

			stage('Three') {
				steps {
					sh 'echo "Step Three"'
				}
			}
		}
}
