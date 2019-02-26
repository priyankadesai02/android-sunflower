pipeline {
         agent none
         stages {
                 stage('build') {
				 agent{label 'gradle'}
                 steps {
					sh "gradle clean build --stacktrace"
                     echo 'Hi, this is Zulaikha from edureka'
					}
								}
                 
                 }
		}
                 