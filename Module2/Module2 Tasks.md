<a name="br1"></a> 

**Unnati Development and Training Center Pvt Ltd**

**AWS Module 2 Gradable Task**

**Sr.**

**Tasks**

**No.**

1\.

Launch the instance with name "KuCL2.0", use "Amazon Linux

2023 AMI" Image to launch the instance. Use "us-east-1" region

to launch the instance. Use "t2.micro" as a instance type.Use key

pair "Unnati-KuCL2.0". Take a ssh session using Putty/Powershell

create a ﬁle named "myhost" in home directory of ec2-user,

which contains the hostname of the instance.

2\.

Launch the instance with name "Unnati", use "Ubuntu Server

22\.04 LTS (HVM), SSD Volume Type" image to launch the

instance. Use "us-east-1" region to launch the instance. Use

"t2.micro" as a instance type. Use key pair "Unnati-KuCL2.0".

Take a ssh session using Putty/Powershell create a ﬁle named

unnati.txt which contains the text: "Welcome to Unnati

Development and Training Pvt Ltd".

3\.

4\.

Launch the instance with name "MyDesktop", use "Microsoft

Windows Server 2022 Base" image to launch the instance. Use

"us-east-1" region to launch the instance. Use "t2.small" as a

instance type.

Create a normal ubuntu instance named "Ubuntu-Desktop", with

AMI "Ubuntu Server 22.04 LT S (HVM), SSD Volume Type". Use "us-

east-1" region to launch the instance. Use "t2.micro" as a

instance type. Install the required packages to convert it in

graphical desktop.Use key pair "Unnati-KuCL2.0".

Use following documentation for reference

[https://ubuntu.com/tutorials/ubuntu-desktop-aws#5-connecting-](https://ubuntu.com/tutorials/ubuntu-desktop-aws#5-connecting-to-ubuntu-desktop)

[to-ubuntu-desktop](https://ubuntu.com/tutorials/ubuntu-desktop-aws#5-connecting-to-ubuntu-desktop)

5\.

6\.

Launch a spot instances name "Kucl2.0 Spot Instance" with AMI

"Ubuntu Server 22.04 LT S (HVM), SSD Volume Type" in us-east-1

region, with key pair "Unnati-KuCL2.0".Take SSH session of

instances and create a ﬁle hello.txt which contains text "Hello

from unnati!".

Launch two instances name "KuCL2.0" and "Unnati" in us-east-1

region. AMI should be should be "Amazon Linux 2023 AMI" and

"Ubuntu Server 22.04 LT S (HVM), SSD Volume Type", Instance



<a name="br2"></a> 

**Unnati Development and Training Center Pvt Ltd**

type should be t2.micro. Create a ﬁle named mynote.txt which

contains "Hello from KuCL2.0" on "KuCL2.0" instance and copy

that ﬁle on "Unnati" instances through port number 18000. Use

key pair "Unnati-KuCL2.0"

