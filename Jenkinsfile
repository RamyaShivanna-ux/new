pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
   sh ' sudo /home/ec2-user/test'
 sh 'sudo git clone https://github.com/RamyaShivanna-ux/new.git'
 }
 }
 stage(‘Set Terraform path’) {
 steps {
  sh 'sudo /home/ec2-user/'
 }
 }
 stage(‘Provision infrastructure’) {
  steps {
 sh ‘terraform init’
 sh 'terraform plan'
 }
 }
 }
}
