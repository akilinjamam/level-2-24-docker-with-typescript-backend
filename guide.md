- to create docker image and type:
  1st: docker build .

- to see running docker image and type:
  2nd: docker ps

- to see all images with running image and type
  3rd: docker ps -a

- to run docker container copy docker image id and type:
  4th: docker run -p 5000:5000 image-id

- to run docker container (with dittached mode) copy docker image id and type:
  4th: docker run -p 5000:5000 -d image-id

- to stock docker container and type:
  5th: docker container stop copy-name-of-image

  -to run docker container with attached mode type: docker container -a name-of-image

- to get docker build related help type: docker build --help
- to get docker run related help type: docker run --helps
- to get docker related help type: docker --helps
- to see docker images type docker images
- to remove docker container type: docker container rm docker-container-name
- to remove all docker container type: docker container prune
- to remove docker image type: docker image rmi image-id
- to remove all docker images type: docker image prune
- run container and when container will be exit, it will be automatically deleted and type: docker run -p 5000:5000 --rm image-id
- to build docker container with tag name type: docker build -t docker-typescript:1 .
  -to run docker container with tag name type: docker run -p 5000:5000 --rm REPOSITORY:tag
  example: docker run -p 5000:5000 --rm docker-typescript:1
- to run docker container with giving custom name type: docker run -p 5000:5000 --rm --name docker-app docker-typescript:1
- to remove docker all images when it has repository name and tag type: docker image prune -a
