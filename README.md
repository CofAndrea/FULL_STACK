# FULL_STACK

    REACT.JS, NODE.JS MONGODB

---

i've been trying to replicate the facebook site and some of its functionalities such as:
-create an account
-log in
-log out
-search for others account
-send friend request
-create/delete a post(both text and images)

---

### Objective

## I didn't create every functionality of the site because the main goal for this project was to refine the knowledge of react.js and node.js. Doing that I discovered a lot of cool functions and a lot of very useful npm packages that made the work a lot lighter.

I've also learnt how to use google APIs for email verification of the account. The best part is that I made a lot of CSS practice, which I have to say it's not my best skill so it was pretty helpful to work with it in this project.

---

## What can you actually do with this

Once you set up the database you can play with creating a user, choosing a profile and a cover picture, sending friend requests, creating posts with images, commenting on posts, react to posts.

---

Remember that this project for me has been a test, i'm not going to deploy it or try and create an actual clone of Facebook and it is not a perfect copy as well.

---

## Getting Started

- download the zip and extract files
- open your editor of choice
- go to terminal and go to frontend and backend folders
- npm install for all the packages
- npm start for both and the app will run on your local host

## IMPORTANT IF YOU WANT TO TEST IT

you will need a .env file with the following key in the frontend:

```
REACT_APP_BACKEND_URL
```

and one in the backend with these:

```
PORT=_your value_
DATABASE_URL=_your value_
TOKEN_SECRET=_your value_

BASE_URL=_your value_
EMAIL=_your value_
MAILING_ID=_your value_
MAILING_SECRET=_your value_
MAILING_REFRESH=_your value_
CLOUD_NAME=_your value_
CLOUD_API_KEY=_your value_
CLOUD_API_SECRET=_your value_


```

---

the MAILING ones are all the keys you will get setting up google OAuth, the CLOUD ones are from [https://cloudinary.com/](https://cloudinary.com/)

Andrea Coffetti.

[https://twitter.com/andrea_coffetti](https://twitter.com/andrea_coffetti).
[https://github.com/CofAndrea](https://github.com/CofAndrea).

Version History.
0.1.
Initial Release.
