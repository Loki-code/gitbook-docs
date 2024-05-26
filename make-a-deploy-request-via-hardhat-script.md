---
description: Initiate deploy requests programmatically via your Foundry or Hardhat script
---

# Make a Deploy Request via Hardhat Script

### Prerequisite Steps

1. Log in to your Loki.code account.
2. In the dashboard's sidebar, click Projects.
3. Click on the Project you'd like to save your deploy request to. If you don't have a project that's connected to a Github repository, learn how to connect your Github [here](<README (1).md>), and how to create a project connected to a repository to [here](getting-started/how-to-create-a-new-project.md).
4. In the project's sidebar, click API Keys.
5. In the API Keys page, click the Generate new token button.
6. Give your token a name, and then click the Create button.
7. Copy and save your token in a secure location.

### Deploy Request Steps

1. Create a new or open an existing Hardhat project.
   1. Learn how to create a new Hardhat project.
   2. Loki.code Hardhat project example.
2. Construct an HTTP POST request.
   1. Install Axios in your Hardhat project. See [reference](https://axios-http.com/docs/intro).
   2. Set up an Axios HTTP POST request. See [reference](https://axios-http.com/docs/post\_example).
   3. Set the URL to: [https://loki-api2.azurewebsites.net/deployment-requests/save](https://loki-api2.azurewebsites.net/deployment-requests/save) .
   4. Set the body to include the contract data and deploy options. See example.
   5. Set the headers to include your project's API key. See example.
3. Run the script. See [reference](https://axios-http.com/docs/post\_example).

### Aftermath

1. Once you've successfully sent the deploy request, you can now view it within Loki.code's website, set constructor arguments,&#x20;
2. Log in to your Loki.code account.
3. In the dashboard's sidebar, click Projects.
4. Click on the Project that you saved your deploy request to.
5. Click Deploy in the sidebar.
6. Click on the Deploy Requests tab.
7. Within this tab's content, you now can see all of your deploy requests associated with this project.
8. Click the Review button.
9. Confirm the network to deploy to.
10. Set constructor arguments if needed.
11. Click the Deploy button to deploy your contract. (If you are part of an organization, you can delegate authorization for who makes the final call to deploy the contract.)
