pipeline{

  agent any

  stages {
    stage ('build'){
      steps {
        echo 'Runnin build automation'
        sh './gradleq build --no-daemon'
        arciveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
    }
}
