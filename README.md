# account_transactions

## General Info

This program implements a console program which meets the following requirements:

Implements class Account with the following fields:

- int id
- Transaction[] transactions

Implements enum StandardAccountOperations with the following enums:

- MONEY_TRANSFER_SEND
- MONEY_TRANSFER_RECEIVE
- WITHDRAW

Implements nested class Transaction with the following fields:

- Account accountFrom
- Account accountTo
- double moneyAmount
- StandardAccountOperations operation

## Technologies

- Java language

## Setup

To run this program, the user must have a JDK 8 compiler instaled in his IDE. 
It can be installed following the steps in the [Open JDK Official Page](https://openjdk.java.net/install/). 
For a detailed step-by-step tutorial on how to use the JDK compiler with Java see [this article](https://docs.oracle.com/javame/config/cdc/cdc-opt-impl/ojmeec/1.1/developer/html/compiling.htm).

## Features

These are features that had to be implemented for this program according to the assignment:

In Account class implement next methods:

public void sendMoneyToAccount(Account accountTo, double moneyAmount) {
	<write your code here>
}

public void withdrawMoney(double moneyAmount) {
	<write your code here>
}

public Transaction[] getTransactions() {
	<write your code here>
}
