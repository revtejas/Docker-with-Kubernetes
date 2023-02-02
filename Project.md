## Create GKE cluster and Deploy a website
- Open cloud shell
- Run 'docker run -p 8080:80 nginx:latest' to start the docker image
- Run 'docker run -d -p 8080:80 nginx:latest' to start the docker image in the background
- Check preview in new tab to visit the website
- Run 'docker ps' to see all the running docker images
- Run 'docker ps -a' to see all the docker images
- Copy container ID
- Run 'docker cp .html containerID:htmlpath
  - For example: Run 'docker cp index.html e9e6637ba7b8:/usr/share/nginx/html/'
- check preview in new tab
- DONE!

## Dockerizing Springboot application
- Build jar fil using maven
- Create Dockerfile inside target folder
- Open cmd and change directory to project folder where dockerfile is present
- Open cmd and build docker image using jar file
    - "docker build -t <jarfile_Name>:<Tag> .
- Once docker image is created, you can check it
    - "docker images"
- Run the docker
    - "docker run -p 8081:8080 <jarfile_Name>
- Open localhost:8081/API_Name
- DONE!
  

More to be continued...
