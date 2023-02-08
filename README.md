# Getting Started with Create React App

We Create Project by running the npx create-react-app and we give it a project name after downloading the required packages we can start the project by using npm start command


### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


### Created Components For Cards For User Data

Here we used CardsGrid as a component to display user data as cards 

### To Fetch API Data

The Fetch API provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline, such as requests and responses.It also provides a global fetch() method that provides an easy, logical way to fetch resources asynchronously across the network.By using this method we will be able to fetch the data form the api

### To Navigate to users page
Create React App doesn't include page routing.So we use react-router-dom npm package as it can be used to navigate through pages we install it by using the npm install package 

### Deploying Website on Github Pages
Create a Repository 
```
1)git init-To initialize git 
2)gid add .-command to add all files
3)git commit -m "first commit"-to commit file changes
  git branch -M main-to change branch
  git remote add orgin https//:github.com/VDeepthi11/react-assignment.git
  git push -u origin main
 4)npm i gh-pages-To install github pages
 ```
 ### Making changes in package.json file
 
 We add this code at start
 ```
 "homepage":"https://vdeepthi11.github.io/react-assignment
```
 next script
 We add two commands in scripts section
  ```
 "predeploy":"npm run build",
 "deploy":"gh-pages -d build",
 ```
 ### Final Deployment
 
 We open our project terminal and run the command npm run deploy which will deploy the website in github pages


