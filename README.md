# publishing-doc-img
# install docker desktop and also install docker and wsl extension in vscode
# create Dockerfile in your project
# the basic code for Dockerfile --> FROM nginx:alpine
#                               --> COPY src/usr/share/nginx/html (or) a default syntax - COPY . /usr/share/nginx/html
# to check the current running container: docker ps
# to stop the previous process: docker stop container_name (or) container_id
# to clean the network: docker network ls (or) docker network rm network_name (or) network_id
# to build: docker build -t image_name
# run: docker run -d -p 80:80 image_name
# check in docker desktop - the image is created successfully
