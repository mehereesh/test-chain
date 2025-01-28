1) Clone the repository to your local computer.
2) Install the required node packages using npm installer
  ```
npm install
 ```
3) Run the following command in the terminal to simulate the blockchain using hardhat
```
npx hardhat node
```
4) In another terminal, compile the smart contract using the below command.
```
npx hardhat compile
```
5) Run the contract on the blockchain using following command.
```
npx hardhat run --network localhost scripts/deploy.js
```
6) Start the react project
```
npm start
```
