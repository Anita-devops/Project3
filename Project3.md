## MERN STACK IMPLEMENTATION

### BACKEND CONFIGURATION
### To Update ubuntu
`sudo apt update`
![Apache Status3](./images/Apache-Status3-1.PNG)
![Apache Status3](./images/Apache-Status3-2.PNG)

### To Upgrade ubuntu
`sudo apt upgrade`
![Apache Status3](./images/Apache-Status3-3.PNG)

### To get the location of Node.js software from Ubuntu repositories
`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`
![Apache Status3](./images/Apache-Status3-4.PNG)
![Apache Status3](./images/Apache-Status3-5.PNG)

### To install Node.js on the server
`sudo apt-get install -y nodejs`
![Apache Status3](./images/Apache-Status3-6.PNG)

### To verify installation of nodejs and npm
`node -v`
`npm -v`
![Apache Status3](./images/Apache-Status3-7.PNG)

### Application Code Setup
### To create a new directory for To-Do project and verify
`mkdir Todo`
`ls`
![Apache Status3](./images/Apache-Status3-8.PNG)

### To change directory to Todo and initialize project Todo
`cd Todo`
`npm init`
![Apache Status3](./images/Apache-Status3-9.PNG)
![Apache Status3](./images/Apache-Status3-10.PNG)

# To Install ExpressJS
## To install Express using npm
`npm install express`
![Apache Status3](./images/Apache-Status3-11.PNG)

## To create file index.js and confirm creation
`touch index.js`
`ls`
![Apache Status3](./images/Apache-Status3-12.PNG)

## To install the dotenv module
`npm install dotenv`
![Apache Status3](./images/Apache-Status3-13.PNG)

## To open the index.js file, copy code into it and save
`vim index.js`
![Apache Status3](./images/Apache-Status3-14.PNG)

## To start our server
`node index.js`
![Apache Status3](./images/Apache-Status3-15.PNG)
	[The server on port 5000](http://54.196.28.129:5000/)
![Apache Status3](./images/Apache-Status3-16.PNG)

## Routes
*To create a folder routes, create a file in it and write a command in the file*
`mkdir routes`
`cd routes`
`touch api.js`
`vi api.js`

![Apache Status3](./images/Apache-Status3-17.PNG)

