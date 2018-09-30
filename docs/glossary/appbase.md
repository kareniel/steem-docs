## AppBase

**AppBase** enables many components of the [Steem blockchain](/docs/glossary/steem-blockchain.md) to become modular by creating additional non-consensus blockchains as dedicated plugins. It was released as a [softfork](/docs/glossary/softfork.md) within [HF19](https://github.com/steemit/steem/releases/tag/v0.19.10). These plugins can be updated much more rapidly because they do not require replaying the entire blockchain. Practically speaking, **AppBase** enables different cores, or even different computers, to maintain different parts of the Steem blockchain.

This is significantly more efficient than requiring every core, and every computer in the network maintain the entire blockchain. Modularizing the blockchain enables it to take full advantage of the modular nature of computers. This makes [steemd](/docs/glossary/steemd.md) far more efficient and easier to maintain and scale.

**Source**: [Steem Bluepaper](https://steem.io/steem-bluepaper.pdf)