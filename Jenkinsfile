pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
 sh 'sudo git clone https://github.com/RamyaShivanna-ux/new.git'
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
