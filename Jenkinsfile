pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
   sh ' sudo /home/ec2-user/test1'
 sh 'sudo git clone https://github.com/RamyaShivanna-ux/new.git'
 }
 }
 stage('testing') {
  steps {
   sh 'sudo /home/ec2-user/test1'
 terraform init
 terraform plan
 }
 }
 }
}
