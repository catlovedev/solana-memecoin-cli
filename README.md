# Solana SPL token Cli tool

[🔗doc](https://outsmartchad.github.io/solana-memecoin-cli/)

### Installation 

1. `git clone https://github.com/catlovedev/solana-memecoin-cli.git`
2. `cd solana-memecoin-cli`
3. `npm install`
4. `node help.js `（to see commands or read cli_doc.txt file)

### Prerequisites 🚨

0. we have added a .env.copy file in src/helpers/.env.copy for you to follow and paste your keys to the code (specify the custom jito fee if you need).
1. Add your mainnet wallet secret key, devnet wallet secret key (optional), RPC endpoint(must) and shyft api key(must)
2. change the .env.copy file to .env
3. in src/helpers/config.js, please copy and fill in your .env path.

### Developer CLI:
- Create a new SPL token (on SOL mainnet/devnet) and it will automatically mint to your wallet
- Integrates both **user-defined priority fee and jito tips** that land transactions faster
- Burn a percentage of a token
- Revoke mint and freeze authority of a token
- boost volume of a token by creating buy and sell orders in just **one transaction**
- **Add or Remove liquidity** to a pool
- Swap tokens in a **raydium dex's AMM pool and JUP Swap API**
- Buy or sell a token using SOL using raydium and JUP
- **Buy, Sell, and launch token in pump.fun**
- Check the balance of a token in your wallet

### Trader CLI:
- Optimized Copy Trading Program with auto-buy&sell
- detecting-dips Program with auto-buy&sell
