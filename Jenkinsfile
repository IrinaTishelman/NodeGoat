pipeline {
     stages {
        stage('Build') {
            steps {
                echo 'Building..'
                steps {
                      sh 'npm install'
                       }
                    }
         }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
