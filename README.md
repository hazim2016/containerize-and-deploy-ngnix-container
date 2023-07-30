<p align="center">
<img src="https://imgur.com/55SACnN.png" alt="Docker"/>
</p>


<p align="center">
<h1>Mission Objective and Overview</h1>
<b> The mission objective is to containerize and deploy an ngnix web server using docker. </b>

<h2>Environments and Technologies Used</h2>

- AWS Free tier account
- Dockerhub
- CLI

<h2>Prerequisite </h2>

- EC2 Instance
- Docker Installed

<h2>Installation Steps</h2>

- Build Dockerfile
- Create Dockerimage
- Deploy Container

<p align="center">
<img src="https://imgur.com/DM3zv11.png"  alt="vi editor"/>
</p>
<p>
The first step in creating your container is creating file using your vi editor. The file name will be Dockerfile. This step is critical because it allows you to create your docker image. 
</p>
<br />

<p align="center">
<img src="https://imgur.com/SrDFtQa.png"  alt="Docker image file"/>
</p>
<p>
From Ubunto is the base operating system(OS) that we will be using for our image. Then we will update the ubunto to the latest version with the apt-get update command. then we will install the nginx on that operating system. CMD command acts as userdata meaning that it will run after the nginx is installed. This commanf will start the inginx after it is installed onto the operating system.
</p>
<br />

<p align="center">
<img src="https://imgur.com/lrpehuw.png"  alt="Docker build"/>
</p>
<p>
This command will build out the Dockerimage by using the Dockerfile we have created.
</p>
<br />

<p align="center">
<img src="https://imgur.com/EdAvsDI.png"  alt="vi editor"/>
</p>
<p>
Web Platform Installer. Open the installation Add MySQL 5.5. Then add all PHP version x86 up untill 7.3.
</p>
<br />

<p align="center">
<img src="https://imgur.com/dEOXjN3.png"  alt="image has been created"/>
</p>
<p>
Web Platform Installer. Open the installation Add MySQL 5.5. Then add all PHP version x86 up untill 7.3.
</p>
<br />

<p align="center">
<img src="https://imgur.com/8ExVDAS.png"  alt="image has been created"/>
</p>
<p>
Web Platform Installer. Open the installation Add MySQL 5.5. Then add all PHP version x86 up untill 7.3.
</p>
<br />

<p align="center">
<img src="https://imgur.com/jGYWCUj.png"  alt="image has been created"/>
</p>
<p align="center">
Congratulations you have launched your NGINX web server.
</p>
<br />

