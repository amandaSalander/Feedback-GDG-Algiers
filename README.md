# Feedback-GDG-Algiers
Feedback app made with Polymer and Firebase for GCP Next 2017 GDG Algiers, you can try [demo](https://authwithfirebase.firebaseapp.com)


## install bower
npm install -g bower

you can either install firebase cli or polymer cli

## install firebase cli
npm install -g firebase-tools

## install polymer-cli
npm install -g polymer-cli

## clone the repository
git clone https://github.com/amandaSalander/Feedback-GDG-Algiers.git

cd Feedback-GDG-Algiers

## update bower.json
bower update

in your [console](https://console.firebase.google.com/) create a new project

enable Google authentication in Authentication/ SIGN-IN METHOD

in the overview of your project click on **Add Firebase to your web app** 

<script>
  // Initialize Firebase
  var config = {
    apiKey: "your-api-key",
    authDomain: "your-auth-domain",
    databaseURL: "your-database-url",
    storageBucket: "your-storage-bucket",
    messagingSenderId: "your-messaging-sende-id"
  };
  firebase.initializeApp(config);
</script>

in the index.html change the attributes values of firebase-app to your project configuration

  <firebase-app
    name="your-app-name"
    api-key="your-api-key"
    auth-domain="your-auth-domain"
    database-url="your-database-url">
  </firebase-app>

save and now you can serve your app

## serve the app with Polymer serve
polymer serve --open --port 5000


## serve the app with firebase serve
firebase serve


## you can depoly the app with
firebase deploy



## Enjoy !
leave your comments about the GCP Next 2017 Algiers
