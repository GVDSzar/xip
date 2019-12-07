## Xar hub_3 proposed features

Quick introduction to the features we want to add in the next upgrade hub_3

- [Atomic swaps via Hash Time Locked Contracts](https://github.com/xar-network/xar-network/tree/hub_3_csdt/x/htlc)

https://en.bitcoin.it/wiki/Hash_Time_Locked_Contracts

- [Constant Product Market Maker Model for the uniswap module](https://github.com/xar-network/xar-network/tree/hub_3_csdt/x/coinswap)

https://github.com/runtimeverification/verified-smart-contracts/blob/master/uniswap/x-y-k.pdf

- Snapshotting locally for pruning and truncating historical data. Also allows fast joins without needing to download the full state.

- Auto upgrades for state upgrades without hard forks (like the hub_2 upgrade)

- Support for gateway assets from gateway configured downstream chains (like private chain hubs)

- IBC assets (generated from other Cosmos hubs)
