# Developer Community Application

The project is designed for developers to connect with each other.
 
It has a number of modules such as register/login, profile, education, experience, posts. 

Developers can discuss and post stuffs as well as view the profiles of everyone. 

## Screenshots

![alt text](https://github.com/Manas-Chamola/dev-community/blob/master/demo_images/Landing.jpg?raw=true)


![alt text](https://github.com/Manas-Chamola/dev-community/blob/master/demo_images/Dashboard.jpg?raw=true)


![alt text](https://github.com/Manas-Chamola/dev-community/blob/master/demo_images/Developers.jpg?raw=true)


![alt text](https://github.com/Manas-Chamola/dev-community/blob/master/demo_images/Posts.jpg?raw=true)


![alt text](https://github.com/Manas-Chamola/dev-community/blob/master/demo_images/Discussion.jpg?raw=true)

## Features

* Authentication
* Private Routes
* JWT Token
* Profile, Education, Experience
* Developer Profiles
* Github Repos
* Posts section
* Discussion section
* Like Posts

## Demo: [Click Here](https://mighty-dawn-57628.herokuapp.com/)

## Setup

### 1.
```
git clone https://github.com/Manas-Chamola/dev-community.git
``` 

### 2.
Create a new MongoDB Cloud Database 

### 3.
Go to your Github profile. Under Settings, go to OAuth Apps and create a new OAuth App. You will get a githubClientId and githubSecret

## 4.
Go to the config folder and open the production.json and put your MongoDB instance URI and the githubClientId and githubSecret

### 5.
```
npm start

or

yarn start
```