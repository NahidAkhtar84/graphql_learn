# Start

1. Run this command:
```npm init```

   * And enter several times.

2. Install all the required packages:
   
   Command: ```npm i express express-graphql graphql```

3. Install nodemon as dev dependency (It will hep us to reload our server saving it without reloading it manually.)
   
   Command: ```npm i --save-dev nodemon```

4. Now add this command to script of package.json
   ```"devStart": "nodemon server.js"``` and rename the main key-value as ```"server.js"```

5. Now setup ```server.js``` and run the command to Run:

    Command: ```npm run devStart```

