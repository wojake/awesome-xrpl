# Awesome XRPL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of XRPL related projects and resources.


## Contents

- [XRPL Explorers](#xrpl-explorers)
- [XRPL Tokens](#xrpl-tokens)
- [XRPL DEX](#xrpl-dex)
  - [DEX UI](#dex-ui)
  - [DEX Visualizer](#dex-visualizer)
- [ODL Monitoring](#odl-monitoring)
- [PayString](#paystring)
- [X-address](#x-address)
- [XRPL Developer Tools](#xrpl-developer-tools)
- [Twitter Bots](#twitter-bots)
- [Non-Custodial Wallets](#non-custodial-wallets)
- [Interledger](#interledger)


## Conventions

The XRPL is a decentralized, immutable, censorship-resistant, distributed-ledger. It is also near instant, and the daemon itself is capable of websockets.

Most projects include an active view of current transactions occuring on the network.

Here are some things to know:

- 💫 = Shows live transactions
- <kbd>M</kbd><kbd>T</kbd><kbd>D</kbd> = Multi-environment, Main, Test, Dev networks are supported.


### XRPL Explorers

- [Bithomp](https://bithomp.com) [<kbd>M</kbd>](https://bithomp.com)[<kbd>T</kbd>](https://test.bithomp.com) A block explorer. Tailored for viewing accounts, you can log in with a hardware wallet.
- [XRPL.org Explorer](https://livenet.xrpl.org) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org)[<kbd>T</kbd>](https://testnet.xrpl.org)[<kbd>D</kbd>](https://devnet.xrpl.org)
- [XRPScan](https://xrpscan.com) 💫

### XRPL Tokens

- [XUMM.Community Token List](https://xumm.community/tokens) - See all tokens
  issued on the XRPL, as well as issue your own token using the wizard that
  steps you through the process.
- [XRPL.org Tokens](https://livenet.xrpl.org/tokens) - The XRPL.org explorer
  token list.

#### Casino Coin (CSC)

- [CasinoCoin.info](https://casinocoin.info/) - Everything you wanted to know
  about CSC. Has quickly grown to a great source for analyzing liquidity
  of the CSC token on the [XRPL DEX][#xrpldex], and all info relating to CSC.
  Several tools relating to liquidity are available. It also breaks down all
  DEX orders relating to CSC.


### XRPL DEX

Related to the built-in [XRPL DEX][#xrpldex]


#### DEX UI

User Interfaces to the DEX.

- [Sologenic DEX](https://sologenic.org) The Decentralized Exchange UI from Sologenic
- [XRP Tookit](https://www.xrptoolkit.com) This tool lets you configure different aspects of any XRPL Wallet/Account. There's also a built-in trading UI.

#### DEX Visualizer

Tools to visualize trades on the DEX.

[XRPLApps DEX](https://dex.xrplapps.com/) - The DEX tool of the XRPLApps Suite

#### ODL Monitoring

Monitors inter-exchange XRP flows. [ODL is a product offered through RippleNet.](https://ripple.com/ripplenet/on-demand-liquidity/)

- [Utility Scan](https://utility-scan.com) - Monitors the ODL corridors and
  their trades for producing ODL analytics. Has a public API.
- [XRPL ODL Rosetta](https://threexrp.dev) 💫 XRPL ROSETTA monitors movements of XRP between exchanges by listening to the XRPL, it then classifies and buckets the exchange. Naturally ODL traffic will float to the top the longer the tool runs. However active ODL corridors tend to show up pretty fast, simply look for a destination tag with a large count.

### ODL Miscelaneous

- [ODL Patent via USPTO.report](https://uspto.report/patent/grant/10,902,416)


### PayString

Relating to [PayString][#paystring.org]

### X-address

A format that "packs" a destination tag into the address. A classic address is an account on XRPL, with an optional tag. _[via](https://xrpl.org/accounts.html#addresses)_

[**X-address Info**](https://xrpaddress.info) Everything you wanted to know about X-address format.

- [xrpl-tagged-address-codec](https://github.com/xrp-community/xrpl-tagged-address-codec) - js package for encoding/decoding X-address format
- [xrpl4j][#xrpl4j] - java library, supports X-address and classic formats
- [xrpl-py][#xrpl-py] - python library, supports X-address and classic formats


### XRPL Developer Tools

- 🌟 [**XRPL.org Dev Tools**](https://xrpl.org/dev-tools.html) - Developer tools for working with the XRPL Ledger


#### Connecting a Hardware Wallet

- [ledgerjs](https://github.com/LedgerHQ/ledgerjs) - The SDK for interacting
  with [Ledger][#ledger.com] wallets.
- [XUMM SDK][#xumm-sdk] - The SDK for the [XUMM][#xumm.app] wallet


### Twitter Bots

Twitter bots that crunch numbers daily.

- [Liquidity Index Bot](https://twitter.com/liquidityb) Posts the current snapshot of the Liquidity Index. The index was invented by [@tenitoshi](https://mobile.twitter.com/tenitoshi), and the bot is maintained by [@CinnappleFun](https://mobile.twitter.com/CinnappleFun)
- [UtilityScan](https://twitter.com/UtilityScan) - XRP On Demand Liquidity
  Tracker Running an XRPL Validator.  ([UtilityScan.com](https://utility-scan.com))
- [xrp1ntel](https://twitter.com/xrp1ntel) - XRP Intelligence - By [@devnullprod](https://twitter.com/devnullprod)
- [XRP Updates Bot](https://twitter.com/OdlBot) Tweets XRP ODL stats twice/day (8am/8pm ET), price action updates every 4hr (and when support/resistance met) and news as it happens. Created by [@xrpartisan](https://twitter.com/xrpartisan)


### Non-Custodial Wallets

- 🌟 [XUMM][#xumm.app] - _Pronounced "sum"_ - XUMM is a self-custodial wallet for
  Android & iOS, built by [XRPL-Labs][#xrpl-labs]. XUMM can hold many accounts,
  and is easy to setup. It strives to deliver the best XRPL experience. It has
  several features not found in any other wallet, including Tangram integration
  and xApps which are vetted by the XRPL-Labs team.
  [XRPL-Labs/XUMM-App](https://github.com/XRPL-Labs/XUMM-App) is the source of
  the react native application.
  The [XUMM SDK][#xumm-sdk] provides functionality for integrating with XUMM
  user's XUMM Wallet. For power users, XUMM will offer a Pro subscription
  service that will enable additional functionality, like push notifications on
  all your wallet's activity.
- [Ledger][#ledger.com] Ledger is a hardware wallet manufacturer. Their
  wallets support XRPL, and are supported by most tools, through their 
  [ledgerjs](https://github.com/LedgerHQ/ledgerjs) SDK. [LedgerHQ/app-xrp](https://github.com/LedgerHQ/app-xrp) is the source for the Ledger XRP app.

### Interledger

- 😎 [awesome-ilp](https://github.com/vhpoet/awesome-ilp) - A curated list of ILP
  resources


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.






[#xrpldex]: https://xrpl.org/decentralized-exchange.html
[#paystring.org]: https://paystring.org "The Unviersal Payment Pointer"
[#xrpl4j]: https://github.com/XRPLF/xrpl-py
[#xrpl-py]: https://github.com/XRPLF/xrpl-py
[#xrpl-labs]: https://xrpl-labs.com/
[#xumm.app]: https://xumm.app
[#xumm-sdk]: https://xumm.readme.io
[#ledger.com]: https://ledger.com
