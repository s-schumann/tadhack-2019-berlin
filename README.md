# tadhack-2019-berlin

## 1. Have Node-RED available

In our case we deployed it to [Heroku](https://www.heroku.com):

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## 2. Set up logging

- We are using mongodb3 for logging
- Add mlab MongoDB to Heroku and install the mongodb3 module into the Node-RED palette

## 3. Set the relevant env vars

- **APIDAZE_DID**: DID configured at APIdaze that links to the `/apidazecall` URL on Node-RED
- **APIDAZE_KEY**: Key for the Apidaze app
- **APIDAZE_SECRET**: Secret for the Apidaze app
- *APP_NAME*: set automatically on initialization
- *MONGODB_URI*: set automatically when adding mLab
- *NPM_CONFIG_PRODUCTION*: set automatically on initialization
- **SIMWOOD_CID**: Customer ID you receive from Simwood via E-mail
- **SIMWOOD_KEY**: API Key you receive from Simwood via E-mail
- **SIMWOOD_SECRET**: Secret you receive from Simwood via E-mail

## 4. Import the flows

- Import the flows from the `flows.json` file.
