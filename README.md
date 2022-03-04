# PocketDoc Coding Challenge
Create a simple TODO app in a git repo (GitHub, BitBucket, etc...). If' you'd like, 
you can fork this repo and add your code. The app will consist of a ReactJS single page app, that makes requests to a restful API written 
in golang. The API will persist data to a database or file

## Front-End
Create a web-based ReactJS application that allows a user to create and manage a 
list of tasks (to-dos), with the following scope:  
1. List existing to-do items
2. Create new to-dos
3. Change the status of a to-do (for exampe: "completed")
4. Delete to-dos
5. Prioritize to-dos
6. Sort by due-date 

The front end will call a restful API to persist and modify the to-do data.

## API Back-End
Create a restful API using golang. The API will accept resquests from the React 
app and respond with data in a JSON format. Incoming request parameters can be in 
JSON, or as URL query params. The API should persist data, the choice of how is up 
to you. You can utilize any database that you'd like, or simply save and load data 
from a file JSON file on the local machine (JOSN, CSV, etc...)


## Bonus Points
Extra points for implementing any of these features:
1. Basic authentication with Javascript Web Tokens (JWT)
2. Host the application remotely (AWS, GCP, etc...) 