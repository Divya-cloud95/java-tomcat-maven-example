pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
				SH '''
                echo  "PATH = ${PATH}"
				echo "M2_HOME = ${M2_HOME}"
				'''
            }
        }

        stage ('Build') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
