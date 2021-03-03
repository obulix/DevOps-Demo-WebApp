pipeline {
  agent any
  stages {
    stage('static-code-validation') {
      steps {
        sh 'mvn sonar:sonar -Dsonar.host.url=http://13.82.221.243:9000 -Dlicense.skip=true'
      }
    }

  }
}