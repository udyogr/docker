Inspiration [@CodeWithMosh](https://www.youtube.com/watch?v=pTFZFxd4hOI)

Install docker (brew install docker on Mac)

Install docker [desktop](https://www.docker.com/products/docker-desktop/) in case trouble running daemon from CLI

1. Build a simple javascript app that logs a message.

2. Add a docker file, use node image built on top of linux OS(alpine)

3. Build docker image for the app

    `docker build -t <name_of_tag> <path_of_docker_file>`

4. See docker image generated 

    `docker images`

    `REPOSITORY        TAG       IMAGE ID       CREATED             SIZE`
  
    `hello-docker-mg   latest    e90dd704caa1   31 minutes ago      179MB`
  
    `<none>            <none>    4d0630500795   45 minutes ago      179MB`
  
    `<none>            <none>    de4ddaacea77   About an hour ago   179MB`
  
    `hello-world       latest    b038788ddb22   3 months ago        9.14kB`

5. Run docker image successfully created.

    `docker run <image_tag>`
  
6. See the output from the containerized app.
   
    `Hello Docker World!`

7. Pull a remote docker image from docker hub
   
   `docker pull <docker_hub_image_tag>`
   
