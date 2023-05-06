---
cover: ../.gitbook/assets/IMG_0049.jpeg
coverY: -28
---

# Comparison.

### Backpack and xNFT's.

Let me preface this with saying - I love [Backpack](https://www.backpack.app/) and [Armani](https://twitter.com/armaniferrante). Both of our projects are dedicated to growing the pie, through building beautiful UX for decentralization.&#x20;

Backpack/xNFT's may seem similar to Dappnet, but have pretty different realisations of their direction.

Dappnet is directed towards creating a bulletproof platform for all types of media. Censorship-resistant dapps, but also websites, news, and datasets.&#x20;

Backpack is honing in on building dapps and a great wallet for users.&#x20;

In terms of **technical differences**:

* xNFT's are hosted on Arweave, and cached by the CDN. Backpack must run a CDN, kind of like how Infura runs nodes for Metamask.&#x20;
* Dappnet apps are hosted by IPFS nodes (and soon BitTorrent). IPFS/BitTorrent employ swarm-based P2P solutions to serving content, where each node can also contribute their resources. The scalability of the two designs is to be considered.

### ZeroNet.

[ZeroNet](https://en.wikipedia.org/wiki/ZeroNet) is a custom browser that accesses websites via Bitcoin public keys, and downloads them over BitTorrent.&#x20;

In terms of their approach, there are two main drawbacks:

* **custom browser** - meaning users have to download a separate browser, which means re-working their existing setup and extensions (web3 wallets).
* **.bit domains** - ZeroNet uses the Namecoin protocol so users can access content via .bit domains. We commend Namecoin as the first protocol to square [Zooko's triangle](https://en.wikipedia.org/wiki/Zooko's\_triangle), though it shows its age. For users, the UX for updating .eth domains is simpler, using more common payment methods (ETH, USD), and widely integrated in the crypto ecosystem.

### Prior works.

Finally, I would like to list some prior works. While Dappnet was developed independently, I grew up playing with I2P/Freenet/Tor, and they had a big influence on these ideas. There are a few other approaches which are worth looking into, to compare against what we're doing.

* [**Federalist**](https://github.com/publiusfederalist/federalist). See this [great thread](https://news.ycombinator.com/item?id=29513547) on various approaches on HN.
* [**Beaker Browser**](https://github.com/beakerbrowser/beaker).
* [Freenet](https://en.wikipedia.org/wiki/Freenet), [I2P](https://geti2p.net/en/) and [Tor](https://en.wikipedia.org/wiki/Tor\_\(network\)).







