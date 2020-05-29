# docker-node
#Dockerizing a Node.js web app

#Building your image
!!! docker build -t web-app .

#Run your image
!!! docker run -p 8085:8080 -d web-app

