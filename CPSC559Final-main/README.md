# CPSC559Final

## Members:
## John Tu 889857462 jttc98@csu.fullerton.edu
## Yu Pan 887346302 yupan@csu.fullerton.edu
## Tianhao Shen 886668276 tianhaoshen@csu.fullerton.edu

### Based on the original program from Scaffold-ETH's Simple NFT example:
### https://github.com/scaffold-eth/scaffold-eth-challenges/tree/challenge-0-simple-nft

## Improvements made to the project:
### Changed the webpage icon
### Added the Midterm and About tabs
#### For Midterm tab, added button to redirect user to CryptoZombies DApp
#### Also added Return button to return user back to the main page in the midterm page
#### For About tab, added group member names and the note giving credit to the original source
### Added the CSUF background image
### Changed newly minted NFTs to be cryptocurrency logos in place of animals

# How to run the program:
## 1. Open the folder called scaffold-eth-challenges-challenge-0-simple-nft.
## 2. While in this current directory, open 3 command prompt windows with cmd in the file explorer.
## 3. In the first command prompt window, type yarn install if needed followed by yarn chain to start the hard-hat backend service.
## 4. In the second command prompt window, type yarn start to access the front-end.
## 5. In the third command prompt window, type yarn deploy to compile all contracts over. (Don't forget to include --reset if needed for each new contract saved.)

# Running CryptoZombies in the App
## 1. Navigate to the midterm folder in the File Explorer window by opening the following in order: packages, react-app, public, midterm.
## 2. Open the command prompt window with cmd while in the midterm folder.
## 3. Type truffle install if this is the first time running Ganache.
## 4. Now type truffle migrate to compile the contracts over to the Ganache blockchain.

# Troubleshooting - Experiencing these issues?
## When opening the NFT application, I am unable to see most of the interface. Only the background is visible.
### A: If you try to access the application via HTML directly, you will only notice the background.
### For the menu interface to be visible, be sure to access the index.html page via http-server.
### Open the three command prompt windows in File Explorer and type the following commands in order:
#### 1. yarn install in the first window
#### 2. yarn chain in the first window
#### 3. yarn start in the second window
#### 4. yarn deploy in the third window
## When I try to press Mint NFT, I am seeing an error message that I am unable to do so.
### A: In the third terminal window, be sure to type "yarn deploy" in order to deploy the contract.
### If this doesn't work, then close the app, and Ctrl-C to abort current tasks on the first and second terminal windows, then restart the app.
## When I click on Create New Zombie in the CryptoZombies Midterm App, nothing happens.
### A: If you are unable to create a new zombie, try one of the two solutions below:
#### 1. After doing truffle migrate, be sure to copy the address from ZombieOwnership and replace the current cryptoZombiesAddress with the new one in the midterm index.html file.
#### 2. Be sure to connect to Ganache if you haven't done so already. (You may need to manually add the Ganache network in the MetaMask network settings.)

# Screenshots for the project
## Main Page (Simple NFTs of Cryptocurrencies)
![Ethereum and Dogecoin](/screenshots/main1.png)
![Bitcoin and Bitcoin Cash](/screenshots/main2.png)
![Litecoin and Shiba Inu](/screenshots/main3.png)
## Midterm App (CryptoZombies)
![Zombie successfully created](/screenshots/midterm1.png)
![Zombie level up](/screenshots/midterm2.png)
![Kitty zombie created](/screenshots/midterm3.png)