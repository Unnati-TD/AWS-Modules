  
**AWS Module 2 Task**

| Sr. No. | Tasks |
| :---: | ----- |
| 1\. | Launch EC2 instance with name “unnati-instance” use “Ubuntu Server 24.04 LTS (HVM)” Image to launch the instance. Use “us-east-1” az to launch the instance use “t2.micro” as a instance type the key pair name should  “unnati-key” and add  10GB disk while creating instance take ssh session using powershell and create partition of 2GB in the “unnati-instance”  |
| 2\. | Create an instance named snap-instance using the "Amazon Linux 2023 AMI" and snap-key as the key pair. Create a 5GB gp2 EBS volume, attach it to snap-instance, access it via Windows PowerShell, and create a 2GB partition with an ext3 file system. Mount it on the /test directory, create files named day1 to day10.  |
| 3\. | Launch the instance with name "MyDesktop", use "Microsoft Windows Server 2022 Base" image to launch the instance. Use "us-east-1" region to launch the instance. Use "t2.small" as a instance type.  |
| 4\. | Launch an EC2 instance named web-instance in the us-east-1 availability zone using an Amazon Linux 2023 AMI. Assign the key pair web-key to this instance. Attach a 3GB GP2 volume to web-instance. Access the instance using PowerShell, install the HTTPD package, and Create 3GB partion & mount the 3GB(ext4) partition to /var/www/html.  |
| 5\. | Launch an EC2 instance with the name "simple-instance" using an "Amazon Linux 2 AMI (HVM) \- Kernel 5.10" AMI in the "us-east-1" region. Use the "t2.micro" instance type and create a key pair named "simple-key". Once the instance is running, connect to it using SSH. create a file named unnati.txt which contains the text: "Welcome to Unnati Development and Training Pvt Ltd". |
| 6\. | Launch the instance with name "KuCL2.0", use "Amazon Linux 2023 AMI" Image to launch the instance. Use "us-east-1" region to launch the instance. Use "t2.micro" as a instance type.Use key pair"Unnati-KuCL2.0". Take a ssh session using Putty/Powershell create a file named "myhost" in home directory of ec2-user, which contains the hostname of the instance.  |
| 7\. | Create a normal ubuntu instance named "Ubuntu-Desktop", with AMI "Ubuntu Server 22.04 LTS (HVM), SSD Volume Type". Use "us-east-1" region to launch the instance. Use "t2.micro" as a instance type. Install the required packages to convert it in graphical desktop.Use key pair "Unnati-KuCL2.0". Use following documentation for reference https://ubuntu.com/tutorials/ubuntu-desktop-aws\#5-connecting-to-ubuntu-desktop  |
| 8\. | Launch the instance with name "Unnati", use "Ubuntu Server 22.04 LTS (HVM), SSD Volume Type" image to launch the instance. Use "us-east-1" region to launch the instance. Use "t2.micro" as a instance type. Use key pair "Unnati-KuCL2.0". Take a ssh session using Putty/Powershell create a file named unnati.txt which contains the text: "Welcome to Unnati Development and Training Pvt Ltd".  |
| 9\. | Launch a spot instances name "Kucl2.0 Spot Instance" with AMI "Ubuntu Server 22.04 LTS (HVM)(architecture x86\_64), SSD Volume Type" in us-east-1 region , with key pair "Unnati-KuCL2.0".Take SSH session of instances and create a file hello.txt which contains text "Hello from unnati\!"."t2-micro  |
| 10 | Launch two instances name "KuCL2.0" and "Unnati" in us-east-1 region. AMI should be should be "Amazon Linux 2023 AMI" and "Ubuntu Server 22.04 LTS (HVM), SSD Volume Type", Instance type should be t2.micro. Create a file named mynote.txt which contains "Hello from KuCL2.0" on "KuCL2.0" instance and copy that file on "Unnati" instances through port number 18000\. Use key pair "Unnati-KuCL2.0" |
