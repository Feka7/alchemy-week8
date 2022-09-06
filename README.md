# Casino.sol

A random number casino for use on Ethereum blockchains.

[Click here for a detailed explanation](https://blog.logrocket.com/build-random-number-generator-blockchain/).

# Alchemy exercise

I carried out the exercise trying to change the initial contract as little as possible. In the end, I only added one function `revealHalf` and a boolean variable `revealed` in the `AcceptedBet` struct.

## Workflow

![Workflow](/diagram.jpg)

**Pro:** new mechanism avoid frontrunning attacks with just one boolean variable and a single function call

**Cons:** userB must reveal his number before userA


