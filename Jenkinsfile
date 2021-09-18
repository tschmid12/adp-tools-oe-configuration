pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          readyaml file: './prometheus/srv/config.yml'
        }
      }
  }
}
