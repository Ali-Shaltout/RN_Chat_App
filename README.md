# React Native Simple Chat


# The App
  - The app is a simple Global chat application using React Native, Redux and Firebase

# Firebase configuration. 
You will need to setup your firebase account, then create the file `src/firebase.js` and add the credentials there.

#### Example file (firebase.js)
```
import * as firebase from 'firebase';

const config = {
    apiKey: "API_KEY",
    authDomain: "AUTH_DOMAIN_HERE",
    databaseURL: "DATABASE_URL_HERE",
    projectId: "PROJECT_ID_HERE",
    storageBucket: "",
    messagingSenderId: "SENDER_ID_HERE"
};
firebase.initializeApp(config);

export default firebase;

```
