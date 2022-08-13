## Js_Aave:

### Overview:
Some scripts written in JS to perform a basic lending/borrowing transaction to `Aave` programmatically:

- A user-specified amount of `ETH` is traded for `WETH`.

- The scripts then interact with `Aave`'s Lending Pool contract to Lend the `WETH` the user specified and borrow `DAI` against it. The amount of DAI to be borrwed is determined using `Chainlink`'s Price Feed oracles.

- The scripts have been tested using a fork of Ethereum mainnet.

### Tech Stack:

- **Blockchain**: `Solidity`, `Chainlink Price Feed`, `Hardhat`.

### Features:
- Trading `ETH` for `WETH`.

- Lending a user-specified amount of `WETH` to `Aave`'s lending pool.

- Borrowing the equivalent amount of `DAI` using `Chainlink`'s Price Feed oracle to determine the price.

### Contact Info:
> Author: Jaffar Totanji

> Email: jaafarti@gmail.com

> Telegram: @KuroHata7