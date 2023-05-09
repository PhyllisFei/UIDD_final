# UIDD_final
## Deployment
The application will be running based on Node.js. Below are the steps for configurations:
### 1. Make sure you have Node and npm installed: (https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
Check to see if you can run  ``$ node -v`` and ``$ npm -v``
### 2. Install the Express module using npm. 
ex: ``$ npm install express``
### 3. Run the starter app using Node:
ex: ``$ node App.js``

You should see the message ``Server is running on http://localhost:8000``

If you instead see an error message like ``Error: Cannot find module 'express'`` -- see step 2. 
### 4. Enter the app
Open a web browser (e.g. Google Chrome) to this URL: ``http://localhost:8000/``

## OpenAI API Key Register
One big intelligent part of this app relies on calling the ChatGPT API to generate a welcome message based on how many lives the app user has saved via donating blood. 
But in order to use the API, you need to register and retrieve your own OpenAI API key at https://platform.openai.com/account/api-keys: simply click on "Create new secret key", 
copy the key it generates, and put it in the ``Your Own OpenAI API key`` field at line 104 in ``app1.html``

We are not able to provide our own OpenAI API key because the system will automatically detect it as a leaking information and disable the OpenAI API key immediately.

## Other Things to Notice
You can enter any ``Email address`` or ``Password`` at the login page. But there just has to be one in order to be able to click the ``Sign In`` button and go into the next 
page.
