# Week 1 — App Containerization

## Week 1 -Homework / Tasks - Required

## Dockers
Managed to learn  in short time how to install and run dockers locally .

## Installing dockers on windows 10.

followed the docker documention to install docker Desktop on windows10.
[Docker doc link for windows10](https://docs.docker.com/desktop/install/windows-install/)

![IMAGE OF Docker INSTALL -Terminal](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/docker%20in%20windows%20-week1.JPG)

we can verify using following commands docker -v ,docker to confirm it is installed .

Docker Desktop for Windows provides a development environment for building, shipping, and running dockerized apps. By enabling the WSL 2 based engine, we can run both Linux and Windows containers in Docker Desktop on the same machine.

When we use Docker desktop, we have access to docker in powershell/cmd, have access to your file on windows, the possibility to switch to Windows container and to use it with your IDE.

In order to docker work in widows wsl2 -ex ubuntu ,centos8 we have to enable wsl integration under settings Resources.

![IMAGE OF Docker Desktop INSTALL](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/Doker%20Desktop%20-WIDOWS-WEEK1.JPG)

so know we can run docker in wsl2 - ubuntu

![IMAGE OF Docker Desktop INSTALL](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/installed%20docker%20on%20wsl2%20-ubuntu-week1.JPG)

## Running the Cruddur Application Local

I have installed Github Desktop on windows using the following link.
[Github Desktop link for windows10](https://docs.docker.com/desktop/install/windows-install/)

![Image of Github Desktop](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/GitHub%20Desktop-windows-week1.JPG)

You can use GitHub Desktop to complete most Git commands from your desktop with visual confirmation of changes. You can push to, pull from, and clone remote repositories with GitHub Desktop, and use collaborative tools such as attributing commits and creating pull requests.

once we clone the repo on the desktop we will be able to run it locally.

Docker ps on local drive
![Iamge of docker-containers-locally](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20on%20windows10-week1.JPG)

Frontend-react-js running-locally
![Image of frontend-react-js-locally](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20in%20windows-10-port-3000%20-week1.JPG)

Backend-flask running locally
![Image of backend-flask locally](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20in%20windows-10-port-4567-week1.JPG)

Able to perform the same task on Ubuntu wsl2 on windows

Docker ps on local drive
![Iamge of docker-containers-locally-ubuntu-wsl2](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20on%20ubuntu-week1.JPG)

Frontend-react-js running-locally-wsl2-ubuntu
![Image of frontend-react-js-locally-wsl2-ubuntu](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20on%20ubuntu-frontend-week1-port3000.JPG)

Backend-flask running locally-wsl2-ubuntu
![Image of backend-flask locally-wsl2-ubuntu](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/locally%20on%20ubuntu-backend-week1-port4567.JPG)

## Docker hub 

Able to create Docker hub Repository-public ,pushed the image to repo.
using the following commands

```
docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]
docker push [OPTIONS] NAME[:TAG]

```
Docker image push to Registery
 ![Image of Docker Push from Terminal](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/docker%20image%20pushed%20to%20registry-week1.JPG)

Dockerhub Registery
![Image of Dockerhub Registry](https://github.com/bobby9002/aws-bootcamp-cruddur-2023/blob/main/journal/assets/docker%20registry%20-week1.JPG)

### Challenges faced during week -1

- 1. Couldn't manage to include Healthchecks in Docker-Compose.yml ,tried it but still showing errors.
- 2.still not tried to run the APP in Ec2 




