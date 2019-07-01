pipeline{
agent {
  docker {
    image 'ubuntu'
    label 'latest'
  }
}

  stages{
	stage('Stage 1') {
           steps {
              echo 'dasdasda'
	      sh 'apt-get update'
              }
	}
	stage('Stage 2') {
           steps {
              echo 'dasdasda'
	      sh 'echo "hui2"'
              }
	}
	stage('Stage 3') {
           steps {
              echo 'dasdasda'
	      sh 'echo "hui3"'
              }
	
	}
	}
}
