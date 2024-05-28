---
description: Initiate deploy requests programmatically via a Hardhat script
---

# Deploy Request (Hardhat)

### Prerequisites

1. [Github connected to Loki](<README (1).md>)
2. [An existing Loki project](getting-started/how-to-create-a-new-project.md)[ connected to a Github repository.](getting-started/how-to-create-a-new-project.md)

### Step 1: Generate an API Key

1. Start in the Dashboard.
2. Click the Projects tab in the side bar.
3. Select the project you want the deploy request to be associated with.
4. Click the API Keys tab in the side bar.
5. Click Generate new token, and follow the steps.
6. Save your API key in a secure location.
7. Save the project ID on the top right of the page to use in the deploy request script.

### Step 2: Execute the Deploy Request

1. Add Loki.code's [deploy request script](https://github.com/LokiCode-Inc/deploy-request-scripts/blob/main/hardhat/hardhat.ts) to your Hardhat project, and follow the direction's in its JSDoc comments.
2. You can also use [Loki.code's Hardhat example project](https://github.com/LokiCode-Inc/deploy-request-hardhat), and follow the direction's in its README file.

### Step 3: Confirm the Deploy Request

1. Once you've successfully sent the deploy request to your project, you can now go back to your project's page on Loki.code's website.
2. Click Deploy in the sidebar.
3. Click on the Deploy Requests tab.
4. Within this tab's content, you now can see all of your deploy requests associated with this project.
5. Click the Review button.
6. Confirm the network to deploy to.
7. Set constructor arguments if needed.
8. Click the Deploy button to deploy your contract. (If you are part of an organization, you can delegate authorization for who makes the final call to deploy the contract.)
