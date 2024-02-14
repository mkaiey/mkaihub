# Build and Deploy a Github-like App | React, MongoDB, Express.js, Passport.js

![Demo App](https://res.cloudinary.com/dymu4drhj/image/upload/v1/Mkaidev/wluwngu5wokxypxmf4c3?_a=BAVAfVBy0)

Some Features:

-   ⚙️ Tech stack: MERN + TailwindCSS + Github API
-   🔑 Authentication && Authorization with Passport.js (Github Auth)
-   👾 Fetch Github User Profiles and Repos
-   🚀 Filter Repos on the Client
-   🎭 Learn behind the scenes for authentication
-   🐛 Error handling (both on the server and on the client)
-   🎃 At the end DEPLOY like a pro for FREE!
-   ⏳ And much more!

### Setup .env file

```js
PORT=5000
MONGO_URI=
GITHUB_API_KEY=
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
CLIENT_BASE_URL=
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```

### Deployment steps

```shell
SETUP server.js (express.static and res.sendFile for react app)
SETUP "build" and "start" scripts in package.json
Deploy on render.com with env variables
Update Github OAuth App (homepage url and callback url)
Add CLIENT_BASE_URL as env variable on render
Update the callback url on github.auth.js to full url (deployed url)
```