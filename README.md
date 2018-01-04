# README

## Token Registration, Listing, and Mining Support

Loopring's support to any token includes the following three aspects:

1. Token Registration: if a token is regiestered by Loopring Protocol's [TokenRegistry](https://etherscan.io/address/0x974e1e639b5a3c5f44909E1959Ab786AF21B7086#readContract), it can be traded in a decentralized fashion by the [Loopring Protocol](https://etherscan.io/address/0x03E0F73A93993E5101362656Af1162eD80FB54F2). This is the prerequisite for the other two support below.

2. Token Listing: any Loopring enabled wallet can decide whether to list a certain token to display balance and support order managment. The wallet can display a token's balance and support receiving and sending token even if the token has not been registered in step one, but to enable trading, the token must be registered first. 

3. Order Mining: in Loopring's ecosystem, wallets are supposedly decoupled from relays, therefore, for a wallet to be able to manage orders related to a token pair, that token-pair must be supported by the relay a user selected. The relay has an API to expose what token pairs (markets) it supports.



## Tokens Listed by Loopr Wallet

Loopr, as a wallet, will not list all tokens registered in Loopring Protocol's [TokenRegistry](https://etherscan.io/address/0x974e1e639b5a3c5f44909E1959Ab786AF21B7086#readContract). Currently the following ERC 20 tokens are listed:



## How to get my token registered and listed?

Please follow instructions on our [token-listing](https://github.com/Loopring/token-listing) github repository.




### Requirments for Token Registration

The Loopring foundation will try its very best to minimize the requirments for  token registration. Currently these requirements include:

- Your token must be ERC20 compatible.
- Your token's smart contract code must have been verified on https://etherscan.io.

### Submit Registration/Listing Requests

```
ERC20 smart contract address: [ETHERSCAN.IO TOKEN URL]
Website: [URL]
Email: [EMAIL]
Trading Pairs: [SYMBOL]/ETH,[SYMBOL]/LRC
```

We have prepared an example issue for you: [Listing Request - LoopringToken ](https://github.com/Loopring/loopr/issues/83). 

```
ERC20 smart contract address:https://etherscan.io/token/0xEF68e7C694F40c8202821eDF525dE3782458639f
Website: https://loopring.org
Email: foundation@loopring.org
Trading Pairs: LRC/ETH
```

Please format your issue's title in format: **Listing Request - [TOKEN NAME]**.

We will review your token smart contract's source code, and use our best judgement to decide whether or not to list your tokens. Once the team reach a decision, we will send you feedback via the email you provided. This process is currently totally centralized, at least for now.

### What does 'listing' mean?

For tokens we decided to support, we will register them on Ethereum blockchain using our TokenRegistry smart contract. The registration enables the Loopring Protocol smart contract to support trading of such tokens. Once your token is registered, it can be traded by Loopring. (This process is centralized, but since the Loopring Foundation still holds the majority of all LRC tokens, even a decentralized govenance solution is literally centralized.)

To enable your token holders to sell and buy with Loopring protocol, you have to make sure some Loopring-enabled wallet supports your token as well. Loopr is a wallet developped by the Loopring team, it will support all tokens registered in 
TokenRegistry. But for other wallets, you need to reach out to them for support.

### Issue Resolution

Depends on your token smart contract's source code, we may decide to:

1. reject your request.
2. register your token into TokenRegistry smart contract but not to list it on Loopr.io
3. register your token into TokenRegistry smart contract and list it on Loopr.io with seleted trading pairs.

### Trading Pairs
By default, we will add a traiding pair for your token with ETH. But for some tokens, we will also add a traiding pair with LRC. If you would like to add additional traiding pair, please let us know in the issue.

