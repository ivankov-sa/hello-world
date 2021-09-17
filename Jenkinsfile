pipeline {
  agent any
  stages {
      stage("шаг 1") {
          steps {
              echo "hello 1"
              sh "ls -la"
          }
      }
      stage("шаг 2") {
          steps {
              echo "hello 2"
              sh "mkdir step2"
              sh "pwd"
          }
      }
  }
}