pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
  sh 'cd /home/'
 }
 }
 stage('testing') {
  steps {
 terraform init
 terraform plan
 }
 }
 }
}
