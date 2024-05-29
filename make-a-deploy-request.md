---
description: >-
  Initiate and manage contract deployments on Loki.code from your existing
  development environment, with access to team approvals and comprehensive
  DevOps tools.
---

# Make a Deploy Request

### What is a Deploy Request?

By connecting your GitHub account to Loki.code, you gain access to our platform's full suite of DevOps tools, including deployment history, contract playground, and team deployment approvals, every time you make a contract deployment.

For most developers, it is more convenient to use Loki.code in conjunction with their existing development environment, such as Hardhat or Foundry. This is where deploy requests come into play. Deploy requests allow you to initiate a deployment on Loki.code from your existing development environment and enable teams to separate the roles of developers who initiate deployments and authorized individuals who approve those deployments (for example, on the mainnet).

By incorporating one of our deploy request scripts into your project, you can send deploy requests for your contract to one of your projects on Loki.code. From there, you or an authorized team member can approve the deployment. Once approved, the deployment details will be added to the project's history, and you will have the ability to interact with it in Loki.code's playground.

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

Deploy requests are simply API calls that send your contract data and deployment options to your project on Loki.code. To simplify this process, you can use this [repository](https://github.com/LokiCode-Inc/deploy-request) as a reference, which includes examples of Hardhat and Foundry projects that implement this in a script.

1. If you already have a project, click on the appropriate example script link in the README, and copy that file into your project. For example, this is the [script](https://github.com/LokiCode-Inc/deploy-request/blob/main/hardhat/scripts/deploy-request.ts) for Hardhat.
2. If you don't have a pre-existing project, click on the appropriate example project link and follow the instructions in that project's README file. For example, this is the [reference project](https://github.com/LokiCode-Inc/deploy-request/tree/main/hardhat) for Hardhat.

### Step 3: Confirm the Deploy Request

1. Once you've successfully sent the deploy request to your project, you can now go back to your project's page on Loki.code's website.
2. Click Deploy in the sidebar.
3. Click on the Deploy Requests tab.
4. Within this tab's content, you now can see all of your deploy requests associated with this project.
5. Click the Review button.
6. Confirm the network to deploy to.
7. Set constructor arguments if appropriate.
8. Click the Deploy button to deploy your contract. (If you are part of an organization, you can delegate authorization for who makes the final call to deploy the contract.)
9. You can now view the details and history of your deployement in the same page's Deployments tab.
