# Thinkific Sample App

## Tech Stack:

- Node
- Express.js
- EJS
- Bootsrap 5

## Thinkific OAuth Flow:

- Authorization Code Flow - https://developers.thinkific.com/api/authorization/#authorization-code-flow

## Pre-requisites

- Partner Portal account: https://www.thinkific.com/partners/

## Instructions:

- **Partner Portal**: Create an app to get a **CLIENT_KEY** and **CLIENT_SECRET**
- **Partner Portal**: Add http://localhost:8080/authcodeflow in the **App Settings & Details > Callback URL**
- **Github**: Download sample app files
- **Terminal**: Go to sample app's directory and run **npm install**
- Find and open the **.env** file in the app directory
- Copy-paste your **CLIENT_KEY**. and **CLIENT_SECRET**.
- **Terminal**: run **node app.js**. to start the server

## How to use the sample app:

- Go to the index page
- Install the app to your Thinkific site
- An access token is generated and stored
- User is redirect /app where you can test the Thinkific API endpoints

## Thinkific Developer Documentation

### Getting Started
- [Getting started with Thinkific apps](https://developers.thinkific.com/building-apps/#getting-started-with-apps)
- [Building Apps & Integrations](https://developers.thinkific.com/building-apps/)

### Authorization
- [OAuth Authorization](https://developers.thinkific.com/api/authorization/)
- [OpenID Connect](https://developers.thinkific.com/api/openid-connect)
- [Scopes](https://developers.thinkific.com/api/scopes)

### API reference & other features
- [OAuth API](https://developers.thinkific.com/api/oauth/)
- [Admin API](https://developers.thinkific.com/api/api-documentation/)
- [Webhooks API](https://developers.thinkific.com/api/webhooks-api/)
- [Site Scripts API](https://developers.thinkific.com/building-apps/site-scripts/)
- [Theme Extensions](https://developers.thinkific.com/building-apps/theme-extensions/)
