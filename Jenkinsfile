pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifaces artifacts: 'dist/trainSchesule.zip'
      }
    }
  }
}
