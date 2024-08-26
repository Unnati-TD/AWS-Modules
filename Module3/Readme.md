### Module 3 Readme

This directory contains a script to solve a set of tasks. You can find the problem statements in the file named "Module3 Tasks.md" or you can download the "Module3 Tasks.pdf". To use the script, follow the instructions below:

### Getting Started

**Step 1: Open AWS CloudShell**
- Login to AWS Management Console.
- Search for "CloudShell" in the AWS Management Console search bar.
- Click on CloudShell to open a terminal session within your browser.

**Step 2: Upload the Verification Script to CloudShell**
- Click on the "Actions" button in CloudShell and select "Upload file".
- Select the key pair and upload it.

**Step 3: Run the Verification Script**
- List the files in the CloudShell environment by running the `ls` command.
- Change the permission of `Unnati-key.pem` key pair.

### Downloading the Script
To download the script, run the following command in your terminal:

```bash
sudo wget -P /usr/bin https://raw.githubusercontent.com/Unnati-TD/AWS-Modules/main/Module3/UNNATI-AWS-KUCL-MODULE3
```

### Giving Execute Permission
After downloading the script, you need to give it execute permission. Use the following command:

```bash
sudo chmod +x /usr/bin/UNNATI-AWS-KUCL-MODULE3
```

### Usage
Once the script is downloaded and has the necessary permissions, you can use it to solve the tasks. The script takes input from a file containing the questions and produces the desired output.

To use the script, execute the following command:

```bash
UNNATI-AWS-KUCL-MODULE3 grade task1
```

Replace 'task1' with the task number of your choice.
