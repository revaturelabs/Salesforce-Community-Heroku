# Salesforce App

This guide helps Salesforce developers who are new to Visual Studio Code go from zero to a deployed app using Salesforce Extensions for VS Code and Salesforce CLI.


## Multiplayer quiz app built on Salesforce technology (player app)

ℹ️ Please refer to the [quiz host app](https://github.com/fostive/quiz-host-app) for documentation.

## Heroku deploy (recommended)

Click on this button and follow the instructions to deploy the app:

<p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/revaturelabs/Salesforce-Community-Heroku/edit/master">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
  </a>
<p>

## Local setup (development only)

Create a `.env` file at the root of the project:

```
SF_LOGIN_URL='https://login.salesforce.com'
SF_USERNAME='YOUR_SALESFORCE_USERNAME'
SF_PASSWORD='YOUR_SALESFORCE_PASSWORD'
SF_TOKEN='YOUR_SALESFORCE_SECURITY_TOKEN'
QUIZ_API_KEY='YOUR_QUIZ_API_KEY'
COLLECT_PLAYER_EMAILS=false
```

Run the project with `npm start`

## 
