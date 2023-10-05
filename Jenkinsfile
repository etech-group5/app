pipeline{
	agent any 
	stages{
		stage('1-clone'){
			steps{
	checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'git-id', url: 'https://github.com/etech-group5/app.git']])
			}
		}
		stage('2-turn'){
			steps{
				echo "keep walking"
				sh 'lscpu'
			}
		}
		stage('3-rotate'){
			steps{
				echo "keep walking"
				sh 'whoami'
			}
		}
		stage('4-station'){
			steps{
				echo "keep walking"
				echo "final stage"
				sh 'lsblk'
			}
		}
	}
}