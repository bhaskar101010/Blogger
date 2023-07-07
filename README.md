# Blogger

> A Realtime Blog Application


 To install all the dependecies `npm` is used.

Back end is implemented using [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/). [Atlas](https://www.mongodb.com/cloud/atlas), the _Cloud_ version of [MongoDB](https://docs.mongodb.com/) is used.

This is a _responsive web application_ for viewing in Desktop.

```
This is still a work in progress
If you find any bugs you can report it to me.
Pull requests are always welcome. For major changes, 
please open an issue first to discuss what you would like to change.

```
## Features

- Latest features of JavaScript i.e. ES6, ES7, ES8 is used
- 
- ES8 `async/await` is used

<br/>

<ul>
 <li> This is Simple Blog Application </li>
 <li> It is a Full Stack Application </li>
</ul>

- All the user details, group chats and conversations are stored in the [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

<ul>
 <li>Login/Signup as well as Logout feature is added </li>
 <li>Error will be shown if the credentials are not correct</li>
</ul>

<ul>
 <li> Realtime fully functional blog application </li>
 <li> User Registration/Account Management: Users can create accounts to manage their profile </li>   
 <li> Content Management System (CMS): It provides a user-friendly interface for writing and formatting content, or deleting existing posts. </li>
 <li> Search Functionality: A search bar allows users to search for specific blogs, making it easier to find relevant content. </li>
 <li> Read / Unread status of conversation is supported</li>
 <li> All the blogs are stored in the database i.e. 
</ul>


## Tech Stack

MongoDB, Express, EJS , Node Js, Javascript ,Css ,Html

## Usage

**Test users**

| Email | Password  |
| -------- | --------- |
| bhaskar | password |

``` Or Use the  Sign In feature.  ```

### Clone the repository:
```
gh repo clone bhaskar101010/Blogger
```

### Env Variables

Create a .env file in the root and add the following

```
PORT = 5000
MONGO_URI = <yourMongoDbUri>
JWT_SECRET = <yourSecret>
```

### Install Dependencies (frontend & backend)

```
npm install

```

### Run
Run project(:5000)
```
nodemon .\app.js
```



