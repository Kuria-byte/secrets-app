# Intro
![start](https://user-images.githubusercontent.com/61579772/93634517-50864e80-fa23-11ea-9a01-105141a1a10a.jpg)
![secret](https://user-images.githubusercontent.com/61579772/93634252-deae0500-fa22-11ea-9fcf-bd9e4892fd2b.jpg)
- live: https://boiling-anchorage-46886.herokuapp.com/

# About
- Learning user website Authentication
- Passport strategy for authenticating with ***Facebook and Google using the OAuth 2.0 API.***
- This lets you authenticate using Facebook/Google in your Node.js applications. By plugging into Passport, Facebook/Google authentication can be easily and unobtrusively integrated into any application or framework that supports ***Connect-style middleware***, including Express.

## What I learnt📐
- PassportJs & Cookie sessions for Authentication
- Bcrypt,Hashing and salting
- Hashing using MD5
- Passport google oauth2
- Deploying node.js app to Heroku
- Setting up environment configurations
- MongoDb databse operations

## Version 1
- Each user can commit one secret under there user.id
- Secrets submitted stay annonymous
- User Interface will be updated in *** version 2.0.0.0 ***

## Configure Strategy
- The Facebook authentication strategy authenticates users using a Facebook account and OAuth 2.0 tokens.
- The app ID and secret obtained when creating an application are supplied as options when creating the strategy.
- The strategy also requires a verify callback, which receives the access token and optional refresh token, as well as profile which contains the authenticated user's Facebook profile. The verify callback must call cb providing a user to complete authentication.

### References❤
- https://www.geeksforgeeks.org/password-hashing-with-md5-module-in-node-js/
- https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/
- https://www.thesslstore.com/blog/difference-encryption-hashing-salting/

