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
The first step in creating your container is creating a file using your vi editor. The file name will be Dockerfile. This step is critical because it allows you to create your docker image. 
</p>
<br />

<p align="center">
<img src="https://imgur.com/SrDFtQa.png"  alt="Docker image file"/>
</p>
<p>
From Ubuntu is the base operating system(OS) that we will be using for our image. Then we will update the ubuntu to the latest version with the apt-get update command. Then we will install the nginx on that operating system. CMD command acts as userdata meaning that it will run after the nginx is installed. This command will start the nginx after it is installed onto the operating system.
</p>
<br />

<p align="center">
<img src="https://imgur.com/lrpehuw.png"  alt="Docker build"/>
</p>
<p>
This command will build out the Dockerimage by using the Dockerfile we have created. It will run the commands one by one.
</p>
<br />

<p align="center">
<img src="https://imgur.com/EdAvsDI.png"  alt="Successfully built"/>
</p>
<p>
After the Docker build . command is run you should see a successfully built with your image Id.
</p>
<br />

<p align="center">
<img src="https://imgur.com/dEOXjN3.png"  alt="image has been created"/>
</p>
<p>
You should see two Images when you type docker images. I have three showing because in my vi editor I had the an error I put a colon instead of a semicolon and when I went to use docker run to create my container it would kill my container instantly.
</p>
<br />

<p align="center">
<img src="https://imgur.com/8ExVDAS.png"  alt="image has been created"/>
</p>
<p>
This command runs docker in detached mode with port mapping with our server side and nginx server side nginx default port is port 80. When we run this command the nginx container will be launched on our public ip address through port 80.
</p>
<br />

<p align="center">
<img src="https://imgur.com/jGYWCUj.png"  alt="image has been created"/>
</p>
<p align="center">
Congratulations you have launched your NGINX web server.
</p>
<br />

