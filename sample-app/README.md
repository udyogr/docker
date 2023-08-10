Install docker (brew install docker on Mac)

Install docker [desktop](https://www.docker.com/products/docker-desktop/) in case trouble running daemon from CLI

1. Build a simple js app that logs a message.

2. Add a docker file, use node image built on top of linux OS(alpine)

3. Build docker image for the app

  `docker build -t <name_of_tag>hello-docker-mg <path_of_docker_file>`

4. See docker image generated 

  `docker images`

5. Run docker image successfully created.

  `docker run <image_tag>`

6. See the output from the containerized app.

7. Output
   `Hello Docker World!`
