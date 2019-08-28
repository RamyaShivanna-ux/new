pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
   sh ' sudo /home/ec2-user/test'
 sh 'sudo git clone https://github.com/RamyaShivanna-ux/new.git'
 }
 }
 stage('testing') {
  steps {
   sh 'sudo /home/ec2-user/test'
 sh ‘terraform init’
 sh 'terraform plan'
 }
 }
 }
}
