pipeline {
    agent any
    tools {
    maven 'mvncfg'
    }

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn compile'
                
            }
        }

        stage ('Package Stage') {

            steps {
                
                    sh 'mvn package'
                
            }
        }


        
    }
}
