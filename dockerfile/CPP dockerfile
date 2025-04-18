
# get the base image

FROM frolvlad/alpine-gxx

#reate a working directory to save all the working files
WORKDIR /app

#copy file
COPY helloworld.cpp /app

#complie the code
RUN g++ helloworld.cpp

#Run command

CMD ["./a.out"]
