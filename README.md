## Passport Starter

Starting point for the youtube tutorial series @ https://www.youtube.com/watch?v=A23O4aUftXk

In this tutorial series we'll be learning how to use different passport strategies for OAuth2 login 
authentication for some of your favorite socials including Facebook, Instagram, Google, Twitch, Github, and Amazon!

#1. git clone passport-starter
#2. npm install express cors passport passport-facebook chalk
#3. create server directory and index.js inside it
#4. sudo npm install passport-amazon passport-github passport-instagram passport-twitch passport-twitter passport-google-oauth20
#5. sudo npm install @material-ui/core @material-ui/icons lodash react-router react-router-dom
#6. sudo npm install concurrently http-proxy-middleware

 "server": "nodemon server/index.js",
    "dev": "concurrently --kill-others \"npm run start\" \"npm run server\" "
    "proxy": "http://localhost:5000",# react-and-express-passport-app-boilerplate
