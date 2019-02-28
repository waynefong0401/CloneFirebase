# CloneFirebase
Clone Firebase project from one account to another

Need to install node.js

      https://nodejs.org/en/download/
      
Need to install Firebase functions(only admin)

for mac users : 

      npm install --save firebase-admin
      
To get the Firebase database key(for both source and destination), 

go to dashboard -> Users and permissions -> Service accounts ->

select Node.js -> Generate new private key

The key will only be used to clone the DB.

To run the script

      node copyFirestoreDB.js
      

