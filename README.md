# Chatbot
Simple ChatBot using api.ai.javascript

Required AngularCLI.

-->go to the chatbot using cmd or terminal.
Now install npm packges using forllowing command.

$ npm install

-->Create your account in api.ai. It's free for learners.

https://dialogflow.com/

-->Add agent name and then choose simple chat or whatever you want.

-->Add simple kind of questions and it's response.

-->Test your questions and it's reponse from the same site.

-->Right side click on agent name/view all agent

-->Go to your agentname and choose Client access token.

Add this client access token to 'chatboat/src/environment.ts'.

===>(*Now make sure that your @angular/cli version should not be >1.5.0
If it is >1.5.0 then uninstall it and install 1.4.10 version.

npm uninstall -g @angular/cli

npm install -g @angular/cli@">=1.4.0 <1.5.0"

)<===

start your chatbot app using:-
ng serve 

Opent your browser and go on:- 
localhost:4200
