---
description: >-
  Initiate and manage contract deployments on Loki.code directly from your
  existing development environment, all while enjoying access to team approvals
  and an extensive suite of DevOps tools.
---

# Make a Deploy Request

### What is a Deploy Request?

By connecting your GitHub account to Loki.code, you gain access to our platform's comprehensive suite of DevOps tools, including deployment history, contract playground, and team deployment approvals, each time you make a contract deployment.

For most developers, it is more convenient to use Loki.code in conjunction with their existing development environment, such as Hardhat or Foundry. This is where deploy requests come into play. Deploy requests allow you to initiate a deployment on Loki.code from your existing development environment and enable teams to delineate the roles of developers who initiate deployments and authorized individuals who approve those deployments (for instance, on the mainnet).

By incorporating one of our deploy request scripts into your project, you can send deploy requests for your contract to one of your projects on Loki.code. From there, you or an authorized team member can approve the deployment. Once approved, the deployment details will be added to the project's history, and you will have the ability to interact with it in Loki.code's playground.

### Video Demonstration

{% embed url="https://youtu.be/_N7kZL1pe8Q" %}

### Prerequisites

1. [Github linked to Loki.code](link-a-github-repository.md)
2. [An existing project](create-a-new-project.md)

### Step 1: Generate an API Key

1. Start in the dashboard.
2. Click the "Projects" tab in the side bar.
3. Select the project you want the deploy request to be associated with.
4. Click the "API Keys" tab in the side bar.
5. Click "Generate new token", and follow the steps.
6. Save your API key in a secure location.
7. Save the project ID on the top right of the page to use in the deploy request script.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 4.57.11 AM.png" alt=""><figcaption><p>Creating a new token interface</p></figcaption></figure>

### Step 2: Execute the Deploy Request

Deploy requests are essentially API calls that transmit your contract data and deployment options to your project on Loki.code. To facilitate this process, you may refer to this [repository](https://github.com/LokiCode-Inc/deploy-request), which includes examples of Hardhat and Foundry projects that implement this in a script.

1. If you already possess a project, click on the appropriate example script link in the README, and copy that file into your project. For instance, this is the [script](https://github.com/LokiCode-Inc/deploy-request/blob/main/hardhat/scripts/deploy-request.ts) for Hardhat.
2. If you do not have a pre-existing project, click on the appropriate example project link and follow the instructions in that project's README file. For instance, this is the [reference project](https://github.com/LokiCode-Inc/deploy-request/tree/main/hardhat) for Hardhat.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 4.59.34 AM.png" alt=""><figcaption><p>A deploy request script in a Hardhat project</p></figcaption></figure>

### Step 3: Confirm the Deploy Request

1. Once you have successfully sent the deploy request to your project, return to your project's page on Loki.code's website.
2. Click on "Deploy" in the sidebar.
3. Select the "Deploy Requests" tab.
4. Within this tab, you will now see all of your deploy requests associated with this project.
5. Click the "Review" button.
6. Confirm the network for deployment.
7. Set constructor arguments if necessary.
8. Click the "Deploy" button to deploy your contract. If you are part of an organization, you may delegate the authorization for the final deployment decision.
9. You can now view the details and history of your deployment in the "Deployments" tab on the same page.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 5.07.41 AM.png" alt=""><figcaption><p>Deploy requests awaiting review</p></figcaption></figure>
