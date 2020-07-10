# receive-fax

Envrionment variables must be configured in your .env file.

ACCOUNT_SID=

AUTH_TOKEN=

SENDGRID_API_KEY=

## Pre-requisites

[twilio-cli](https://github.com/twilio/twilio-cli)

[plugin-serverless](https://github.com/twilio-labs/plugin-serverless)

## Local Setup

cd receive-fax

npm install

## Local Testing

npx twilio-run .

## To Deploy

twilio serverless:deploy
