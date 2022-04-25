** Docker Commands

* Docker pull image

docker pull registry.access.redhat.com/ubi8/ubi:8.5

* Docker run container with hostname

docker run -it --name webserver -h webserver registry.access.redhat.com/ubi8/ubi:8.5 bash

