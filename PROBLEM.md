## Exercise: Explore and launch EC2 Instance on AWS 


The primary idea behind this exercise is to make you familer with AWS EC2 instance  and explore different instance type , start and stop instance. 

we will complete this exercise in series of steps:

# Step 1: Login to you VLAB and start aws lab which has been assigned to you .

# Step 2: Open aws console in your browser  and select EC2. 

# Step 3: Explore different AMI available in your region. 

# Step 4: Select Instance and then Launch Instance from menu.  

# Step 5: Select Amazon Linux AMI which has free tier eligiblity. 

# Step 6 : Select t2.micro as instance type then  Review and Launch . 

# Step 7: create key pair for ec2, download it on your local system as we need this .pem          file. 

## Step 8: On Launch status window select how to connect with your Instance . 

## Step 9:  Select SSH client and follow the instrction given . 
    command for your reference :
     ssh -i /path/my-key-pair.pem my-instance-user-name@my-instance-public-dns-name

## Step 10: Create one text file named stackroute.txt on ec2 instance and write few lines. 

## Step 11: Use SCP client to download this file from EC2 instance to your local system . 
    command for your reference:
      scp -i /path/my-key-pair.pem ec2-user@my-instance-public-dns-name:path/            my-file.txt path/my-file2.txt

## Step 12 : copy one file from your local system to EC2 instance . 
    command for your reference :
    scp -i /path/my-key-pair.pem /path/my-file.txt ec2-user@my-instance-public-dns-name:path/

## Step 13: Stop the instance and terminate running instance. 

## Step 14 : Congratulations , you are done  , Logout from console and close your lab. 

