# Deploying an Wordpress website on AWS



## Step 1:  Launch an Amazon EC2 Instance
   
* Initiate the process by launching an Amazon Elastic Compute Cloud (EC2) instance, which will serve as the virtual server hosting your WordPress application.

![Screenshot (252)](https://github.com/sunilkurthakoti/Deploying_Wordpress_website/assets/131526336/409d4550-c0cf-4f6c-8274-71c64d983fcc)


## Step 2:  Set Up an Amazon RDS for MySQL Database
   
* Establish a managed Amazon Relational Database Service (RDS) to store the MySQL database for your WordPress site. This ensures a scalable and reliable database solution.

![Screenshot (253)](https://github.com/sunilkurthakoti/Deploying_Wordpress_website/assets/131526336/672ce554-c5ca-4b46-9137-b5a7fdcdb995)


## Step 3:  Create an IAM Role for EC2 with RDS Full Access
   
* Configure an Identity and Access Management (IAM) role for your EC2 instance, providing it with the necessary permissions to interact seamlessly with the RDS database.

## Step 4:  Connect EC2 to RDS Using MySQL Client
   
* Facilitate communication between your EC2 instance and the RDS database by configuring the required connection details and credentials. This step is pivotal for data flow and management.

![Screenshot (249)](https://github.com/sunilkurthakoti/Deploying_Wordpress_website/assets/131526336/4fe392da-946a-47df-a80f-b4a2c8596834)


## Step 5:  WordPress DB Creation and Apache Server Installation
   
* Install and configure the WordPress application on your EC2 instance. Simultaneously, create the essential database tables and set up the Apache web server to ensure optimal performance.

![Screenshot (250)](https://github.com/sunilkurthakoti/Deploying_Wordpress_website/assets/131526336/9b531d83-19af-4a48-be7b-4772d1239e31)


## Step 6:  Set up the server and post your new WordPress app and Explore the Newly Set Website
   
* Complete the WordPress setup process, including the provision of site information, creation of an administrative account, and customization of settings. This step ensures your WordPress site is fully operational.

![Screenshot (251)](https://github.com/sunilkurthakoti/Deploying_Wordpress_website/assets/131526336/4597308e-5b80-4a04-b7b6-54f1572bcf9c)


* By following these steps, you'll successfully deploy a WordPress site on Amazon Web Services (AWS), incorporating key infrastructure components like EC2 instances and RDS databases. The emphasis on establishing a seamless connection between the EC2 instance and RDS database ensures the proper functioning of your WordPress website. After completing these steps, you can confidently explore and enjoy your newly set-up WordPress site on AWS infrastructure.
