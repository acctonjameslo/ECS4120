// Declarative //
ppipeline {
    agent any
    
    stages {
        stage ('One) {
            steps {
               echo 'Hi, this is AS3000 sanity test for branch - master'
            }
        }
        stage ('Build') {
            steps {
                echo 'Build'
                sh 'make test'        
            }
        }
        stage ('Test') {
            steps {
                echo 'Test'
            }
        }
    }
}
