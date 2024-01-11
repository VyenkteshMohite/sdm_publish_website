# sittflstore



# Docker

## GIT Proxy Settings
### git config --global --unset http.proxy
### git config --global --unset https.proxy
### git config --global --unset core.proxy
### git config --global http.proxy http://exam@192.168.10.4:808
### git config --global credential.helper wincred
### git config --global user.name "Omkar Ware"
### git config --global user.email "omkarware003@gmail.com"
### git config --global user.password " "

## AWS Docker
### sudo apt update
### git clone <link>
### (cd into docker file folder)
### sudo apt install npm
### npm install nodejs
### npm install express
### sudo apt install docker.io
### sudo docker built -t <imgname> .
### sudo docker run -it -p 9000:8000 <imgname>


==========================================================================

1.Create public or private repo on github for node app.
2.Clone public repo to local machine.
2.Add server.js file , public folder ,package.json, Dockerfile to node js application folder locally copied.
4.Add .gitigore file to block bin, node_modules folder.
5.Push code repository to git hub account.
6.Create aws virtual server with Ubutnu OS, keypair file using  aws console.
7.set fire wall using  security manager of virtual Server with inbound rule alltraffic , request to be
8.Update Linux server using 
  sudo apt update 
9.Clone public repository consisting nodejs app to linux virtual server.
10.Install docker using command.
    sudo apt install docker.io
11.Ensure Docker demon process is running in background
   sudo systemctl status docker
12.Check number of docker images installed in virtual server 
   sudo docker images
13.Check number of docker instances running with the help docker service.
    sudo docker pass
14.Change directory to clonned repo
    cd localrepfolder
15.Use Docker build command to create docker container image for node js application.
   sudo docker build -t knowitnodeapp  .
16.Run Docker container instance using following command.
   sudo docker run -d -p 8081:8081 knowitnodeapp
17.Check number of docker container instances running in virtual server.
   sudo docker pas
18.Access website hosted by node js application running inside container with the help
   docker engine to remote server managed  AWS
19.Terminate container instance running with the help of following command
    sudo docker kill -f  containerid


