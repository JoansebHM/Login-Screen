In order to successfully start the program, mongodb and npm must be installed on the system and added to the environment variables in order to execute them from the terminal.

Once installed, run the command: npm run dev , in the visual code console, so that you can start the server and connect to the database automatically. If everything goes well, the console should display 2 messages saying that the server is on port 3000 and that the database is connected.

At this point you can now enter your web browser and set localhost:3000 to open the server.

Once you have completed the above steps, open another console and type the mongosh command to open the database, then enter the database we have created, with the command: Use node-login-passport-local . Once in, type the command: db.users.find() , to be able to see the users registered at that time.

Now the application is ready to save users in the database and authenticate them. Moreover you can see in the database as <br> users are registered.
