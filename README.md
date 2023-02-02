
# Zenduty API Postman Collection

Zenduty maintains a Postman Collection to make building with our API easier. Postman's Collection folders conveniently keep our API requests and elements organized, and are essentially Executable API Descriptions.

To access the Zenduty API via the Postman Collection, follow these steps - 

### Generating the API Key

1. Login to your Zenduty account. Navigate to your account page from the Zenduty dashboard in the top right corner.
  ![](/assets/API_0.png)
2. Click on the API Keys section, and then click on **Create a new API key**.
  
3. Give a name to your new API key and then click **Create**.

4. Copy the newly generated API key and save it in a secure location(you will not be able to retrieve the same API key again).

  ![](/assets/API_1.png)

### Importing the Zenduty API Postman Collection

1. Clone the [zenduty-api-postman](https://github.com/Zenduty/zenduty-api-postman) repository from GitHub.

2. Open your Postman app and navigate to the Collections section.

3. Navigate to the cloned project in your local machine. Import the **Zenduty API.postman_collection.json** file.

  ![](/assets/API_2.png)

### Adding the API Key to access the Zenduty API

1. Click on the Zenduty API collection in your Postman app.

2. Navigate to the **Authorization** tab. In the **Value** section, replace `(Your API key here)` with the API Key copied from Zenduty. The Value section should look like `Token xxxxxxxxxxx`. 

3. Click on **Save**.  

  ![](/assets/API_3.png)


## Example Use-Cases

We can now use the Zenduty API calls to harness the information we want to build upon. <br>
Let's try and get the list of all users on-call right now under a particular team.

1. Expand the **Teams** folder in the Zenduty API collection and select the **List Teams** request.

2. Everything is pre-filled, all you need to do is click on the **Send** button.

3. In the response, we get a list of all teams inside the account. Copy the `"team"` UUID for a team you'd like to check the on-call users for.
![](/assets/API_4.png)

4. Now, expand the **On Call** folder and select the **List Details of On-call** request.

5. Replace the ``team_id`` placeholder in the URL with your chosen team's UUID and click on **Send**.

6. In the responses, we get a list of all the users on-call under different escalation policies in the chosen team. 
![](/assets/API_5.png)

We can build upon this as we require, like for essence, building an email script that fetches this list of people on-call and sends it to the team managers periodically.


