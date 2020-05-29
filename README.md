# docker-node
#Dockerizing a Node.js web app

#Building your image
docker build -t web-app .

#Run your image
docker run -p 49160:8080 -d web-app

