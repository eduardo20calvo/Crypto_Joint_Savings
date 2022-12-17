## Crypto Joint Savings

This project entails creating a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement features for a joint savings account. The features consist of the ability to deposit and withdraw funds from the account. 

# Create a Joint Savings Account Contract in Solidity

To begin a new contract was defined as JointSavings. Within this contract variables were defined; two variables of type "address payable" named accountOne and accountTwo, a variable of type "address public" named lastToWithdraw, and two variables of type "uint public" named lastWithdrawAmount and contractBalance. 

A function was defined as "withdraw" that accepts two arguments: amount of type "uint" and recipient of type "payable address".

A function was defined as "public payable" named deposit. 

A function was defined as "public" named setAccounts that takes two "address payable" arguments named account1 and account2.

Last but not least, a fallback function was added so that the contract can store ether that's sent from outside the deposit function.

# Compile and Deploy Your Contract in the JavaScript VM

The smart contract was compiled and deployed in Javascript VM environment. 

