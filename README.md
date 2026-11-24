<p align="center">
  <a href="https://grom.exchange"><img src="https://raw.githubusercontent.com/grom-exchange/brand-kit/main/logos/grom-mark-nord-bg-256.png" width="96" alt="GROM"></a>
</p>

<h1 align="center">GROM Exchange — docs</h1>

<p align="center">How GROM works, what it supports and where to find official links.</p>

<p align="center">
  <a href="https://grom.exchange"><b>Launch app</b></a> ·
  <a href="#getting-started">Getting started</a> ·
  <a href="#swaps-and-cross-chain-routes">Swaps</a> ·
  <a href="#fees">Fees</a> ·
  <a href="#faq">FAQ</a> ·
  <a href="#official-links">Official links</a>
</p>

---

## What GROM is

GROM is a non-custodial DeFi hub. One interface for:

| Product | What it does | Open |
| --- | --- | --- |
| Swap & bridge | Swap tokens on one network or across networks; GROM compares routes from several aggregators | [Swap](https://grom.exchange/swap) |
| Trade | Perpetual futures from a connected wallet | [Trade](https://grom.exchange/futures) |
| Predictions | Event markets | [Predictions](https://grom.exchange/predict) |
| Stocks | Tokenized stocks and ETFs bought on-chain | [Stocks](https://grom.exchange/stocks) |
| Markets | Live prices, trending DEX tokens, new listings | [Markets](https://grom.exchange/markets) |

You keep custody the whole time: there is no account, no sign-up and no deposit.

## Getting started

1. Open [grom.exchange](https://grom.exchange) and press **Connect wallet**. Browser-extension wallets and WalletConnect are supported; Solana wallets work for Solana routes.
2. Choose a product — for example **Swap**.
3. Pick the token you pay with and the token you want, on any supported network.
4. Review the quote: route, fees, network gas and the minimum you receive.
5. Confirm in your wallet. Only you can sign.

Every coin also has its own page, e.g. [grom.exchange/token/pepe](https://grom.exchange/token/pepe), that opens the swap with that coin selected.

## Swaps and cross-chain routes

- GROM requests quotes from **LI.FI, Velora (ParaSwap), KyberSwap, Squid** and **Jupiter** (Solana) and shows the available route for your pair and amount.
- A cross-chain swap has two stages: the source-chain transaction you sign, and delivery on the destination chain. A submitted transaction is not yet a completed transfer — the route status in the app shows when funds have arrived.
- A configured provider does not guarantee a route for every pair, network or amount. The in-app quote is the reference.

Supported networks include Ethereum, BNB Chain, Base, Arbitrum, Optimism, Polygon, Avalanche, Linea, Solana, Robinhood Chain, HyperEVM, Monad, Plasma and X Layer. Availability per product can differ.

## Fees

- Each quote shows the GROM fee, provider fees, network gas and the expected output **before** you sign.
- Fees differ by route and provider; Solana swaps via Jupiter currently carry no GROM fee.
- The live swap configuration is public: [grom.exchange/api/swap/public-config](https://grom.exchange/api/swap/public-config).

## Safety

- GROM never asks for a seed phrase, private key or password, and never asks you to send funds to "verify" a wallet.
- Check the domain is `grom.exchange` before connecting.
- Read what your wallet asks you to sign: network, token, amount and recipient.
- Crypto assets — especially meme coins — are volatile and can lose most of their value. Nothing in GROM is investment advice.

## FAQ

**Do I need an account or KYC?**
No account is needed on GROM — you connect a wallet and sign. Third-party services and some regions may apply their own checks.

**Where are my funds?**
In your wallet. GROM routes your transaction to the chosen provider; it does not keep a balance for you.

**Why did a cross-chain swap not arrive yet?**
Delivery on the destination chain can take from seconds to several minutes depending on the route. Check the route status in the app and the destination-chain explorer.

**Which wallet should I use?**
Any wallet that supports the network you trade on — browser extensions, mobile wallets through WalletConnect, and Solana wallets for Solana routes.

## Official links

- App: [grom.exchange](https://grom.exchange)
- X: [@GromExchange](https://x.com/GromExchange)
- Telegram: [t.me/Grom_DeFi](https://t.me/Grom_DeFi)
- GitHub: [github.com/grom-exchange](https://github.com/grom-exchange)
- Brand kit: [grom-exchange/brand-kit](https://github.com/grom-exchange/brand-kit)

## Feedback

Spotted a mistake in these docs or a reproducible interface problem? Open an issue with the page, browser, network and steps to reproduce. **Never include a seed phrase, private key or token.** Security issues: see the [security policy](https://github.com/grom-exchange/.github/blob/main/SECURITY.md).
