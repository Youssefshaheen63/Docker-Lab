#### What is the difference between:
CMD: 
  - default command 
  - can it change when container running
  - can use default args

ENTRYPOINT:
   - main command
   - usually fixed
   - use when need conatiner do task
-----
### 1
#### Run the container hello-world
![alt text](image.png)

#### Check container status
![alt text](image-1.png)


#### Start the stopped container
![alt text](image-2.png)


#### Remove the container
![alt text](image-3.png)

#### Remove the image
![alt text](image-4.png)

-----
### 2
#### Run container centos or ubuntu in an interactive mode
![alt text](image-5.png)

#### Run the following command in the container “echo docker ”
![alt text](image-6.png)

#### Open a bash shell in the container and touch a file named hello-docker
![alt text](image-7.png)

#### Exit container
![alt text](image-8.png)

#### Stop the container and remove it. Write your comment about the file hello-docker
![alt text](image-9.png)

Once i remove the conainer the file is deleted.

#### Remove all stopped containers
![alt text](image-10.png)


-----
### 3
#### Deploy a MySQL database called app-database. Use the mysql latest image, and use the -e flag to set MYSQL_ROOT_PASSWORD to P4sSw0rd0!. The container should run in the background.

![alt text](image-11.png)

-----
### 4
#### Run nginx
![alt text](image-12.png)
![alt text](image-13.png)

#### Add html static files to the container and make sure they are accessible
![alt text](image-14.png)
![alt text](image-15.png)
![alt text](image-16.png)

#### Commit the container with image name IMAGE_NAME
![alt text](image-17.png)

-----
### 5
#### Create a python simple app
![alt text](image-18.png)
![alt text](image-19.png)

#### Create a dockerfile to containerize the python app
![alt text](image-21.png)

#### Build the image and test it
![alt text](image-22.png)
![alt text](image-23.png)

#### Push the created image into your docker hub repo
![alt text](image-24.png)
![alt text](image-25.png)
![alt text](image-26.png)
![alt text](image-27.png)
