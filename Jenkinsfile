pipeline {
 agent any
 
 stages {
 stage(‘checkout’) {
  steps {
   cd /home/ec2-user/test
 git  ‘https://github.com/RamyaShivanna-ux/new.git’
 
 }
 }
 stage(‘Set Terraform path’) {
 steps {
  cd /home/ec2-user/
 }
 }
 
 
 stage(‘Provision infrastructure’) {
 
 steps {
 
 sh ‘terraform init’
 sh ‘terraform plan -out=plan’
 // sh ‘terraform destroy -auto-approve’
 sh ‘terraform apply plan’
 }
 }
 }
}
