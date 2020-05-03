# DockerWebApp

How to run this in your system?   
Step 1 - Clone this repository   
Step 2 - Open the terminal and change the directory  
Step 3 - Run following commands   

 ### sudo docker build -t <your_docker_user_name>/DockerWebApp .    
 or    
 ### sudo docker build .    
 (If you are using this second command then copy the container id and use it in next command after port numbers)    
 
 ### sudo docker run -p 8080:8080 <your_docker_user_name>/DockerWebApp  
