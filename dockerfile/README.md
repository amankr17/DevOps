 # Commands that are used to create a dockerfile

## First create a directory for project 
- mkdir dockerproject

#### Create code file 
- helloworld.cpp

#### test the it on local 
- g++ helloworld.cpp

#### output ####
- ./a.out

## create dockerfile name dockerfile 
- vim dockerfile

## Build docker image ####
- docker build -t giveimagename:versionname . ***(Full stop indicates from same directory)***
- docker buildx build --platform linux/amd64,linux/arm64 -t giveimagename:versionname .  ***(Alternative solution)***

## Docker check images
- docker get images

### Docker run image
- docker run -d giveimagename:versionname   ***(version name is tag for the image)*** 
