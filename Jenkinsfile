pipeline {
    agent any 

    stages {
      stage('Installer') {
          steps {
              sh 'pip install -r requirements.txt'
          }
      }

    stage('Tester') {
            steps {
                sh 'pytest'
            }
        }
  }
}
