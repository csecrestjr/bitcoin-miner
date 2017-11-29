# bitcoin-miner
Create a Raspberry Pi Bitcoin Miner
If you don’t know already, Bitcoin is a virtual currency set up in 2009. Bitcoin has grown in reputation over the past few years becoming a very popular as a method to pay for services over the internet. The value has rocketed recently thanks to the huge coverage in the media, for both positive and negative reasons.

#There are two ways to get Bitcoin:

Buying them from an exchange, which is the process of converting local currency to Bitcoin.
Mining them. Mining is the process of verifying transactions in the blockchain.
As the whole of the Bitcoin system is decentralised, every transaction is publically viewable within what is called the blockchain. This blockchain contains every bitcoin exchanged between users so, as there is no central server, it has to be self governed. This is the job of the miners.

#Requirements

#In order to mine Bitcoin, you will need:

A pool account
Bitcoin Wallet
Raspberry Pi
Raspbian image SD card
USB Bitcoin miner
Creating an Account

#There are four things you need to do:

Download a bitcoin wallet
Create a pool account
Set up payment
Set up workers
Download a Bitcoin Wallet
A wallet is a program that sits on your computer and gives you a wallet address, this is a unique string of numbers and letters that you will use to receive bitcoins. Download the client for your computer from https://bitcoin.org/en/download

After installation, you will have to save a file called wallet.dat, keep this file safe, as this contains your unique wallet address within it, including all bitcoins that you will gain. If you lose this file, you cannot recover any bitcoins it contained.

Create a Pool Account
Once you have a wallet address, create a pool account. A pool is a huge collection of other people working towards gaining bitcoins. Due to the complexity of mining a bitcoin, it has become unrealistic to solo mine–the act of processing millions of numbers to solve the block problem. Working as a group, or pool, lets everyone have a chance of earning some Bitcoin. There are many pools around, in this tutorial I’ll be using one called Slush’s pool: http://mining.bitcoin.cz/

Set Up Payment
Once you have created a pool account, you'll need to enter your unique wallet address into the Bitcoin payout address.

Create Worker Account
Next step is to create a worker login account. Within your pool account you have the ability to create something called a worker for each of your bitcoin miners, so you're able to monitor them all separately just in case one should fail. 

Each worker has its own login name and password. Whilst you are on My Account click Register New Worker and give it a name, for example; worker, and a password.

Now you're ready to set your Raspberry Pi mining for Bitcoin.

