# User Authentication With Firebase Services

Sign Up users with their Email | Google | Facebook | Github accounts into your application.<br/>
A React application made using Firebase.<br/>

### Installation

Clone the repository, install the dependencies and start the server.

```sh
cd firebase-auth
yarn
yarn start
```

Include a .env file in project root with Api Key and Auth Domain from your [Firebase Console](https://console.firebase.google.com):

```
REACT_APP_APIKEY = ''
REACT_APP_AUTHDOMAIN = ''
```

To complete setup, register your app with the platform specific OAuth service and obtain **APP ID** and **APP Secret**
[Register Facebook Login](https://developers.facebook.com/apps) <br/>
[Register Github Login](https://github.com/settings/developers)

![App Promo](firebase-auth.gif)
