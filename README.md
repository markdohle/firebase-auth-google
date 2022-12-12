# firebase-auth-google
MIT xPro Week 26 - Firebase Authentication Using Google

## Firebase Authentication With OAuth2

Most applications need to implement some sort of authentication mechanism to identify their users. Knowing a user’s identity allows the application to provide personalized experiences across multiple devices. Firebase Authentication provides back-end services and ready-made UI libraries to authenticate users to your app. 

To sign a user into your app, you first receive authentication credentials from them. These credentials can be the user's email address and password or, alternatively, an OAuth token from a federated identity provider such as Facebook or Google.

In this week’s videos, you’ve seen how to implement Firebase Authentication using a username and password combination. Your task in this activity is to give your users another way to log in with the Google identity provider. Download the starter files Links to an external site. to begin. 

Here’s how it will work:

- The login page will contain a button asking the user to “log in using Google.” 

- Once the user clicks on that button, a pop-up asking them to log into their Google account will be displayed. 

- After a successful Google login, the pop-up is closed, and the user is sent back to your application, where the following message should be displayed: “You are logged in using the following email: user-email.” (User-email should be the user’s email address.)
