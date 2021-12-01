# React-moralis examples

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Quick start

1. Ensure you have a moralis account https://moralis.io
1. Install dependencies via `yarn install` (or `npm install`)
1. Copy `.env.example` to `.env` and add your keys:

   ```sh
   # Your appId
   REACT_APP_MORALIS_APP_ID="xxx"

   # Your serverUrl
   REACT_APP_MORALIS_SERVER_URL="xxx"
   ```

1. Start the app with `yarn start` (or `npm run start`)

## Deploy via github actions

1. Ensure you have a moralis account https://moralis.io
1. `mv .github/workflows/moralis.yml.example .github/workflows/moralis.yml`
1. Update the details for:
   - REACT_APP_MORALIS_APP_ID
   - REACT_APP_MORALIS_SERVER_URL
   - moralisSubdomain
1. Add the following secrets to your github repo in the github interface ( Settings > Secrets). You can find the information in your moralis account when you click on view details on the server you are using in your account.
   - MORALISAPIKEY
   - MORALISAPISECRET
