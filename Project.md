## Create GKE cluster and Deploy in it
- Open cloud shell
- Run 'docker run -p 8080:80 nginx:latest' to start the docker image
- Run 'docker run -d -p 8080:80 nginx:latest' to start the docker image in the background
- Check preview in new tab to visit the website
- Run 'docker ps' to see all the running docker images
- Run 'docker ps -a' to see all the docker images
- Copy container ID
- Run 'docker cp <.html> <containerID>:<htmlpath>
  - For example: Run 'docker cp index.html e9e6637ba7b8:/usr/share/nginx/html/'
- check preview in new tab
- It's RUNNING!

