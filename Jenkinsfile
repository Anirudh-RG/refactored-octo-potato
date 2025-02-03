pipeline {
	agent any

	environment{
		BASH = '"C:\\Users\\Anirudh\\AppData\\Local\\Programs\\Git\\bin\\bash.exe"'
	}
	stages{
		stage('Stage 1'){
			steps{
				bat '${env.BASH} scripts/stage1.sh'
			}
		}
	}
}