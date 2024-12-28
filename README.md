# SimpliLearn MEAN Stack Developer - Dockerizing Angular Application

**Project: Dockerizing Angular Application**

**Objective:**
The objective of this Project to deploy an Angular application on Docker container on an EC2 instance so that other developers can access and modify it if required.

**Following has been used:**

1. AWS EC2 instance
2. Docker
3. Node JS
4. Angular CLI
5. GitHub

**Step-by-Step Process:**
1.Installed Node.js and npm, Visual Studio Code, Angular Docker.
2.Created git repository, initialized git in project directory.
3.Writing the program to fulfil the requirements of the project.
4.Launched an EC2 Instance.
5.Installed Docker and created docker container.
6.Set Up Angular Application.
7.Run the docker container.
8.Added the project to git repository, commmited and then pushed to remote repo.

## Steps to run App

**Type it on terminal!**

1. Pull the App from docker
   \*\* `   docker pull kastackered/dockerizing-angular-ec2:latest`
2. Run the docker image
   \*\* `   docker run –d –p 80:80 kastackered/dockerizing-angular-ec2:latest`
3. Paste this link on your browser the app will run
   http://localhost

4. Amazon EC2 Instance running on
   http://100.27.2.203/
