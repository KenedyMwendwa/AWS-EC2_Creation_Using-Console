# AWS-EC2_Creation_Using-Console

Is it your first time to create EC2 instance in AWS? Don't worry I'm here to help you....

Follow these steps to create your first EC2 instance in AWS:

## Step 1: Sign in to AWS Console

Go to the [AWS Management Console](https://aws.amazon.com/console/) and sign in to your AWS account.

If you don't have an account, first proceed and create an account. [Sign Up](https://aws.amazon.com/)

## Step 2: Navigate to EC2 Dashboard

Navigate to the EC2 Dashboard by clicking on the "Services" dropdown menu and selecting "EC2" under the "Compute" section.

Can't find the services Dropdown? Type EC2 in the search bar at the top of the page and click Enter...

## Step 3: Launch Instance

Click on instances.

Click on the "Launch Instance" button to begin the process of launching a new EC2 instance.

## Step 4: Choose an Amazon Machine Image (AMI)

Select an Amazon Machine Image (AMI) from the available options. This is the operating system and software configuration for your instance.

Here choose your preffered OS Image:
- Amazon Linux
- Red Hat Linux
- SUSE Linux
- Ubuntu
- Windows 

## Step 5: Choose Instance Type

Choose an instance type based on your requirements. This determines the computing resources (CPU, memory, etc.) for your instance.

If you're using a free tier account, stick to the free tier instance types otherwise you'll incurr some costs.

## Step 6: Configure Instance Details

Configure instance details such as network settings, IAM role, monitoring, etc. You can leave most settings as default if you're unsure.

If you're beginner leave most of the settings as default.

## Step 7: Add Storage

Add storage to your instance. You can specify the size and type of storage (e.g., SSD, magnetic) based on your needs.

For a free tier account AWS provides a maximum of 30 GiB, avoid exceeding this limit otherwise you will incurr some costs.

Some Operating systems require larger storage compared to others, therefore opt for OS images taking lesser storage.



## Step 8: Add Tags (Optional)

Add tags to your instance for better organization and management. Tags are key-value pairs that help identify your resources.

## Step 9: Configure Security Group

Configure the security group for your instance. This controls inbound and outbound traffic to your instance. Make sure to allow SSH (port 22) if you need remote access.

In this case if your local computer uses a static IP, you can restrict the source of access to your IP address.

## Step 10: Review Instance Launch

Review all the configurations you've made for your instance. Once you're satisfied, click on the "Launch" button.

## Step 11: Create Key Pair

Choose an existing key pair or create a new one. This key pair is used to securely connect to your instance via SSH.

Choose the .pem or .pmk option to save your key in your local computer.

## Step 12: Access Your Instance

Once your instance is launched, you can access it using SSH. Use the following command:
Congratulations!!!!
Enjoy working on your new virtual computer.

```bash
ssh -i your-key.pem ec2-user@your-instance-public-ip
````

### ⚙️ Connect with Me

<p align="center">
<a href="mailto:mulilamwendwa@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/kenedy-mulila-29319215a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> 
