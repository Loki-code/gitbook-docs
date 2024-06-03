# Interact with & test a contract

Once you have deployed your contract through Loki.code, you may access its Playground. The Playground is a user interface that allows you to interact with your contract by making calls and transactions, and observing its state update in real time.

### Prerequisites

1. [Github linked to Loki.code](link-a-github-repository.md)
2. [An existing project](create-a-new-project.md)
3. [A contract deployed through Loki.code](deploy-a-contract.md)

### Steps

From the Dashboard's left sidebar, click on "Projects," and then select the project that contains the contract you wish to interact with.

On that project's page, click on "Deploy" in the left sidebar. From here, you will see several different tabs to choose from. Click on the "Deployments" tab, which will display the history of all the contracts you have deployed through Loki.code.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-03 at 7.49.21 AM.png" alt=""><figcaption></figcaption></figure>

Locate the deployed contract with which you wish to interact, and click on its respective "Playground" button in the bottom-right corner. You will be directed to your project's Playground, which should resemble the image below.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 1.50.51 AM.png" alt=""><figcaption></figcaption></figure>

The first step is to connect your Ethereum wallet by clicking the "Connect Wallet" button at the top right, allowing you to interact with your contract. Ensure that your wallet is connected to the same network on which the contract was deployed.

On the left side, you will see the public and external functions from your contract, along with some basic information about each one. To call a function, click the "Try it" button, add any necessary arguments, and then click "Transact."

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 2.06.06 AM.png" alt=""><figcaption></figcaption></figure>

After clicking "Transact," your wallet will open a window for you to confirm the transaction.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 2.07.30 AM.png" alt=""><figcaption></figcaption></figure>

As we invoked a write function in this example, it was necessary to pay ether to execute the transaction. However, if you call a read function, you can retrieve data from the blockchain network without incurring any costs.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 2.22.46 AM.png" alt=""><figcaption></figcaption></figure>

In addition to the contract interaction section, the Playground's right-hand side offers JavaScript and TypeScript code snippets implemented via Web3, Ethers, and Viem. These snippets provide developers with quick access to the necessary code for integrating the function into their own applications, thereby expediting the development process.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-04 at 2.26.57 AM.png" alt=""><figcaption></figcaption></figure>

Ultimately, the Playground offers users an effortless means to interact with deployed contracts, whether by calling functions, conducting tests, or integrating the contract into another application.

We have many more features planned for the Playground—stay tuned!
