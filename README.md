# Betting Ethereum Dapp
The application where users are able to bet money for a number between 1 and 10 and if they’re correct, they win a portion of all the ether money staked after 100 total bets.

## How this works
User can sign in using their Metamask account and bet for the number. When the number of people betting reaches 100, a number will be random generated to pick one lucky number. The total amount of money will be divided according to the money ratio of winners.


![screen shot 2018-08-07 at 12 52 04 pm](https://user-images.githubusercontent.com/35791349/44934245-31cc9680-ad3a-11e8-9ce4-585ef41a162d.png)


## Installation
Install  all the dependencies:
```
npm install
```
Change your database configuration in the `.env` file.

Running the app using http-server
```
http-server dist/
```
 

## Built with
Database: The Ethereum’s ``Testnet Ropsten blockchain``.

Frontend: ``React.js`` with webpack.

Contract’s programing language: ``Solidity 0.4.11``.

Frameworks: ``Truffle`` to deploy, test and compile our contracts.

Development server: ``Node.js`` to use the app while developing locally along with testrpc.

Metamask: To use the final application like the end user would.

## Author

An Q Tran



Thanks to Merunas Grincalaitis and his awesome tutorial on Medium.com that helps me building this Dapp.
