# ChitFund

Chit funds are key financial inclusion tools for millions in India, especially low-budget investors who do not have access to formal institutions like banks and NBFCs. A chit fund is a very traditional and homegrown financial tool that helps subscribers inculcate the habit of saving. India is home to millions of such subscribers who have been doing this for many decades, but on the other hand, the chit fund system is also prone to fraud. With news claiming that 1.2 to 1.4 million of public money is being lost because of various chip fund schemes. More than 350 frauds affecting 15 million families in 17 states were identified, mainly targeting low-income investors by several mutual fund companies.

## How the application work

A user is allowed to create a chit fund and participants can join up to a prescribed limit. Each participant can pay his installments and after all participants are paid, the smart contract selects the winner for the current installment and transfers the money to his wallet. Transfer collection starts against the next installment.
The smart contract is developed in Solidity, compiled by solc and deployed on the Rinkeby network using web3.js. NodeJs is used on the server, ReactJs on the front-end along with NextJs.


## Dependencies

Install these prerequisites to follow along,

- NPM: https://nodejs.org
- Metamask: https://metamask.io/

### Step 1. Clone the project

```
git clone https://github.com/Abhinav/chit-fund.git
```
### Step 2. Install dependencies

```
$ cd chit-fund
$ npm install
```
### Step 3. Configure metamask and select Rinkeby Test Network

### Step 4. Run the Front End Application

```
$ node server.js Visit this URL in your browser: http://localhost:3000
```

