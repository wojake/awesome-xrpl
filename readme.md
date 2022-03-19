# Awesome XRPL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of XRPL related projects and resources.

# Contents

Use the outline navigation from the top left:

<img width="237" alt="image" src="https://user-images.githubusercontent.com/134478/123027016-bfbe1400-d3a2-11eb-8bc7-a926f665dfdb.png"><img width="237" alt="image" src="https://user-images.githubusercontent.com/134478/122861901-d3f00b80-d2e5-11eb-84e5-d8f9de0b5529.png">



# ✨ [XRPL.org](https://xrpl.org) ✨

[XRPL.org](https://xrpl.org) is a great resource for anyone wanting to learn more about the XRPL and how it works.

Feel free to [explore](https://xrpl.org/get-started.html) [there](https://xrpl.org/overview.html) [first](https://xrpl.org/introduction.html)!
([It's](https://xrpl.org/send-a-multi-signed-transaction.html) [really](https://xrpl.org/references.html) [good](https://xrpl.org/technical-faq.html) 😳)

To come back here anytime you want – just remember the [**xrpl.rocks**](https://xrpl.rocks)! 🎉

# Conventions

The XRPL is a [decentralized](https://xrpl.org/consensus.html), [immutable](https://xrpl.org/modifying-the-ledger.html),
[censorship-resistant](https://xrpl.org/transaction-queue.html), distributed-ledger.
It is also near instant, and the daemon itself is capable of websockets.

Most projects include an active view of current transactions occuring on the network.

Here are some things to know:

- <kbd>M</kbd><kbd>T</kbd><kbd>D</kbd><kbd>H</kbd> = Multi-environment.
  <kbd>M</kbd>ain, <kbd>T</kbd>est, <kbd>D</kbd>ev, <kbd>H</kbd>ooks networks are supported.
- 💫 = Live! Shows real-time transactions on the XRPL _right now_.
- 🪄✨ = Wizard! A tool that provides a wizard so you don't need to be a wiz.
- 🗣️ = Discussion! An active discussion



# XRPL Explorers

- [Bithomp](https://bithomp.com) [<kbd>M</kbd>](https://bithomp.com)[<kbd>T</kbd>](https://test.bithomp.com)[<kbd>H</kbd>](https://hooks.bithomp.com) block explorer. Tailored for viewing accounts, you can log in with a hardware wallet.
- [Ledger Observer](https://observer.xrpldata.com/) - A *visual* exploration of
  an account and \ connections. Originally created by
  [@LedgerExplorer](https://twitter.com/LedgerExplorer). src: [nixer89/ledger-observer](https://github.com/nixer89/ledger-observer)
- [xrpintel](https://xrpintel.com) 💫 - Live transaction explorer with JSONPath
  filtering. [Public API](https://xrpintel.com/api) by [@DevNullProd](https://twitter.com/devnullprod)
  - 🔗 [Dossier of gateways](https://xrpintel.com/gateways) and their issued tokens as KYG or "Know Your Gateway".
  - [Bloc Trac](#app/bloctrac) offers the same JSONPath filtering to trigger alerts
- [XRPLORER](https://xrplorer.com/) - A XRPL explorer focused on forensics and tracing transactions to their acocunts
  and their held XRP and tokens
- [XRPL.org Explorer](https://livenet.xrpl.org) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org)[<kbd>T</kbd>](https://testnet.xrpl.org)[<kbd>D</kbd>](https://devnet.xrpl.org) 
  XRPL.org's explorer src: [ripple/explorer](https://github.com/ripple/explorer)
- [XRPLF Technical Explorer](https://explorer.xrplf.org) 💫 <a name="tech-explorer"></a> [<kbd>M</kbd>](https://explorer.xrplf.org)[<kbd>T</kbd>](https://explorer-testnet.xrplf.org)[<kbd>H</kbd>](https://hooks-testnet-explorer.xrpl-labs.com) *Beta* A *technical* explorer that is for examining the raw transaction data.
  Which can be viewed as structured JSON. This explorer is focused on showing that data, by giving as much space to the data as possible.
  New closed ledgers share the space with pinned ledgers that are opened. You can jump right into a txn, ledger or account 
  by clicking it in the data or by providing it as a path, e.g., `https://explorer.xrplf.org/{whatever}`
- [XRPScan](https://xrpscan.com) 💫 Block explorer with a [public API](https://docs.xrpscan.com/)
  - 🔗 [Validators](https://xrpscan.com/validators)
  - 🔗 [Amendments](https://xrpscan.com/amendments)
  - 🔗 [Metrics](https://xrpscan.com/metrics)

# XRPL Tokens

> _colloquially referred to as "Tokens", formerly known as "IOU"_

All [( issued currencies || tokens )](https://xrpl.org/issued-currencies-overview.html) are interoperable by default using the [built-in DEX](#xrpl-dex).

## Token Explorers

- [XUMM.Community Token List](https://xumm.community/tokens) - 🪄✨ <kbd>M</kbd><kbd>T</kbd> See all tokens
  issued on the XRPL, as well as issue your own token using the wizard that
  steps you through the process.
- [XRPL.org Tokens](https://livenet.xrpl.org/tokens) - The XRPL.org explorer
  token list.
- [OnTheDEX.live](https://onthedex.live) 💫 - Live token data for all XRP Ledger tokens. View price charts, block explorers, volume, market cap and other metrics for free. By           [@ForexCadet](https://twitter.com/ForexCadet).

We recently had a great amount of interest in issuing tokens through tools and services, like [XUMM.community](https://xumm.community)'s token issuer and now xApp 
through the [XUMM Wallet](https://xumm.app).

One resource made by a community member, ([@gadget78](https://twitter.com/gadget78)) is a spreadsheet of tokens that contain a lot of useful information, and a credit-like rating.

Some basic things that are desirable, which also align with requirements [for being listed within XUMM.app](https://support.xumm.app/hc/en-us/articles/4405548600466-How-do-I-get-an-issued-token-listed-in-XUMM-display-name-icon-), and are also listed at the end of [XUMM.Community Token Creator xApp](https://xumm.app/detect/xapp:nixer.tokencreate) are: 

- Issuing account is "blackholed" ([the root key is removed](https://xrpl.org/disable-master-key-pair.html))
- There's a known team (non-anoymous developers) behind the project

### XRPL Token Ratings

- [Gadget78's Spreadsheet](https://gadget78.co.uk) - A spreadsheet that started as a list of tokens. Now offers much more, including a rating and information not available directly through the XRPL; meticulously gathered and put together through Gadget78, and the twitter community of researchers that provide them information.
- [XRPLF's self-assesstment](https://foundation.xrpl.org/token-assessment-framework/browse-token-self-assessments/) - A self-assesstment framework that consists of tokens' data, it is information that the issuer has written themselves.

# XRPL DEX

Related to the built-in [DEX][#xrpldex]. 

> 💡 The DEX unlocks [auto-bridging](https://xrpl.org/autobridging.html), and [path finding](https://xrpl.org/paths.html).

## DEX UI

User Interfaces to the DEX. All transactions are signed by your [non-custodial wallet](#walletsnon-custodial).

- [Sologenic DEX](https://sologenic.org) 🪄✨ <a name="dex-ui/sologenic.org"></a> The Decentralized Exchange UI from Sologenic.
  It's flexible and allows the user to choose any asset in their wallet on either side of the trade.
  This is a hallmark of the XRPL DEX, you could create an offer for any assets you have [Trustlined](https://xrpl.org/trust-lines-and-issuing.html).
  The wizard walks you through a first time use, and has more advanced options in trading and creating your transaction.
- [XRP Tookit](https://www.xrptoolkit.com) 🪄✨ [<kbd>M</kbd>](https://xrptoolkit.com)[<kbd>T</kbd>](https://test.xrptoolkit.com)
  The wizard makes it easy for *anyone* who's never sent an XRP transaction to do their first one, using your wallet to sign!
  This tool lets you configure different aspects of any XRPL Wallet/Account. There's also a built-in trading UI.
- [XDEX](https://xdex.com) - XDEX provides clean and informative DEX-related information, it presents market data like no other interface.

## DEX Explorer

- [Gatehub Markets](https://gatehub.net/markets/) - Gatehub is a gateway and issuer of digital assets like 
  Bitcoin, ETH, which are then traded on the DEX. This explorer is for their issuances.
  [Gatehub](https://gatehub.net) is also a custodial wallet, as it is a DEX; you're free to trade in their assets without
  needing to create a gatehub account.

## DEX Visualizer

Tools to visualize trades on the DEX.

- [**Velocity of Value**](https://dex.xrplapps.com/) 💫 - The DEX tool of the XRPLApps Suite, focuses on visualizing non-XRP movements as `value per second`.
  _First-Time Use recommendation: dimming the "inactive" assets, and collapsing "unclassified"._

## DEX Dev Tools

XRPL Dev Tools pertaining to the [DEX](#xrpl-dex).

- [dexter](https://github.com/hammertoe/dexter) - A tool for creating orders on the XRPL DEX.
  Created by [@hammertoe](https://twitter.com/hammertoe) during the Ripple Innovate hackathon. 
  Uses [`xrpl-py`][#xrpl-py]
- [Sologenic XRPL Trading Data](https://github.com/sologenic/xrpl-trading-data/) - Sologenic.org has a public API for accessing DEX trading data. 
  This is its' documentation.

_See also [XRPL Developer Tools](#xrpl-developer-tools)._

# XRPL Validators

Each of these explorers show all validators for the network.

- [XRPL Apps Validator Stats & Ranking](https://stats.xrplapps.com/) - The
  validator stats of the XRPLApps Suite.
- [XRPScan Validator Registry](https://xrpscan.com/validators) 💫 - The XRPScan
  validator registry.
- [XRPL.org Explorer](https://livenet.xrpl.org/network/validators) 💫 [<kbd>M</kbd>](https://livenet.xrpl.org/network/validators)[<kbd>T</kbd>](https://testnet.xrpl.org/network/validators)[<kbd>D</kbd>](https://devnet.xrpl.org/network/validators)- The
  XRPL.org Explorer's Network Validators.
- [OtterServices' Validator Guide](https://github.com/OtterServices/RippledValidatorGuide/) Explains from start to finish if you're not even running a node.

# ODL
[**O**n **D**emand **L**iquidity is a product offered through RippleNet.](https://ripple.com/ripplenet/on-demand-liquidity/).
RippleNet's ODL customers may use XRP on the XRPL to bridge currencies in one use case.

## ODL Explorer

- [XRPL ODL Rosetta](https://threexrp.dev) 💫 [🌐](https://threexrp.dev/app.html) monitors movements of XRP between exchanges by listening to the XRPL, 
  it then classifies and buckets the exchange. Exploration of different exchanges are available, currently under active development by [@ShortTheFomo](https://twitter.com/ShortTheFOMO)

## ODL Monitoring

Monitors inter-exchange XRP flows.

- [Utility Scan](https://utility-scan.com) - Monitors the ODL corridors and
  their trades for producing ODL analytics. Has a public API.


## ODL Miscelaneous

- [ODL Patent via USPTO.report](https://uspto.report/patent/grant/10,902,416)



# I want to run a Node 🏗️

I want to run a node and be a participant in the XRPL.

Want to skip ahead? Use the [developer tools](#xrpl-developer-tools) and a [public node](#i-need-a-node-to-connect-to-).

## The Daemon – `rippled`

> a daemon (/ˈdiːmən/ or /ˈdeɪmən/) is a computer program that runs as a background process, rather than being under the direct control of an interactive user

[`rippled`](https://github.com/ripple/rippled/) _This is the core of the XRPL_, it's a peer to peer network daemon.

###### …maybe we rename it `xrpld` 😎

## Installing, Configuring and Running `rippled`
- [XRPL.org Installing `rippled`](https://xrpl.org/install-rippled.html) Install and get the core running, its easy! 
  (Like just install a package or run a container easy.)
- [XRPL.org Configuing `rippled`](https://xrpl.org/configure-rippled.html) Next steps after you get it installed and running.
- [Node Configurator](https://xrplf.github.io/xrpl-node-configurator/) - 🪄✨ This wizard will walk you through configuring a node!
  If you want to go full custom. The [shipped, example configuration file](https://github.com/ripple/rippled/blob/7bd5d51e4e4e76a5547051d30b330739618eddb0/cfg/rippled-example.cfg)
  is pretty verbose about each option, this wizard will
  package you up your validators, your config and even instructions in a zip you generate locally.
- [IANA Registration for `xrpl` service port](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml?search=2459) `2459` registerd with IANA as the peer port protocol. [via](https://xrpl.org/peer-protocol.html#peer-protocol-port)
  
See [XRPL Developer Tools](#xrpl-developer-tools) for connecting to your node or any other node, such as a public one like [XRPLcluster](https://xrplcluster.com).

### `rippled` in a 🐳 Container
- [rippled Docker container (node)](https://github.com/WietseWind/docker-rippled) - [Docker hub](https://hub.docker.com/r/xrptipbot/rippled/)
- [rippled Docker container (validator)](https://github.com/WietseWind/docker-rippled-validator) - [Docker hub](https://hub.docker.com/r/xrptipbot/rippledvalidator/)

### `rippled` on the Raspberry Pi 4

The RPi4 is ARM64 capable and can compile `rippled`, if you'd like to boot up an
[ARM 64-bit OS](https://ubuntu.com/download/raspberry-pi).
The RPi4 @ 8GB meets the [minimum requirements](https://xrpl.org/system-requirements.html#minimum-specifications),
it could meet the [recommended requirements](https://xrpl.org/system-requirements.html#recommended-specifications)
with a bump to its' RAM to 32GB since it also has 1Gbps networking.


- [Running an XRPL Validator on a RPi4](https://write.as/dvilela/running-an-xrpl-validator-on-a-raspberry-pi-4)
  The [author](https://github.com/derkomai) has an installation script available
  [here](https://github.com/derkomai/xrpldRaspberryPi). This methodology can apply to compiling `rippled`
  on AWS Graviton EC2 Instances as well.
  
# I Run a Node 🔧

I run a node and want to be a [good participant](https://xrpl.org/run-rippled-as-a-validator.html#1-understand-the-traits-of-a-good-validator).

If it's public, consider adding it to the [public node list below](#i-need-a-node-to-connect-to-).

## Broadcast Channels

Keep up with new releases and amendment proposals, without the noise.

- [ripple-server mailing list](https://groups.google.com/forum/#!forum/ripple-server/) This email list announces releases, and other info 
  for any [node](https://xrpl.org/rippled-server-modes.html) operator. _Old-school_, but effective for widespread announcements!

# I want to promote my node to validator 🔧

Check out: 
- [OtterServices' Validator Guide](https://github.com/OtterServices/RippledValidatorGuide/) Explains from start to finish if you're not even running a node.
- [XRPL.org Validator Info](https://xrpl.org/run-rippled-as-a-validator.html) The necessary additional steps to promote a node you're already running to a validator.


# I need a node to connect to 🙇

Don't want to setup a node, but want to query the ledger or propagate some signed transactions?

## Public Nodes

[XRPLCluster](https://xrplcluster.com) is a public cluster provided by the [XRPLF][#xrplf.org].

📡 **Connect**

Websocket
```
wss://xrplcluster.com
```

📊 **Metrics**

- [Public Stats](https://ws-stats.com/)
  - [Public Stats API](https://xrpl.ws-stats.com)


Aliases:

- [`xrpl.ws`](https://xrpl.ws) _TLD isn't as stable as .com_, use `xrplcluster.com` instead.

# XRPL Developer Tools

- [XRPL Binary Visualizer](https://richardah.github.io/xrpl-binary-visualizer/) - Decode rippled / XRPL-related hex / JSON / base64.
- [xrp.fans](https://xrp.fans/) _[Source](https://github.com/WietseWind/rippled-ws-client-dashboard)_- Dashboard Debugging & Development for the XRPL
- [XRPL Composer](https://graph.trustline.co) 💫 <kbd>T</kbd> - Create, visualize, and validate complex payment paths on the XRP Ledger

See also [**XRPL.org Dev Tools**](https://xrpl.org/dev-tools.html), the list
below are shortcuts for convenience.

## Connecting to `rippled`
- [XRPL.org WebSocket Tool](https://xrpl.org/websocket-api-tool.html) <kbd>M</kbd><kbd>T</kbd><kbd>D</kbd>- connect
  to a node in the browser and send txns.
- [XRPL.org Info Tool](https://xrpl.org/xrp-ledger-rpc-tool.html) - Get Info
  with a classic address, transaction ID, or ledger index.
- [Transaction Sender](https://xrpl.org/tx-sender.html) 🪄✨ -  This tool sends transactions to the XRP Testnet
  address of your choice so you can test how you monitor and respond to incoming transactions.
- [Testnet Faucet](https://xrpl.org/xrp-testnet-faucet.html) - For funding (and
  creating) a testnet wallet.
- *See also [XRPLF Technical Explorer](#tech-explorer).*

## Libs

- [Libs/Production-Ready](#libs--production-ready)
    - [Libs/YMMV](#libs--ymmv)
    - [Libs/SDK](#libs--sdk)
    - [Libs/Benchmarks](#lib--benchmarks)
      - [XRPL Address Vanity Generators](#xrpl-vanity-generators)
- [Libs/Unverified](#libs--unverified)
- [Libs/Deprecated](#libs--deprecated)

Libraries to connect & interact with the daemon and the network.

### Libs / Production-Ready

Libraries that are current and production-ready.

- [**xrpl.js**][#xrpl.js] - JavaScript / TypeScript _maintained by [XRPLF][#xrplf]_
- [**xrpl4j**][#xrpl4j] Java _maintained by [XRPLF][#xrplf]_
- [**xrpl-py**][#xrpl-py]
  [![xrpl-py Documentation Status](https://readthedocs.org/projects/xrpl-py/badge)](https://xrpl-py.readthedocs.io/)
  Python _maintained by [XRPLF][#xrplf]_

#### Libs/YMMV

**Note**: Your mileage may vary!

<details><summary> Do you use any of these in production? </summary>

If you find any of these to be production-ready, please consider moving it to top 
section in lieu of some integration suite, like [Acid Tests](https://www.acidtests.org/) does for browsers and
targeting web standards.

</details>


- [xrbp](https://github.com/DevNullProd/XRBP) - Ruby :: [rubydoc](https://www.rubydoc.info/gems/xrbp)
- [node-red-contrib-xrpl](https://github.com/xrpinnovations/node-red-contrib-xrpl)
  <a name="code/node-red-contrib-xrpl"></a> - [Node-RED](https://nodered.org) Modules for XRPL
- [xrpl-client](https://www.npmjs.com/package/xrpl-client): Javascript/Typescript nodejs WebSocket client with health detection and auto-reconnect
- [xrpl-accountlib](https://www.npmjs.com/package/xrpl-accountlib): Javascript/Typescript nodejs lib. to sign & derive from Family Seed, Mnemonic & Secret Numbers


### Libs/Benchmarks

#### XRPL Vanity Generators

- [nhartner/xrp-vanity-generator](https://github.com/nhartner/xrp-vanity-address) - Using [xrpl4j][#xrpl4j]
- [WietseWind/xrp-vanity-generator](https://github.com/WietseWind/xrp-vanity-generator) - Using [ripple-keypairs](https://github.com/ripple/ripple-keypairs),
  part of [xrpl.js](https://github.com/XRPLF/xrpl.js)


### Libs/SDK 

Packaged and installable, can be used to interface with an API or
Application.


#### Connecting a Wallet

##### [Ledger][#ledger.com] Wallets

- [ledgerjs](https://github.com/LedgerHQ/ledgerjs) - The SDK for interacting
  with [Ledger][#ledger.com] wallets.


##### [XUMM][#xumm.app] Wallets

- [XUMM SDK JS/TS][#xumm-sdk] - The TypeScript/JavaScript SDK for the [XUMM][#xumm.app] wallet,
  by [XRPL-Labs](https://github.com/XRPL-Labs/)
  - _See also [Xumm Community](#app/xumm-community)_
- [XUMM SDK Python](https://pypi.org/project/xumm-sdk-py/) - The Python version of the XUMM SDK for [XUMM][#xumm.app]
- [XUMM SDK PHP](https://packagist.org/packages/xrpl/xumm-sdk-php) - The PHP version of the XUMM SDK for [XUMM][#xumm.app]
- [XUMM.NET.SDK](https://www.nuget.org/packages/XUMM.NET.SDK) - The .NET/C# version of the XUMM SDK for [XUMM][#xumm.app]
- [xumm4j](https://github.com/francisrosario/xumm4j) - The Java version of the XUMM SDK for [XUMM][#xumm.app] by [francisrosario](https://github.com/francisrosario)


### Libs/Unverified

**Note**: Unverified and not updated (unofficially deprecated)

- [ripple-libpp](https://github.com/ripple/ripple-libpp): C++ Standalone RCL-compatible transaction signing and serialization library
- [ripple-rest](https://github.com/ripple/ripple-rest): A RESTful API for submitting payments and monitoring accounts on the Ripple Network
- [ripple-lib-ruby](https://github.com/kevinejohn/ripple-lib-rpc-ruby/): Ruby
- [ripple-haskell](https://github.com/singpolyma/ripple-haskell/): Haskell
- [RippleKit](https://github.com/xasos/RippleKit): Swift
- [rubblelabs/ripple](https://github.com/rubblelabs/ripple): Go
- [xrpl-rust](https://github.com/sephynox/xrpl-rust): Rust

### Libs/Deprecated

**Note**: Unverified or deprecated libaries. If they're deprecated, an alternative is included

- [federation-php](https://github.com/ripple-unmaintained/federation-php) - _No Maintainer_ - 
  Simple PHP federation endpoint with a static JSON dataset. _No alternative known_


# Code/App
Code repositories that are also applications in their own right.

## Shell
- [rubblelabs/tx](https://github.com/rubblelabs/tx): Tool for executing transactions on the Ripple network

## Desktop
- [Ripplectron](https://github.com/devjin0617/ripplectron): Desktop client for Electron


# Code/IoT

- [XRPL-monitor-ESP32](https://github.com/derkomai/XRPL-monitor-ESP32) - Using an ESP32 (an arduino with wifi),
  and circuit python to communicate with the XRPL.

See also:
- [node-red-contrib-xrpl](#code/node-red-contrib-xrpl)


# Code/Framework

## Code/Framework/Multi-Chain
Frameworks for interacting with multiple chains, including XRPL.

- [CoinClub Framework](https://github.com/QCloud-DevOps/CoinClub_Framework) -  A Python Library for multiple Blockchains.
  Token support for XRP, XLM, FileCoin, Algorand, Cardano, and more.


# Code/Other

Code repositories that didn't fit anywhere else

- [Get GitHub XRPL Tx Types](https://runkit.com/wietsewind/get-gh-xrpl-tx-types) - this runkit page shows how to scrape the [xrpl.org](https://xrpl.org)
  published pages to determine the transaction types and their schema.

## Code/Other/Vanity Generators

See also [XRPL Vanity Generators](#xrpl-vanity-generators)

- [CodeShark/RippleGen](https://github.com/CodeShark/RippleGen/) - C++/Boost over 8 years old, need to test it!

## Code/Other

- [ripple-blobvault](https://github.com/ripple/ripple-blobvault): Server for storing persistent data for Ripple clients
- [rippled-historical-database](https://github.com/ripple/rippled-historical-database): SQL database as a canonical source of historical data in Ripple
- [federation-python](https://github.com/miracle2k/ripple-federation-python): Python module for a simple federation endpoint.
- [Ripple Rails](https://github.com/singpolyma/ripple-rails/)
- [Ripple Checkout](https://github.com/emschwartz/ripple-donate-widget): An embeddable widget for paying with Ripple.
- [ripple-data-api](https://github.com/ripple/ripple-data-api) _Deprecated_


# X-address

A format that "packs" a destination tag into the address - Starts with `X`. 
A classic address - Starts with `r` - is an account on XRPL, with an optional tag. [_via_](https://xrpl.org/accounts.html#addresses)

[**X-address Info**](https://xrpaddress.info) Everything you wanted to know about X-address format.

- [xrpl-tagged-address-codec](https://github.com/xrp-community/xrpl-tagged-address-codec) - js package for encoding/decoding X-address format
- [xrpl.js][#xrpl.js] - JavaScript/TypeScript library, supports X-address and classic formats
- [xrpl4j][#xrpl4j] - Java library, supports X-address and classic formats
- [xrpl-py][#xrpl-py] - Python library, supports X-address and classic formats


# Twitter Bots

Twitter bots that crunch numbers. Updates are frequent and when certain thresholds are met.

- [Bithomp Alerts](https://twitter.com/BithompAlerts) XRP price alerts by [@bithomp](https://twitter.com/bithomp):
  more than 5% within an hour, more than 10% in a day. (XRP/USD XRP/BTC by [@bitstamp](https://twitter.com/bitstamp))
- [Liquidity Index Bot](https://twitter.com/liquidityb) Posts the current snapshot of the Liquidity Index. The index was invented by [@tenitoshi](https://mobile.twitter.com/tenitoshi), and the bot is maintained by CinnappleFun
- [UtilityScan](https://twitter.com/UtilityScan) - XRP On Demand Liquidity
  Tracker Running an XRPL Validator.  ([UtilityScan.com](https://utility-scan.com))
- [**xrp1ntel**](https://twitter.com/xrp1ntel) - XRP Intelligence - By [@devnullprod](https://twitter.com/devnullprod) - 
  tweets interesting and easily-digestable messages of rolling stats of the XRPL. Its' followers, tend to raise the more
  interesting of them to top with retweets/likes.
- [XRP Updates Bot](https://twitter.com/OdlBot) Tweets XRP ODL stats twice/day (8am/8pm ET), price action updates every 4hr (and when support/resistance met) and news as it happens. Created by [@xrpartisan](https://twitter.com/xrpartisan)

## [CasinoCoin](#casino-coin-csc)

- [CasinoCoin Alerts](https://twitter.com/CasinoCoinAlert) CasinoCoin (CSC) price swing alerts: movement of more than 10% within an hour, or more than 15% in a day. By [@ForexCadet](https://twitter.com/ForexCadet).


# Apps

Applications that integrate or involve the XRPL.

## Software as a Service (SaaS)

- [Block Trac](https://blocktr.ac) <a name="app/bloctrac"></a>
  💫 🪄✨ - Constant monitoring of an account on various block chains, including XRPL. 
  JSONPath expressions allow powerful filtering, example filters are provided, or you can use the create new 
  filter wizard. _Formerly known as ZerpTracker._
- [xrpayments.co](https://xrpayments.co): Tool to generate payment request QR (with currency conversion) There's a 
  corresponding 📱 App that requires registration here.
- [XRPhone](https://xrphone.app): Pay merchant invoices over the phone using XRP. [Source](https://github.com/jremi/xrphone)
- [XUMM.community](https://xumm.community/) 🪄✨ <kbd>M</kbd><kbd>T</kbd>
  <a name="app/xumm-community"></a> - Xumm Community is a useful wizard/tool that compliments the 
  XUMM wallet

## Mobile
- [Spend The Bits](https://spendthebits.com/) 📱 App that let's you save and send Bitcoin _instantly_ by leveraging the XRPL
  and [issued currencies](https://xrpl.org/issued-currencies-overview.html).

## Ideas
- [XRPL Ideas (GitHub Discussions)](https://github.com/intelliot/xrpl-ideas/discussions) Forum where you can share XRPL ideas, and read ideas by others.


# Wallets (Non-Custodial)

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
- [**Ledger**][#ledger.com] - Ledger is a hardware wallet manufacturer. Their
  wallets support XRPL, and are supported by most tools, through their 
  [ledgerjs](https://github.com/LedgerHQ/ledgerjs) SDK. [LedgerHQ/app-xrp](https://github.com/LedgerHQ/app-xrp) is the source for the Ledger XRP app.
- [**Solo Wallet**](https://www.sologenic.com/ecosystem/solo-wallet) <a name="non-custodial/solo-wallet"></a> 📱
  Store your cryptocurrencies including SOLO, XRP, and the upcoming Tokenized Assets such as Stocks, ETFs, and commodities all in one decentralized wallet app.
  iOS/Android. [Unverified Source](https://github.com/sologenic/sologenic-expo-wallet)
- [**Trezor**](https://trezor.io) - Trezor wallet, supports XRP.
- [**Paper Account Generator**](https://www.xrpaddress.org/) - A paper account generator entropy is created client-side. By [Wietse][#wietse]
- [**Trustline**](https://trustline.co) 📱 <kbd>T</kbd> - A non-custodial stablecoin wallet for Android and iOS. The app runs on the Trustline Credit Network, which offers stable, fast, low-cost payments. The Aurei (AUR) stablecoin is the first trustless asset on the XRPL besides XRP.


# PayString

[PayString][#paystring.org] is ledger-agnostic and is an easy protocol to adopt for dynamic and authorized wallet responses.

- [payid-lambda](https://github.com/xpring-eng/payid-lambda) An AWS Lambda for serving up a PayString.
- [paystring-cli](https://github.com/PayString/paystring-cli) Query a PayString from the commandline.

# Interledger

- [**Awesome Interledger**](https://github.com/vhpoet/awesome-ilp) [![awesome-ilp](https://awesome.re/badge.svg)](https://github.com/vhpoet/awesome-ilp)


# XRPL Cross Blockchain

XRP is utilized to connect other block chains to the XRPL.
This is an intrinsic property of XRP, since it's a [scarce resource](https://github.com/ripple/rippled/commit/f0e3383856a8923e55b0f10e7822de9031b7159e)
and the native token of the XRPL.


## Cross BlockChain / Sidechains
- 🌟 [A Vision for Federated Sidechains on the XRPL](https://dev.to/ripplexdev/a-vision-for-federated-sidechains-on-the-xrp-ledger-2o7o) 
  🗣️ This dev.to discussion and proposal is around federated sidechains.
  Federated `rippled` clusters allow for proving ideas out in production. 
  Transmission can happen across sidechains to or through the XRPL to other sidechains using [X-addresses](#x-address); 
  One could imagine standing up a private XRPL cluster in order to traverse through the mainnet. 
  One could do pretty much anything thinking of the federator as the gateway to and from a hub of value, 
  the XRPL would further enable the <abbr title="Internet of Value">IoV</abbr>.


## Cross Blockchain / Parallel Networks

These are networks that run in parallel to the XRPL, the XRP input into the network through various ways.

- [Wanchain](https://www.wanchain.org/) - a blockchain with a novel approach to node operation using SMPC
  or [Secure Multi Party Computation](https://www.explorewanchain.org/#/../technology/smpc)
- [Flare Networks](https://flare.xyz) - a blockchain that uses 
  <abbr title="Flare Consensus Protocol">[FCP](https://flare.xyz/flare-consensus-protocol-an-explainer/)</abbr>
  and is due to launch Q2/Q3 2021.
  XRP is collateralized according to the rate provided by the [FTSO](https://flare.xyz/ftso-a-breakdown/),
  [FXRP](https://drive.google.com/file/d/1ftqaiUgU7-57KEFzYQ807h9pwUzsE84Y/view?usp=sharing)
  is one of several assets that will be integrated with 
  [state connectors](https://docs.flare.network/en/state-connector).
  - 🔗 [FXRP Whitepaper](https://drive.google.com/file/d/1ftqaiUgU7-57KEFzYQ807h9pwUzsE84Y/view) 
  - 🔗 [All Whitepapers](https://flare.xyz/whitepapers/)



# Books / Docs / Videos
- [Build a VueJS WebApp connecting to the Ripple Ledger](https://itnext.io/develop-awesome-webapps-using-vuejs-webpack-bda08ebb691c)



# Misc

Stuff that didn't really fit anywhere else.

- [Awesome Ripple](https://github.com/vhpoet/awesome-ripple) - A related awesome list, that uses a legacy name.
  Many items from
  [`README.md@3d85e95`](https://github.com/vhpoet/awesome-ripple/blob/3d85e95f1614af6a4dca89a03e1f8156670a97ef/README.md)
- [FUD Bingo](https://fudbingo.com) - A bingo card for XRP common misconceptions. Created by [Wietse][#wietse]
- [Jed Balance](https://jed.tequ.dev/) - A stats page for analyzing the
  [`tacostand`](https://bithomp.com/explorer/tacostand) settlement wallet,
  including its' remaining balance and chart of its' staggered release.


# Contribute
Want to add or remove something from the awesome list?    
We welcome contributors with open arms, read the [contribution guidelines](contributing.md) first.




[#xrplf]: https://github.com/xrplf
[#xrplf.org]: https://foundation.xrpl.org
[#xrpldex]: https://xrpl.org/decentralized-exchange.html
[#paystring.org]: https://paystring.org "The Unviersal Payment Pointer"
[#xrpl4j]: https://github.com/XRPLF/xrpl-py
[#xrpl-py]: https://github.com/XRPLF/xrpl-py
[#xrpl.js]: https://github.com/XRPLF/xrpl.js
[#xrpl-labs]: https://xrpl-labs.com/
[#xumm.app]: https://xumm.app
[#xumm-sdk]: https://github.com/XRPL-Labs/XUMM-SDK
[#ledger.com]: https://ledger.com
[#wietse]: https://wietse.com
