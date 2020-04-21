# Docker-Applications

To containerize your app, follow these steps
Make sure you are in html-js-app folder on your system


docker build -t my-first-app .
docker container run --name=first-docker-cont -d -p 8500:80 my-first-app

