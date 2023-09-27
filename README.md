# IAM-Cloud-Deployment-to-AWS


In this project we will be migration the entire IT team to AWS via automation
After migrating the users, we will associate permissions to groups and enforcing MFA for added security. 

 

1) Open the AWS Cloud Shell

2) Install dos2unix on AWS Cloud Shell (required by the script)
   

     sudo yum install dos2unix -y


3) Download the aws-iam-create-user.sh script on AWS Cloud Shell
   

     wget https://tcb-bootcamps.s3.amazonaws.com/bootcamp-aws/en/aws-iam-create-user.sh


4) Give the proper permission to aws-iam-create-user.sh script
   

      chmod +x aws-iam-create-user.sh
   

6) Upload the users2.csv file to AWS Cloud Shell
   

8) Run the script aws-iam-create-user.sh to create the IAM users
   

        ./aws-iam-create-user.sh users2.csv

