  
**AWS Module 5 Task**

| Sr. No. | Tasks |
| :---: | ----- |
| 1\. | Deploy a Docker container on Amazon ECS using Fargate. Create an ECS cluster named "unnati-cluster" in the "us-east-1" region. Define a task definition named "unnati-task" with a container named "unnati-container" that uses the "nginx" image. Set up the task to use 0.5 vCPU and 1GB of memory. Create a service named "unnati-service" to run the task definition with desired count set to 2\. Verify that the containers are running by accessing the NGINX welcome page.  |
| 2\. | Create an ECS cluster named "alpha-cluster" in the "us-east-1" region, define a task named "alpha-task" with a container named "alpha-container" using the "httpd" image, allocate 1 vCPU and 2GB memory, set up a service named "alpha-service" to run the task definition with desired count set to 3, and verify that the containers are running by accessing the Apache HTTP Server default page.  |
| 3\. | Create an ECS cluster named "wordpress-cluster" in the "us-east-1" region. Define a task named "wordpress-task" with two containers: "wordpress-container" using the "wordpress" image for the frontend, and "mysql-container" using the "mysql" image for the backend. Allocate 1 vCPU and 2GB of memory to the "wordpress-container" and 0.5 vCPU and 1GB of memory to the "mysql-container." Create a service named "wordpress-service" to run the task with a desired count of 1\. Finally, verify that the WordPress site is accessible by visiting the public IP of the "wordpress-container."  |

