# biz9-server
BiZ9-Server is an open-source tool to ship, develop, and run various applications inside a Linux container, a lightweight virtual machine. It has many tools and features that provide administrative needs to run your application.


## Links

[Amazon Web Services EC2 Linux Instance Setup](#Amazon-Web-Services-EC2-Linux-Instance-Setup)

[EC2 Linux Instance Setup](#Amazon-Web-Services-EC2-Linux-Instance-Setup)


## Amazon Web Services EC2 Linux Instance Setup

### Amazon Web Services EC2 Setup
#### Go to Amazon Web Services
1. Login into your Amazon Web Services Account
2. Go to https://signin.aws.amazon.com
3. Log in or create an account

![](/other/photo/screenz/1/0.jpg)

#### Go to Product EC2
4. Use the search bar and go to EC2

![](/other/photo/screenz/1/9.jpg)

#### Launch Instance
5. Click the launch instance

#### Name the instance
6. Enter instance title ( default : server-19 )
![](/other/photo/screenz/1/3.jpg)

#### Choose an Amazon Machine Image (AMI)
7. Search and select ‘Debian’ ( default: Debian 12 )
![](/other/photo/screenz/1/4.jpg)

#### Instance type
8. Select instance type ( default: t2.medium )
![](/other/photo/screenz/1/5.jpg)

#### Key pair
9. Create new key pair ( default: 19.pem )
10. Key pair type: RSA ( default: RSA )
![](/other/photo/screenz/1/6.jpg)


#### Save to application folder
11. Save .PEM file to ec2_key folder ( default: project_folder_id/server/other/aws/ec2_key/19.pem )


#### Network Settings
12. Allow SSH traffic from anywhere
13. Allow HTTPS traffic from internet
14. Allow HTTP traffic from the internet

![](/other/photo/screenz/1/10.jpg)

#### Configure storage
15. Enter storage size ( default: 20 GIB )

#### Summary
16. Enter number of instances ( default: 20 GIB )
17. Click Launch Instance

![](/other/photo/screenz/1/7.jpg)

#### Instance is running
18. Your instance will be in a pending and then running state.
19. Confirm your instance is running.

![](/other/photo/screenz/1/8.jpg)









