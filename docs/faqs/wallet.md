---
id: install-wallet 
title: Installing Your Wallet
sidebar_label: Installing Your Wallet
slug: /install-wallet
---

## Polkadot.js
[Polkadot.js](https://polkadot.js.org/extension/) is a web browser wallet extension that manages users’ private keys, 
and it allows the signing of transactions with their accounts. Unlike MetaMask, Polkadot.js does not allow users to create transactions 
with the extension (though you can sign transactions with the extension), it only manages the private keys. 
Transactions must be made from apps, such as the [Polkadot.js Apps](https://polkadot.js.org/apps/#/accounts).
 
In this tutorial, you’ll learn how to set up the Polkadot.js extension and create an account to interact with SkyeKiwi.
 
### Installation
First, [download the Polkadot.js extension](https://polkadot.js.org/extension/). After installing and opening it, you will see this screen:

<img src="https://github.com/dappforce/subsocial-docs/blob/main/static/img/getting-started-1.png?raw=true" width="360" />

Next, we will create an account.

## Creating An Account
***Note:** It is recommended to read the rest of the steps on how to create an account, and then create an account. 
If you click off of the extension during the creation process, it will close and you will have to start over.*

To create an account with the Polkadot.js extension, you need to:
1. Click the + button in the top right corner
2. Click “Create new account”

<img src="https://github.com/dappforce/subsocial-docs/raw/main/static/img/getting-started-2.png" width="360" />

On the next screen, 12 words in order will be shown. These 12 words make up your mnemonic seed phrase, and provide access to your account. 
**Store these, *in the correct order*, somewhere safe** (for more information on storing your seed properly, 
[read the wiki here](https://wiki.polkadot.network/docs/learn-account-generation#storing-your-key-safely)).

1. Create a copy of the 12 words somewhere safe and secure
2. Check the box at the bottom that says “I have saved my mnemonic seed safely.”

***NOTE:** Your seed phrase will grant anyone access to your account, and all funds held in it. 
Losing your seed phrase can prevent you from being able to recover your account. 
If your seed phrase is stolen, the thief will be able to take all of the funds from your account.*

<img src="https://github.com/dappforce/subsocial-docs/raw/main/static/img/getting-started-3.png" width="360" />

On the next page, you can define some settings for your account. 
1. For Network, we recommend leaving it on “Allow use on any chain” 
(*Advanced users seeking more security can create individual accounts for each chain, but this complicates the user experience, and can be confusing.*)
3. Set a descriptive name for the account
4. Create a strong password

<img src="https://github.com/dappforce/subsocial-docs/raw/main/static/img/getting-started-4.png" width="360" />

Congratulations, you now have a Substrate account.