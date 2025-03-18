# Social-Network-MERN-Stack

## Project Screenshots:
![image](https://github.com/user-attachments/assets/53c8a21c-85ac-4716-b347-faf2b495decc)
![Uploading image.png…]()

![image](https://github.com/user-attachments/assets/2af773e1-4148-49ad-b3a1-faff811d382e)

![image](https://github.com/user-attachments/assets/acc49360-b703-4cfe-8521-5f20515308b8)
![image](https://github.com/user-attachments/assets/4a9db2c6-dc04-4fbf-bb1a-a4c0c6e37cc9)
![image](https://github.com/user-attachments/assets/8b2d614f-b4fe-4a7d-b4d0-72fd4225041b)


## Built With
- **React** - A JavaScript library for building user interfaces
- **Redux** - State management
- **Semantic UI React** - UI framework
- **Socket.io** - Used for real-time features
- **Node.js** - Used for backend
- **MongoDB** - Database

## Features
- Like posts, comments, replies
- See likes for posts, comments, replies
- Follow, unfollow users
- Update user information
- Search users
- Tag people on posts and in comments with autocomplete
- Send verification emails
- Pagination for:
  - Home feed
  - User profile
  - Hashtag page
  - Location page
  - Notifications
  - Comments
  - Replies

## Real-Time Features
- Get notifications when someone:
  - Likes your post, comment, or reply
  - Tags you in a post or replies to your comment
- Chat functionality:
  - Send text messages and images
  - Seen feature and activity status of users

## Installing
### Install dependencies
```sh
npm i && cd client && npm i && cd ..
```

### Create `variables.env` file and configure it with your values
```
NODE_ENV=development
DATABASE="Mongodb Connection String"
JWT_KEY="secretkey"
EMAILUSER="example@gmail.com"
EMAILPASS="example"
HOST="your ip e.g. http://192.168.0.14:5000"
ENABLE_SEND_EMAIL="true or false" # false if you don't want to set it up
TEST_DATABASE="testing db"
```

### Configure socket connection
Go to `client/src/_services/socketService.js` and replace:
```js
window.location.hostname
```
with your local IP address on port 5000, e.g.,
```
192.168.0.14:5000
```

## Running the Project
```sh
npm run dev
```


## Contribute
Show your support by ⭐ the project.

