# zenduty-api-postman
Zenduty API Postman collections

## How to generate the API Key
1. Login to your Zenduty account click your profile and go to account section.
2. Click the API Keys and then click Create a new API key.
3. Give a name to your new API key and then click create.
4. A popup is shown from where copy that newly generated API key and save it somewhere in your local machine.

## How to import Zenduty api postman collection

1. Go to Zenduty/zenduty-api-postman in Github(https://github.com/Zenduty/zenduty-api-postman).
2. Click Zenduty API.postman_collection.json to view the contents within the GitHub UI.
3. In the top right, right click the Raw button.
4. Click save link as and download the file in your local machine.
5. Open postman app and go to collection section.
6. Click import and import the collection(the json file you just downloaded).

## How to add API key to access your Zenduty API's.

1. Go to Zenduty API in your collection section.
2. Go to any api request and in headers tab add a key value pair where key will be Authorization and value will be token {{API key}}.
