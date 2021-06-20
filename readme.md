# Awesome XRPL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of XRPL related projects and resources.


## Contents

- [XRPL Explorers](#xrpl-explorers)
- [XRPL DEX](#xrpl-dex)
  - [DEX UI](#dex-ui)
- [ODL Monitoring](#odl-monitoring)
- [PayString](#paystring)
- [Twitter Bots](#twitter-bots)
- [X-address](#x-address)
- [XRPL Developer Tools](#xrpl-developer-tools)


## Conventions

The XRPL is a decentralized, immutable, censorship-resistant, distributed-ledger. It is also near instant, and the dameon itself is capable of websockets.

Most projects include an active view of current transactions occuring on the network.

Here are some things to know:

- 💫 = Shows live transactions
- <kbd>M</kbd><kbd>T</kbd><kbd>D</kbd> = Multi-environment, Main, Test, Dev networks are supported.


### XRPL Explorers

- [Bithomp](https://bithomp.com) [<kbd>M</kbd>](https://bithomp.com)[<kbd>T</kbd>](https://test.bithomp.com)
- [XRPL.org Explorer](https://livenet.xrpl.org) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org)[<kbd>T</kbd>](https://testnet.xrpl.org)[<kbd>D</kbd>](https://devnet.xrpl.org)
- [XRPScan](https://xrpscan.com) 💫

### XRPL DEX

Stuff related to the built-in [XRPL DEX](https://xrpl.org/decentralized-exchange.html)

#### DEX UI

User Interfaces to the DEX

- [Sologenic DEX](https://sologenic.org) The Decentralized Exchange UI from Sologenic
- [XRP Tookit](https://www.xrptoolkit.com) This tool lets you configure different aspects of any XRPL Wallet/Account. There's also a built-in trading UI.


#### ODL Monitoring

Monitors inter-exchange XRP flows. [ODL is a product offered through RippleNet.](https://ripple.com/ripplenet/on-demand-liquidity/)

- [XRPL ODL Rosetta](https://threexrp.dev) 💫 XRPL ROSETTA monitors movements of XRP between exchanges by listening to the XRPL, it then classifies and buckets the exchange. Naturally ODL traffic will float to the top the longer the tool runs. However active ODL corridors tend to show up pretty fast, simply look for a destination tag with a large count.

### ODL Miscelaneous

- [ODL Patent via USPTO.report](https://uspto.report/patent/grant/10,902,416)


### PayString

Relating to [PayString][#paystring.org]

### X-address

A format that "packs" a destination tag into the address. A classic address is an account on XRPL, with an optional tag. _[via](https://xrpl.org/accounts.html#addresses)_
[See XRPL.org Accounts](https://xrpl.org/accounts.html#addresses)

- [X-address Info](https://xrpaddress.info) Everything you wanted to know about X-address format.


### XRPL Developer Tools

#### [XRPL.org Developer Tools](https://xrpl.org/dev-tools.html)

Developer tools for working with the XRPL Ledger


### Twitter Bots

Twitter bots that crunch numbers daily.

- [Liquidity Index Bot](https://mobile.twitter.com/liquidityb) Posts the current snapshot of the Liquidity Index. The index was invented by [@tenitoshi](https://mobile.twitter.com/tenitoshi), and the bot is maintained by [@CinnappleFun](https://mobile.twitter.com/CinnappleFun)
- [xrp1ntel](https://mobile.twitter.com/xrp1ntel) - XRP Intelligence - By [@devnullprod](https://twitter.com/devnullprod)
- [XRP Updates Bot](https://mobile.twitter.com/OdlBot) Tweets XRP ODL stats twice/day (8am/8pm ET), price action updates every 4hr (and when support/resistance met) and news as it happens. Created by [@xrpartisan](https://twitter.com/xrpartisan)



## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.






[#paystring.org]: https://paystring.org "The Unviersal Payment Pointer"
