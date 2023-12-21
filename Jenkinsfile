pipeline{
	agent any 
	stages{
		stage('1-action1'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'ArmandCantiller87', url: 'https://github.com/ArmandTeam8/jenkins1.git']])
			}
		}
		stage('2-action2'){
			steps{
				sh 'df -h'
			}
		}
		stage('3-action3'){
			steps{
				sh 'lsblk'
			}
		}
		stage('4-action4'){
			steps{
				sh 'lscpu'
			}
		}
		stage('5-welcome message'){
            steps{
                echo 'welcome to Etech team8 jenkins'
            }
        }
	}
}	


	