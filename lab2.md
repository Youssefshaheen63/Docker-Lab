### 1
#### Run a container nginx with name my-nginx and attach 2 volumes to the container using volume mount 
![alt text](image-30.png)

#### Volume1 for containing static html file
![alt text](image-28.png)

#### Volume2 for containing nginx configuration
![alt text](image-29.png)

#### Edit the html content 
![alt text](image-31.png)


#### Remove the container 
![alt text](image-32.png)

#### un a new 2 containers with the following:
#### o Attach the two volumes that were attached to the previous container
#### using volume mount
#### o Map port 80 to port 8080 on you host machine
#### o Access the html files from your browser
![alt text](image-33.png)
![alt text](image-34.png)
![alt text](image-35.png)

-----
### 2
#### Run a container Nginx with name nginx-bind-mount and attach 2 volumes using bind mount under any paths
![alt text](image-36.png)
![alt text](image-38.png)
![alt text](image-39.png)
#### Remove the container 
![alt text](image-40.png)


#### Run a new container with the following: 
####  o Attach the two volumes that were attached to the previous container
####  o Check the old data in the new containers
![alt text](image-41.png)
![alt text](image-42.png)