# Project Setup Guide

## 1. Clone the Repository

First, create a folder on your local machine where you want to store your project files. After that, clone the repository from which you want to take the application or website. Run the following command in your terminal:


git clone https://github.com/shreyashpatil4266/ci-cd-static-web-docker



git add .
git commit -m "Initial commit with files from the old repository"
git push origin master


docker_username: your_dockerhub_username
change it into docker.yml file with your own username only dont give pass there 


make cahnges in the github go--settings----secrets and variable -----actions ----new repository secret ----create give name as DOCKER_USERNAME -----value your username of docker hub------then same create new -----DOCKER_PASSWORD ----- value your passowrd ...






open docker desktop if no installed installed it https://www.docker.com/products/docker-desktop/

it will help creating the docker container 
now the files are created as you cloned it the ngnix server will run the insex.htnnl on local host after run 



but for autoamtion you have to use minikube in that start it creted two file one deploymeny.yml and one service.yml
then kubectl apply -f deployment.yml              kubectl apply -f service.yml


then run build and run docker in minikube and see the hit the ip you will see the index.html page 



and now do the git push to everything-up-to-date..

i have three change to be sure my project is working first run the local host and see the website 
![Screenshot 2025-04-22 134335](https://github.com/user-attachments/assets/a8a8c84e-4e00-4fc8-89b8-92649dd838f3)

then cahnge the code in index.html like remove all the detail and again run and build then see the changes 
![Screenshot 2025-04-22 135421](https://github.com/user-attachments/assets/36cc3488-ff9a-4e0c-8d4f-1f4e2bb27da5)


then revert the changes from git logs and then run again 
![Screenshot 2025-04-22 140240](https://github.com/user-attachments/assets/b5b2efd6-9551-401e-8a4d-8ed99032277e)


