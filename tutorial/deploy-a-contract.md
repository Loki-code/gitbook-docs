# Deploy a contract

Loki.code offers an effortless experience for compiling and deploying your contracts through its user interface. The primary advantage of deploying with Loki.code is the ability to meticulously track your deployment history and access Loki.code's Playground, which provides an interface to interact with your contracts post-deployment.

### Prerequisites

1. [Github linked to Loki.code](link-your-github.md)
2. [An existing project](create-a-new-project.md)

### Step 1: Compile a contract

From the Dashboard, click on "Projects" in the left sidebar, and then select the project that contains the contract you wish to deploy.

You will observe three tabs within the left sidebar; ensure that you are in the "Files" tab. On your screen, you should now see the contents of your linked GitHub repository. If you click on a Solidity file within the file tree, the contents of that file will be displayed on the right. Additionally, you should see a "Compile" button in the top right corner.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-02 at 11.49.51 PM.png" alt=""><figcaption></figcaption></figure>

Click on the "Compile" button, and a dialog will appear, allowing you to confirm the compilation of the Solidity file. Click "Compile."

<figure><img src="../.gitbook/assets/Screenshot 2024-06-02 at 11.52.20 PM.png" alt=""><figcaption></figcaption></figure>

Now that your Solidity file has been successfully compiled, let us proceed to deploy it. Click on the "Deploy" tab in the left sidebar, and you will see a user interface similar to the example below.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-03 at 7.23.55 AM.png" alt=""><figcaption></figcaption></figure>

A brief explanation on each tab:

1. **Recent Events**: A summary of the instances found in all other tabs.
2. **Workflow Runs**: Your GitHub workflow executions.
3. **Compilations**: The compilations you have made on Loki.code, from which you can initiate deployments.
4. **Deployments**: Your deployment history and details.
5. **Deploy Requests**: Incoming requests to deploy contracts, sent by yourself or team members via API call.

### Step 2: Deploy the contract

If you have not yet linked your Ethereum wallet to Loki.code, kindly sign into it via the "Connect Wallet" button located at the top right. This step is essential for deploying your contract.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-03 at 6.24.43 AM.png" alt=""><figcaption></figcaption></figure>

To deploy your compiled contract, locate its card within the "Recent Events" tab or the "Compilations" tab.&#x20;

Select the network to which you wish to deploy, input constructor arguments if applicable, and, if all appears satisfactory, click "Deploy" to proceed with deploying your contract.&#x20;

Your wallet provider should then present a confirmation dialog to finalize the deployment. Below, you will find an example using Metamask.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-03 at 6.50.36 AM.png" alt=""><figcaption></figcaption></figure>

To view the details of that deployment, click on the "Deployments" tab. Here, you will find a history of all your successful contract deployments. Each instance also features a "Playground" button at the bottom-right, which navigates you to that contract's Playground—a user interface where you can interact with the deployed contract.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-03 at 6.54.32 AM.png" alt=""><figcaption></figcaption></figure>

Congratulations on successfully deploying your first contract through Loki.code!
