<a name="br1"></a> 

**Docker**


# What is Docker ?

● Docker is a containerization plateform for developing , packaging, shipping, and running applications.

● Its provide the ability to running an application in an isolated

environment called a container

# Why do we need a Docker ?

**Explaining with the example :**

Your developers write code locally and share their work with their colleagues using Docker containers. They use Docker to push their applications into a test environment and run automated and manual tests.

**● The code is not running when**

Developer -----------------> Testing Team **(but its not running my machine)**

code

●

**The code is running when**

Developer--------> docker-------> packaging docker image -------->Testing Team

code                help                    container               run code


# Why is a container ?

● A way of packaging an application dependencies and configuration.

● It can be easily shared.



<a name="br2"></a> 

**Architecture**

**(Container)**

**—---------------------------------------**

**3\_Docker engine**

**—--------------------------------------**

**2\_Operating system**

**—--------------------------------------**

**1\_Hardware**

**—------------------------------------------**

**How to create Container ?**

Dockerfile ------------> docker image ---------> container1

container2

container3



<a name="br3"></a> 

**● Installation of Docker**

sudo apt install docker.io

**● Check version**

docker –version

**● Run a Container:**

docker run IMAGE

**● List Running Containers:**

docker ps

**● List All Containers (including stopped ones):**

docker ps -a

**● Stop a Running Container:**

docker stop CONTAINER\_ID

**● Remove a Stopped Container:**

docker rm CONTAINER\_ID



<a name="br4"></a> 

**● List Local Images:**

docker images

**● Pull an Image from Docker Hub:**

docker pull IMAGE\_NAME[:TAG]

**● Build an Image from a Dockerfile:**

docker build -t IMAGE\_NAME[:TAG] PATH\_TO\_DOCKERFILE

**● Remove an Image:**

docker rmi IMAGE\_ID

**● Inspect Container Details:**

docker inspect CONTAINER\_I

**● View Container Logs:**

docker logs CONTAINER\_ID

