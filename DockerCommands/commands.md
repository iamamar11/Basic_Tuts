## Commands for the Dockers

| Commands          | Description      |
| :-----------------:|:-----------------:|
| `docker run docker/whalesay cowsay HELLO THERE`| *This command is use to run the conatiner of specific image. Here we are running container of whalesay image from docker hub* |
| `docker pull docker/whalesay cowsay` | *This command is used to download the image and later can be run using the run command* |
| `docker ps | docker ps -a ` | *This command is used to get the info of current container(**without -a**) and (**with -a**) for all the container present on machine* |
| `docker stop containerName ` | *This command is used to stop the running container* |
| `docker rm contianerName ` | *This command is used to remove the container from the machine Permanently* |
| `docker images` | *This command is used to get the list of all the downloaded and userdefined images on the machine* |
| `docker rmi imageName ` | *This command is used to delete the image from the machine permanently* |~