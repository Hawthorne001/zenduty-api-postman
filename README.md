
# zenduty-api-postman
Zenduty API Postman collections

## How to generate the API Key
1. Login to your Zenduty account. Navigate to your account page from your Zenduty dashboard in the top right corner.
2. Click on the **API Keys** section, and then click on **Create a new API key**.
3. Give a name to your new API key and then click **Create**.
4. Copy the newly generated API key and save it in a safe location(you will not be able to retrieve the API key again).

## How to import Zenduty api postman collection

1. Clone the [zenduty-api-postman project in Github](https://github.com/Zenduty/zenduty-api-postman)
2. Open your Postman app and navigate to the **Collections** section.
3. Navigate to the cloned project in your local machine. Import the **Zenduty API.postman_collection.json** 

## How to add API key to access the Zenduty API

1. Go to **Zenduty API** collection in your Postman app
2. For any API request, add a key value pair and in headers tab where the key will be **Authorization** and value will be **Token {{API key}}**.
