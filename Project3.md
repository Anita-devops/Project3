## MERN STACK IMPLEMENTATION

### BACKEND CONFIGURATION
### To Update ubuntu
`sudo apt update`
![Apache Status3](Images/Apache-Status3-1.png)
![Apache Status3](Images/Apache-Status3-2.png)


### To Upgrade ubuntu
`sudo apt upgrade`
![Apache Status3](images/Apache-Status3-3.png)

### To get the location of Node.js software from Ubuntu repositories
`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`
![Apache Status3](Images/Apache-Status3-4.png)
![Apache Status3](Images/Apache-Status3-5.png)

### To install Node.js on the server
`sudo apt-get install -y nodejs`
![Apache Status3](images/Apache-Status3-6.png)

### To verify installation of nodejs and npm
`node -v`
`npm -v`
![Apache Status3](images/Apache-Status3-7.png)

### Application Code Setup
### To create a new directory for To-Do project and verify
`mkdir Todo`
`ls`
![Apache Status3](images/Apache-Status3-8.png)

### To change directory to Todo and initialize project Todo
`cd Todo`
`npm init`
![Apache Status3](images/Apache-Status3-9.png)
![Apache Status3](images/Apache-Status3-10.png)

# To Install ExpressJS
## To install Express using npm
`npm install express`
![Apache Status3](images/Apache-Status3-11.png)

## To create file index.js and confirm creation
`touch index.js`
`ls`
![Apache Status3](images/Apache-Status3-12.png)

## To install the dotenv module
`npm install dotenv`
![Apache Status3](images/Apache-Status3-13.png)

## To open the index.js file, copy code into it and save
`vim index.js`
![Apache Status3](images/Apache-Status3-14.png)

## To start our server
`node index.js`
![Apache Status3](images/Apache-Status3-15.png)
![Alt text](Images/Apache-Status3-16.png)

## Routes
*To create a folder routes, create a file in it and write a command in the file*
`mkdir routes`
`cd routes`
`touch api.js`
`vi api.js`
![Apache Status3](Images/Apache-Status3-17.png)

## MONGODB DATABASE
