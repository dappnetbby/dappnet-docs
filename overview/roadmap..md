---
cover: ../.gitbook/assets/IMG_9820.jpeg
coverY: 0
---

# Roadmap.

Dappnet is an open-source project, built as a **public good**.

Post-launch, there are a couple of immediate things to focus:

* [Porting Dappnet to Windows](https://github.com/liamzebedee/dappnet/issues/35).
* **Making it work better for dapps**. The gateway resolves .eth to IPFS content. Right now it gets slow on resolving multiple sites at once, as it’s a proof-of-concept in JS. We want to rewrite in Go/Rust for paralellism.
* **Adding BitTorrent support, supporting video streaming**. IPFS is very slow. BitTorrent can provide a better UX than IPFS, as well as potentially being able to stream videos from the P2P network using [webtorrent](https://github.com/webtorrent/webtorrent). We’ve already got a test case of downloading a .eth website from BitTorrent.

And in the grander scheme of things, this is what should exist and I want to build:

* **ZK ENS domains on L2’s**. A cheaper, private naming system which is better than IPNS. [Issue #21](https://github.com/dappnetbby/dappnet-features/issues/21)
* **Integrating an Ethereum light client**. Resolving ENS without dependency on Infura/Cloudflare. [Issue #4](https://github.com/dappnetbby/dappnet-features/issues/4)
* **Snapshot voting for .eth subdomains**. Proposing xyz.tumblr.eth using Snapshot. [Issue #17](https://github.com/dappnetbby/dappnet-features/issues/17)
* **Dynamic content for .eth domains**. Resolving .eth to an IP address. There is no option yet for “dynamic content” in IPFS/BitTorrent websites. This can be built, though for now, it would be very useful for people to be able to configure IP addresses. [Issue #10](https://github.com/dappnetbby/dappnet-features/issues/10)
