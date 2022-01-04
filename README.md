# Blockchain_Homework_18
Repository for Blockchain Homework - Week 18

## Creating & Running a Proof-of-Authority Blockchain Network

### Prerequesites and Installs

1. Python 
2. Go Ethereum Tools (GETH) v 1.9.7 
    https://geth.ethereum.org
3. Metamask Wallet Browser Extension 
    https://metamask.io/download
    
### Creating Nodes

1. Create empty directories for nodes
2. Create accounts for two (or more) nodes for the network with a separate datadir for each using geth. 
   You will be prompted to provide a password for each of these nodes during creation, afterwhich you will
   be provided a new key for each node. Be sure to save these passwords in a txt file, as well as elsewhere.

![Screen Shot 2021-12-24 at 7 15 08 am](https://user-images.githubusercontent.com/87409108/148058473-4c195962-22a2-42b9-824f-b4ec1b17dfff.png)

3. Run puppeth & follow prompts as in image below. When it comes to choosing a network ID, make sure you choose a number that you haven't used before, and remember this number. We used 321 here.
   
![Screen Shot 2021-12-24 at 7 15 24 am](https://user-images.githubusercontent.com/87409108/148058852-d67ca548-153e-41ee-afff-7921a6b62b9a.png)

4. Continue following the prompts as below, and exit puppeth by using the Cntrl+C keys combination. 
 
![Screen Shot 2022-01-04 at 5 34 21 pm](https://user-images.githubusercontent.com/87409108/148059294-5303e92f-aea0-4bf7-b8b4-468614f19926.png)

5. Initialise nodes

![Screen Shot 2022-01-04 at 5 34 31 pm](https://user-images.githubusercontent.com/87409108/148059548-e8a95930-a139-4e8e-ba9c-1ee50be36692.png)

6. Start mining with node 1. 

![Screen Shot 2022-01-04 at 5 41 14 pm](https://user-images.githubusercontent.com/87409108/148059626-b399e8c7-d7b6-4a0b-982e-001b2b4810fc.png)

7. Start mining with node 2.

![Screen Shot 2022-01-04 at 5 44 05 pm](https://user-images.githubusercontent.com/87409108/148059794-0660c564-8276-4edd-8c3b-471dc8563c95.png)

### Connecting to Metamask Wallet

1. Head to https://metamask.io/download and follow the prompts for your browser.

![Screen Shot 2022-01-04 at 11 38 52 pm](https://user-images.githubusercontent.com/87409108/148060359-788ec045-2246-454b-bf12-d98f3ad2ed24.png)

2. Once installed, create a new network in settings. Name the network the name of your network. In this exercise, we called
   the network tmnet, so we will call it tmnet. Add the chain ID that you noted down before. We used 321. The RPC URL is
   Local Host (http://127.0.0.1:8545). The others can be left blank.
   
 ![Screen Shot 2022-01-04 at 11 46 39 pm](https://user-images.githubusercontent.com/87409108/148061293-50d2bb46-ce97-4e21-b40f-236f5d87a908.png)
 
3. Navicate the menu and import 2 accounts, using the public keys or Json files created when we created our nodes. 

4. We can now send coins from one account to the next on our testnet. Simply click "send" and choose the amount to send.

![Screen Shot 2022-01-04 at 9 07 44 pm](https://user-images.githubusercontent.com/87409108/148061799-747e454c-efc2-441a-a2df-06635af50769.png)

5. Your transaction will then be added to a que to be processed. 

![Screen Shot 2022-01-04 at 9 43 13 pm](https://user-images.githubusercontent.com/87409108/148061918-5f41736e-aad0-4ba0-af92-9ac9bd5ccfb9.png)

6. Congratulations, you have now created a blockchain test net and successfully transferred coins from one account to another.

