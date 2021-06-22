# Awesome XRPL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of XRPL related projects and resources.

# Contents

Use the outline navigation from the top left:

<img width="237" alt="image" src="https://user-images.githubusercontent.com/134478/122861901-d3f00b80-d2e5-11eb-84e5-d8f9de0b5529.png">


# ✨ [XRPL.org](https://xrpl.org) ✨

[XRPL.org](https://xrpl.org) is a great resource for anyone wanting to learn more about the XRPL and how it works.

Feel free to [explore](https://xrpl.org/get-started.html) [there](https://xrpl.org/overview.html) [first](https://xrpl.org/introduction.html)!
([It's](https://xrpl.org/send-a-multi-signed-transaction.html) [really](https://xrpl.org/references.html) [good](https://xrpl.org/technical-faq.html) 😳)

To come back here anytime you want – just remember the [**xrpl.rocks**](https://xrpl.rocks)! 🎉

# Conventions

The XRPL is a decentralized, immutable, censorship-resistant, distributed-ledger. It is also near instant, and the daemon itself is capable of websockets.

Most projects include an active view of current transactions occuring on the network.

Here are some things to know:

- 💫 = Shows live transactions
- <kbd>M</kbd><kbd>T</kbd><kbd>D</kbd> = Multi-environment, Main, Test, Dev networks are supported.


# XRPL Explorers

- [Bithomp](https://bithomp.com) [<kbd>M</kbd>](https://bithomp.com)[<kbd>T</kbd>](https://test.bithomp.com) A block explorer. Tailored for viewing accounts, you can log in with a hardware wallet.
- [Ledger.Exposed](https://ledger.exposed) -  Live stats and insights in the XRP distribution, ownership, escrows and the flow of funds. 
  - src: [frontend](https://github.com/WietseWind/XRP-Stats-Frontend) / [backend](https://github.com/WietseWind/XRP-Ledger-to-MongoDB)
- [xrpintel](https://xrpintel.com) 💫 - Live transaction explorer with JSONPath
  filtering.
  - 🔗 [Dossier of gateways](https://xrpintel.com/gateways) and their issued tokens as KYG or "Know Your Gateway".
- [XRPL.org Explorer](https://livenet.xrpl.org) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org)[<kbd>T</kbd>](https://testnet.xrpl.org)[<kbd>D</kbd>](https://devnet.xrpl.org)
- [XRPScan](https://xrpscan.com) 💫 Block explorer with a [public API](https://docs.xrpscan.com/)
  - 🔗 [Validators](https://xrpscan.com/validators)
  - 🔗 [Amendments](https://xrpscan.com/amendments)
  - 🔗 [Metrics](https://xrpscan.com/metrics)

# XRPL Tokens

- [XUMM.Community Token List](https://xumm.community/tokens) - See all tokens
  issued on the XRPL, as well as issue your own token using the wizard that
  steps you through the process.
- [XRPL.org Tokens](https://livenet.xrpl.org/tokens) - The XRPL.org explorer
  token list.

## Casino Coin (CSC)

- [CasinoCoin.info](https://casinocoin.info/) - Everything you wanted to know
  about CSC. Has quickly grown to a great source for analyzing liquidity
  of the CSC token on the [XRPL DEX][#xrpldex], and all info relating to CSC.
  Several tools relating to liquidity are available. It also breaks down all
  DEX orders relating to CSC.


# XRPL DEX

Related to the built-in [XRPL DEX][#xrpldex]


## DEX UI

User Interfaces to the DEX.

- [Sologenic DEX](https://sologenic.org) The Decentralized Exchange UI from Sologenic
- [XRP Tookit](https://www.xrptoolkit.com) This tool lets you configure different aspects of any XRPL Wallet/Account. There's also a built-in trading UI.

## DEX Visualizer

Tools to visualize trades on the DEX.

[Velocity of Value](https://dex.xrplapps.com/) - The DEX tool of the XRPLApps Suite

# XRPL Validators

- [XRPL Apps Validator Stats & Ranking](https://stats.xrplapps.com/) - The
  validator stats of the XRPLApps Suite.
- [XRPScan Validator Registry](https://xrpscan.com/validators) 💫 - The XRPScan
  validator registry.
- [XRPL.org Explorer](https://livenet.xrpl.org/network/validators) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org/network/validators)[<kbd>T</kbd>](https://testnet.xrpl.org/network/validators)[<kbd>D</kbd>](https://devnet.xrpl.org/network/validators)- The
  XRPL.org Explorer's Network Validators.

# ODL

## ODL Monitoring

Monitors inter-exchange XRP flows. [ODL is a product offered through RippleNet.](https://ripple.com/ripplenet/on-demand-liquidity/)

- [Utility Scan](https://utility-scan.com) - Monitors the ODL corridors and
  their trades for producing ODL analytics. Has a public API.
- [XRPL ODL Rosetta](https://threexrp.dev) 💫 [🌐](https://threexrp.dev/app.html) XRPL ROSETTA monitors movements of XRP between exchanges by listening to the XRPL, it then classifies and buckets the exchange. Naturally ODL traffic will float to the top the longer the tool runs. However active ODL corridors tend to show up pretty fast, simply look for a destination tag with a large count.

## ODL Miscelaneous

- [ODL Patent via USPTO.report](https://uspto.report/patent/grant/10,902,416)


# PayString

Relating to [PayString][#paystring.org]

# X-address

A format that "packs" a destination tag into the address. A classic address is an account on XRPL, with an optional tag. [_via_](https://xrpl.org/accounts.html#addresses)

[**X-address Info**](https://xrpaddress.info) Everything you wanted to know about X-address format.

- [xrpl-tagged-address-codec](https://github.com/xrp-community/xrpl-tagged-address-codec) - js package for encoding/decoding X-address format
- [xrpl4j][#xrpl4j] - java library, supports X-address and classic formats
- [xrpl-py][#xrpl-py] - python library, supports X-address and classic formats


# XRPL Developer Tools

- [**XRPL.org Dev Tools**](https://xrpl.org/dev-tools.html)

## The Daemon
- [**rippled**](https://github.com/ripple/rippled/): Ripple peer-to-peer network daemon. **let's rename this to `xrpld`** 😎
- [Rippleserver Google Group](https://groups.google.com/forum/#!forum/ripple-server/) _Still publishes releases!_



### Installing, Configuing and Running the Deamon
- [XRPL.org Installing `rippled`](https://xrpl.org/install-rippled.html)
- [XRPL.org Configuing `rippled`](https://xrpl.org/configure-rippled.html)
- [Node Configurator](https://xrplf.github.io/xrpl-node-configurator/) - This wizard 🪄✨ will walk you through configuring a node!
  If you want to go full custom. The default configuration file is pretty verbose about each option, this walkthrough runs and will
  package you up your validators, your config and even instructions in a zip you generate locally.

#### Connecting To the Daemon
- [XRPL.org WebSocket Tool](https://xrpl.org/websocket-api-tool.html/)
- [XRPL.org Info Tool](https://xrpl.org/xrp-ledger-rpc-tool.html)

#### About the Daemon in a 🐳
- [rippled Docker container (node)](https://github.com/WietseWind/docker-rippled) - [Docker hub](https://hub.docker.com/r/xrptipbot/rippled/)
- [rippled Docker container (validator)](https://github.com/WietseWind/docker-rippled-validator) - [Docker hub](https://hub.docker.com/r/xrptipbot/rippledvalidator/) - [Tutorial](https://medium.com/@WietseWind/how-to-run-a-ripple-validator-digitalocean-7e5fca1c3d77)

## Code

### Libs

- [**xrpl4j**][#xrpl4j] - Java maintained by the [XRPLF][#xrplf]
- [**xrpl-py**][#xrpl-py] - Python maintained by the [XRPLF][#xrplf]
- [**ripple-lib**](https://github.com/ripple/ripple-lib/) - JavaScript / Typescript

⬇️ YMMV with these ⬇️
- [ripple-libpp](https://github.com/ripple/ripple-libpp): C++ Standalone RCL-compatible transaction signing and serialization library
- [ripple-rest](https://github.com/ripple/ripple-rest): A RESTful API for submitting payments and monitoring accounts on the Ripple Network
- [rippled-ws-client](https://www.npmjs.com/package/rippled-ws-client): Lightweight Javascript / nodejs client with health detection and auto-reconnect
- [ripple-lib-ruby](https://github.com/kevinejohn/ripple-lib-rpc-ruby/): Ruby
- [ripple-haskell](https://github.com/singpolyma/ripple-haskell/): Haskell
- [rubblelabs/ripple](https://github.com/rubblelabs/ripple): Go packages to interact with the Ripple protocol
- [RippleKit](https://github.com/xasos/RippleKit): Swift
- [Ripple Go](https://bitbucket.org/dchapes/ripple/): Ripple Go is a set of Go packages and a rippled client.

#### Lib Benchmarks / XRPL Vanity Generators
- [nhartner/xrp-vanity-generator](https://github.com/nhartner/xrp-vanity-address) - Using [xrpl4j][#xrpl4j]
- [WietseWind/xrp-vanity-generator](https://github.com/WietseWind/xrp-vanity-generator) - Using [ripple-lib](https://github.com/ripple/ripple-lib/)


### Connecting a Hardware Wallet
- [ledgerjs](https://github.com/LedgerHQ/ledgerjs) - The SDK for interacting
  with [Ledger][#ledger.com] wallets.
- [XUMM SDK][#xumm-sdk] - The SDK for the [XUMM][#xumm.app] wallet


### Apps
- [Ripplectron](https://github.com/devjin0617/ripplectron): Desktop client for Electron
- [rubblelabs/tx](https://github.com/rubblelabs/tx): Tool for executing transactions on the Ripple network
- [xrpayments.co](https://xrpayments.co): Tool to generate payment request QR (with currency conversion)


#### Code/Other
- [ripple-blobvault](https://github.com/ripple/ripple-blobvault): Server for storing persistent data for Ripple clients
- [rippled-historical-database](https://github.com/ripple/rippled-historical-database): SQL database as a canonical source of historical data in Ripple
- [ripple-data-api](https://github.com/ripple/ripple-data-api) _DEPRECATED_
- [federation-php](https://github.com/ripple-unmaintained/federation-php): Simple PHP federation endpoint with a static JSON dataset **No Maintainer**
- [federation-python](https://github.com/miracle2k/ripple-federation-python): Python module for a simple federation endpoint.
- [Ripple Rails](https://github.com/singpolyma/ripple-rails/)
- [Ripple Gen](https://github.com/CodeShark/RippleGen/)
- [Ripple Checkout](https://github.com/emschwartz/ripple-donate-widget): An embeddable widget for paying with Ripple.



# Twitter Bots

Twitter bots that crunch numbers daily.

- [Liquidity Index Bot](https://twitter.com/liquidityb) Posts the current snapshot of the Liquidity Index. The index was invented by [@tenitoshi](https://mobile.twitter.com/tenitoshi), and the bot is maintained by [@CinnappleFun](https://mobile.twitter.com/CinnappleFun)
- [UtilityScan](https://twitter.com/UtilityScan) - XRP On Demand Liquidity
  Tracker Running an XRPL Validator.  ([UtilityScan.com](https://utility-scan.com))
- [xrp1ntel](https://twitter.com/xrp1ntel) - XRP Intelligence - By [@devnullprod](https://twitter.com/devnullprod)
- [XRP Updates Bot](https://twitter.com/OdlBot) Tweets XRP ODL stats twice/day (8am/8pm ET), price action updates every 4hr (and when support/resistance met) and news as it happens. Created by [@xrpartisan](https://twitter.com/xrpartisan)


# Non-Custodial Wallets

- 🌟[**XUMM**][#xumm.app] 📱 _Pronounced "sum"_ - XUMM is a self-custodial wallet for
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
- [**Ledger**][#ledger.com] Ledger is a hardware wallet manufacturer. Their
  wallets support XRPL, and are supported by most tools, through their 
  [ledgerjs](https://github.com/LedgerHQ/ledgerjs) SDK. [LedgerHQ/app-xrp](https://github.com/LedgerHQ/app-xrp) is the source for the Ledger XRP app.
- [**Trezor**](https://trezor.io) - Trezor wallet, supports XRP.
- [**Paper Account Generator**](https://www.xrpaddress.org/) - A paper account generator entropy is created client-side for generating a seed. By [Wietse][#wietse]

# Interledger

- [**Awesome Interledger**](https://github.com/vhpoet/awesome-ilp) [![awesome-ilp](https://awesome.re/badge.svg)](https://github.com/vhpoet/awesome-ilp)


# Books / Docs / Videos
- [Steven Zeiler's Ripple coding lessons](https://www.youtube.com/user/stevenzeiler/videos?flow=grid&view=0)
- [Build a VueJS WebApp connecting to the Ripple Ledger](https://itnext.io/develop-awesome-webapps-using-vuejs-webpack-bda08ebb691c)



# Misc

Stuff that didn't really fit anywhere else.

- [Awesome Ripple](https://github.com/vhpoet/awesome-ripple) [![awesome-ilp](https://awesome.re/badge.svg)](https://github.com/vhpoet/awesome-ripple) -
  A related awesome list, that uses a legacy name. A lot of items were taken from [`README.md@3d85e95`](https://github.com/vhpoet/awesome-ripple/blob/3d85e95f1614af6a4dca89a03e1f8156670a97ef/README.md)
- [FUD Bingo](https://fudbingo.com) - A bingo card for XRP common misconceptions. Created by [Wietse][#wietse]
- [Jed Balance](https://jed.tequ.dev/) - A stats page for analyzing the
  [`tacostand`](https://bithomp.com/explorer/tacostand) settlement wallet,
  including it's remaining balance and chart of it's staggered release.


# Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.




[#xrplf]: https://github.com/xrplf
[#xrplf.org]: https://xrplf.org
[#xrpldex]: https://xrpl.org/decentralized-exchange.html
[#paystring.org]: https://paystring.org "The Unviersal Payment Pointer"
[#xrpl4j]: https://github.com/XRPLF/xrpl-py
[#xrpl-py]: https://github.com/XRPLF/xrpl-py
[#xrpl-labs]: https://xrpl-labs.com/
[#xumm.app]: https://xumm.app
[#xumm-sdk]: https://xumm.readme.io
[#ledger.com]: https://ledger.com
[#wietse]: https://wietse.com
