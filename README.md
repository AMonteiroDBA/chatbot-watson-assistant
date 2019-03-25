# chatbot-watson-assistant
Chatbot using Watson Assistant

This is an example of how to use a IBM Watson Assistant with Node.js
To use it, just create a Watson Assistant, put the credentials on it and then deploy it to Bluemix.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/AmonteiroDBA/chatbot-watson-assistant)

OR

## To execute this app locally

1. [Install Node.js][]
2. Go to project root folder
3. Execute `npm install` to install app dependencies
4. Change the config/bot.js file and put the Watson Assistant credentials and workspace_id in the following files:
```
   username = "<username>";
   password = "<password>";
   conversationWorkspace = "<workspace_id>";
```
+ Execute `npm start` to start the app
+ Access the application in the browser at <http://localhost:6001>

[Install Node.js]: https://nodejs.org/en/download/
"# chatbot-watson-assistant"
