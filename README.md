# docker_learn
Learning Docker from basics


#Tensorflow in container
To build and deploy tensorflow from the dockerfile, use the command

	> docker image build -t imagename:tag -f Dockerfile_tensorflow .
	

To run the container, 
	
	> docker container run -it imagename:tag 
