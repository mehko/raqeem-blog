---
template: blog-post
title: Introduction to the blockchain
slug: /blockchain-introduction
date: 2021-12-21 15:13
description: "Introduction the halal blockchain principles "
featuredImage: /assets/shubham-dhage-t9rkvi3n0nm-unsplash.jpg
---
# **What is blockchain?**

**A blockchain is a linked list of transactions stored on a network of computers.**

Blockchains are:

1. **Decentralized**: Transactions are on a network of computers (nodes).
2. **Immutable**: Transactions cannot be changed once committed.
3. **Open**: Transactions can be viewed by anyone.

## How blockchains work

Each block has:

1. A list of transactions
2. A hash (a long string of random characters) for the block
3. The previous block’s hash (this is how the blocks are linked)

   ![block-transactions](https://931184.smushcdn.com/2419704/wp-content/uploads/2021/12/block-chains-1024x442.png?lossy=1&strip=1&webp=1 "transactions between blocks")

   Let’s take a look at how a transaction works on the blockchain.

   Let’s imagine we’ve created the Wasabih’s digital coin or token named WASA (the best crypto token I thought it would reach the moon), and suppose Ahmad wants to send Fajar 1 WASA.

   First, both Ahmad and Fajar need crypto wallets. These wallets don’t actually store crypto assets. Instead, they store two keys:

   * A **public key** links to an address that lets you send and receive transactions. Think of it as your email address.
   * A **private key** proves that you own the tokens associated with your public address. Think of it as your email password. Since a private key is hard to remember (it’s a very long string of random numbers), wallets also give you a 12-24 word **seed phrase**. You shouldn’t share your private key or seed phrase with anyone.

   Ahmad can send Fajar **1 WASA** in three steps:

   ![success-transactions-blocks](https://931184.smushcdn.com/2419704/wp-content/uploads/2021/12/block-chains2-1024x321.png?lossy=1&strip=1&webp=1 "successfull tansaction between blocks")

   1. Ahmad tells his wallet: “I want to send 1 WASA from my public address to Fajar’s public address.” Ahmad signs this transaction based on his private key. This signature proves that Ahmad actually owns 1 WASA.
   2. Ahmad’s wallet sends the transaction to nodes on the blockchain. These nodes then verify the transaction using Ahmad’s signature and public key.
   3. A node groups Ahmad’s transaction with other transactions into a block. It then works with other nodes to add the block to the blockchain.

   Fajar will see 1 WASA in his wallet only after all three steps are complete.

   We mentioned above that a block can be added to the blockchain only if other nodes agree. Let’s explore how nodes reach consensus next.

   ## **Consensus mechanisms**

   To process transactions without middlemen, nodes need to be able to reach consensus themselves. They do this through two popular methods:

   ![proof-of-work-vs-stake](https://931184.smushcdn.com/2419704/wp-content/uploads/2021/12/block-chains3-1024x432.png?lossy=1&strip=1&webp=1 "consensus mechanisms")

   **Proof of work**

   1. Nodes called miners compete to solve a math problem using brute force (e.g., rolling a dice thousands of times to get the right number).
   2. The first miner that solves the problem gets to create a block.
   3. Other nodes check if the block is valid. If it is, the miner is rewarded cryptocurrency. If it’s not, the miner wasted their time and energy.
   4. All nodes add the new block to their copy of the blockchain.

   Proof of work uses energy because miners compete to solve math problems by building powerful machines that run 24/7.

   **Proof of stake**

   1. Nodes called validators stake some cryptocurrency. A stake is like saying: “I’ll commit this amount of cryptocurrency to win the right to do this transaction.”
   2. Validators with more stake are more likely (but not guaranteed) to be selected to process the transaction and create a block.
   3. Other validators check if the block is valid. If it is, all participating validators earn a transaction fee. If it’s not, the validator that created the block might lose its stake.
   4. All nodes add the new block to their copy of the blockchain.

   Conclusion: Proof of stake uses less energy than proof of work. Bitcoin uses proof of work, and Ethereum is currently transitioning from proof of work to proof of stake (Ethereum v2.0). One of the reason why Bitcoin raise a lot of doubts regarding the halal aspect and if it is ethical for the environment, but in the same way we can consider all the bank operations system as non-ethical if we consider energy consumption and the impact on the environment.

   ## **Blockchain trilemma**

   When it comes to blockchains, it’s important to remember that there’s usually a trade-off between security, decentralization, and scalability:

   1. **Security:** Ability to defend from bugs and attacks.
   2. **Decentralization:** Ability to support many nodes.
   3. **Scalability:** Ability to support a large volume of transactions.

   For example, consider Ethereum and Solana (two popular cryptocurrencies). As of December 2021:

   * Solana’s average transaction cost is $0.00025 with 1,000 validator nodes.
   * Ethereum’s average transaction cost is $5.2 with 10,000+ validator nodes.

   The more nodes there are, the less likely it is for a network to become compromised. This post isn’t about which cryptocurrency is better – just remember that this trade-off exists.

   Let’s make **WASA** true, the most popular cryptocurrency, to the moon!