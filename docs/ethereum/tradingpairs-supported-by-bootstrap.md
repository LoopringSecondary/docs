# ERC20 Trading Pairs

The following trading pairs have been enabled by the Loopring's official relay cluster:

- VITE-LRC
- VITE-WETH
- VITE-BAR
- ARP-BAR
- ARP-LRC
- ARP-WETH
- FOO-LRC
- FOO-WETH
- FOO-BAR
- OMG-LRC
- OMG-WETH
- OMG-BAR
- RHOC-LRC
- RHOC-WETH
- RHOC-BAR
- IOST-LRC
- IOST-WETH
- IOST-BAR
- REQ-WETH
- REQ-BAR
- REQ-LRC
- LRC-WETH
- BAR-LRC
- BAR-WETH
- BAT-LRC
- BAT-WETH
- BAT-BAR
- RDN-LRC
- RDN-WETH
- RDN-BAR
- SNT-LRC
- SNT-WETH
- SNT-BAR
- EOS-LRC
- EOS-WETH
- EOS-BAR
- ZRX-LRC
- ZRX-WETH
- ZRX-BAR
- BNT-LRC
- BNT-WETH
- BNT-BAR
- KNC-LRC
- KNC-WETH
- KNC-BAR

You can query the most up-to-date list of trading pairs by using:

```
curl -X POST -H "Content-Type: application/json" -d '{"method":"loopring_getSupportedMarket", "params" : [{}], "id" : 0}' https://bootstrap.loopring.io/rpc/v2
```