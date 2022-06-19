# Hello
Hello world dockerization

step 1.springboot project is running on http://localhost:8080/hello 
step 2.We opened docker then create docker image by using command : docker build -t myimage .  or docker build . -t myimage
step 3.check docker image : docker images
step 4.run that docker image on port 8080 by mapping: docker run -p 8080:8080 myimage

#currently running docker image: docker ps
#all docker image : docker ps -a

