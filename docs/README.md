# How to list my token.

## Token Registration, Listing, and Mining Support

Loopring's support to any token includes the following three aspects:

1. Token Registration: if a token is regiestered by Loopring Protocol's [TokenRegistry](https://etherscan.io/address/0x974e1e639b5a3c5f44909E1959Ab786AF21B7086#readContract), it can be traded in a decentralized fashion by the [Loopring Protocol](https://etherscan.io/address/0x03E0F73A93993E5101362656Af1162eD80FB54F2). This is the prerequisite for the other two support below.

2. Token Listing: any Loopring enabled wallet can decide whether to list a certain token to display balance and support order managment. The wallet can display a token's balance and support receiving and sending token even if the token has not been registered in step one, but to enable trading, the token must be registered first. 

3. Order Mining: in Loopring's ecosystem, wallets are supposedly decoupled from relays, therefore, for a wallet to be able to manage orders related to a token pair, that token-pair must be supported by the relay a user selected. The relay has an API to expose what token pairs (markets) it supports.



## Tokens Listed by Loopr Wallet

Loopr, as a wallet, will not list all tokens registered in Loopring Protocol's [TokenRegistry](https://etherscan.io/address/0x974e1e639b5a3c5f44909E1959Ab786AF21B7086#readContract). Currently only tokens in [ethereum/ERC20/listing.md](https://github.com/Loopring/token-listing/blob/master/ethereum/ERC20/listing.md) are supported.

The official relay's default configuration will also only supprt trading-paires in [ethereum/ERC20/trading_pairs.md](https://github.com/Loopring/token-listing/blob/master/ethereum/ERC20/trading_pairs.md).



### Requirments for Token Registration

The Loopring foundation will try its very best to minimize the requirments for  token registration. Currently these requirements include:

- Your token must be ERC20 or QRC20 compatible.
- For ERC20 token, your token's smart contract code must have been verified by https://etherscan.io.

### Submit Registration/Listing Requests

Please submit an issue for this repository, using [this issue](https://github.com/Loopring/token-listing/issues/1) as an template. Please do NOT submit issues regarding token registration/listing to other project repositories.

