pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
  git 'https://github.com/RamyaShivanna-ux/new.git'
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
