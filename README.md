# Blockchain Challenge 3

## Background

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Task

1- Create a Joint Savings Account Contract in Solidity

2- Compile and Deploy Your Contract in the JavaScript VM

3- Interact with Your Deployed Smart Contract


## Screenshots

### Code Compiled Successfully

![Screenshot1](Execution_Results/1-code-compiled.PNG)

### Code Deployed Successfully

![Screenshot2](Execution_Results/2-deploy-contract.PNG)

### Dummy Accounts

![Screenshot3](Execution_Results/7-dummy-accounts.PNG)

### Set Accounts

#### Two Dummy Accounts Entered

![Screenshot4](Execution_Results/3a-set-account-function.PNG)

#### Accounts Information 

![Screenshot5](Execution_Results/3b-set-account-function.PNG)

##### NOTE: the WEI amount is `0` in the accounts

### WEI conversion amount used for withdrawal
As WEI in the account is zero therefore, require statement will fail and return the statement

![Screenshot6](Execution_Results/5-wei-value.PNG)

#### Withdrawal Execution Result
![Screenshot7](Execution_Results/4-withdraw.PNG)

#### Withdrawal Amount 
![Screenshot8](Execution_Results/6-funds.PNG)
