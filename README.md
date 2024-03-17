# OneIDE
An open source Browser integrated development environment

# Features
1. User login
2. Choice of muliple programming languages - CPP , JAVA , Python , Javascript
3. Output on same screen
4. Ability to download file/code snippet
5. Dark/light mode
6. Code is automatically saved in browser
   
# Libraries Used

1. React
2. Material UI
3. ----- TBD

# Architecture

Overview: 
The idea is to map the IP address of the corresponding domain name , and port to a Docker container
We will dynamically allocate containers , out of physical hosts , which can be scaled up or down as per need.
Every time a user either refreshes or opens a new editor window , a new container will be allocated. We will scale up the physical hosts , if more containers are needed.
 
