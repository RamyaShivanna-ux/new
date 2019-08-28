pipeline {
 agent any
  stages {
 stage(‘checkout’) {
  steps {
   cd /home/ec2-user/test1
 sh 'sudo git clone https://github.com/RamyaShivanna-ux/new.git'
 }
 }
 stage('testing') {
  steps {
   cd  /home/ec2-user/test1
 terraform init
 terraform plan
 }
 }
 }
}
