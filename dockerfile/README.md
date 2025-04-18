 # Commands that are used to create a dockerfile

### First create a directory for project ***
- mkdir dockerproject

* Create code file ####
- helloworld.cpp

* test the it on local ####
- g++ helloworld.cpp

### output ####
- ./a.out

### create dockerfile name dockerfile ####
- vim dockerfile

### Build docker image ####
- docker build -t giveimagename:versionname . # full stop indicates from same directory

### Docker check images
- docker get images

### Docker run image
- docker run giveimagename:versionname    #versionn name is tag for the image 
