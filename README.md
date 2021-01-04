## Gaol : Basics of docker

## CHALLENGE: Docker¶

Repository: challenge-docker
Type of Challenge: Learning
Duration: 4 hours

Team challenge : solo

## Mission:

*Know the basics of Docker in order to be effective for the next project.*


The project must reproduce this architecture:

/app   
    |-docker  
    |   |-Dockerfile -> your Dockerfile  
    |-pipeline  
    |   |
    |   |-model  
    |   |    |-model.py -> print a number between 1 and 400  
    |   |-preprocessing  
    |   |    |-preprocessing.py -> print a numpy array  
    |   |-utils  
    |   |    |-utils.py -> print "in progress..."  

## Learning Objectives

-> Images
-> Containers
-> Volumes

At the end of the challenge, you will be able to:

- Create your own Dockerfile.
- Build a Docker image.
- Run a Docker container.
- Add a Docker volume to your container.
- Manage your images
- Manage your containers

##Steps

1- Create a github repository.
2- Create the above directory structure in it.
3- Create a Dockerfile that copy those files in an /app folder and run the model.py file.
4- Build your image
5- Run a container and verify that it prints the ouput of your model.py file.
6- Connect to your container with SSH and run all the python files model.py, preprocessing.py, utils.py
7- Stop you container and delete it (check that there are no more containers running with docker container ls -a)
8- Run a new container using a volume to do changes without stopping the container and saving your changes. Connect to SSH so it stays running.
9- Add two lines of code in each files locally (be creative!)
10- Re-run all your python files to verify that the changes are effective in your container.
11- Delete all your containers and images.
12- Push your repo with your Dockerfile.

## requirements:

install requirements by executing the following code from your terminal
        - for Python3 ```pip3 install -r requirements.txt```
        - for Python2 ```pip install -r requirements.txt```

## Other:
feel free to use it, feedback, and upgrade!

