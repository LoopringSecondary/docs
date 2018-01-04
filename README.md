# README

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

