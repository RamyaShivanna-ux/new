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
 sh ‘/home/ec2-user/test/terraform init’
 sh '/home/ec2-user/test/terraform plan'
 }
 }
 }
}
