pipeline {
  agent any
  stages {
      stage ('Test') {
        steps {
          echo "Hallo"
          cfg = readyaml file: './prometheus/srv/config.yml'
          echo cfg
          sh "echo ${cfg}"
        }
      }
  }
}
