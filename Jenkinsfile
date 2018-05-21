pipeline {
  agent any
  stages {
     stage('Deploy ARM') {
      environment {
        ANYPOINT_CREDENTIALS = credentials('anypoint.credentials')
      }
      steps {
        bat 'mvn deploy -P arm -Danypoint.target.type=server -Darm.target.name=apprhel74mupoc08-mule4 -Danypoint.environment=Sandbox -Danypoint.username=bimehta -Danypoint.password=Mel2018a'
      }
    }
    }
  }
}