pipeline {
  sgent any 
  stages {
    stage {'Build'} {
      steps {
        echo 'Runing Build automation'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainScheduale.zip'
      }
    }
  }
}
