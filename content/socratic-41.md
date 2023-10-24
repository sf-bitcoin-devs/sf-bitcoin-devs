+++
title = "Socratic Seminar 41"
date = 2023-09-25
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/), [Bitrefill](https://bitrefill.com/), and [CardCoins](https://cardcoins.co).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers August 26th to September 22nd.

Chain Weather Report
--------------------

- [Mempool](https://www.bitcoin-mempool.info/#BTC,30d,weight)
- [Fees](https://transactionfee.info/charts/fees-package-feerates/)
- [Lightning Network Capacity](https://bitcoinvisuals.com/ln-capacity)
- [Regular TXs & Inscription TXs compared by vsize](https://dune.com/queries/2962509/4908103)
- [BRC-20 mints omitting signature check](https://twitter.com/mononautical/status/1705457795745595570)
- [River reduces the capacity of its lightning node by 48%](https://twitter.com/River_LN/status/1696251824213475724)

News & Announcements
--------------------

- [F2Pool received 20 BTC transaction fee and controversially returns it](https://twitter.com/satofishi/status/1701042302238724512)
- [Ripple acquires Fortress trust](https://www.nobsbitcoin.com/ripple-acquires-fortress-trust/)
- [Donjon Faults SE2 on Coldcard Mk4](https://blog.coinkite.com/donjon-faults-2023/)
- ZeroSync released a [demo](https://zerosync.org/demo/) & [repo](https://github.com/ZeroSync/header_chain) for header chain verification
- [ord v0.9.0 adds support for provenance](https://github.com/ordinals/ord/releases/tag/0.9.0)
- [Machankura announces additive batching feature](https://twitter.com/machankura8333/status/1695827506794754104)
  - [Bitcoin Optech overview of payment batching and scaling impacts](https://bitcoinops.org/en/payment-batching/)
  - [Field Report: Using RBF and Additive Batching](https://bitcoinops.org/en/cardcoins-rbf-batching/)
- [Fedimint v0.1.0 release](https://github.com/fedimint/fedimint/releases/tag/v0.1.0)
- [UTXOracle](https://twitter.com/SteveSimple/status/1704864674431332503)
- [Nunchuk Byzantine - collaborative custody platform for Bitcoin advisors](https://nunchuk.io/blog/byzantine)
- [Latest Tor release supports HiddenServicePOW](https://gitlab.torproject.org/tpo/core/tor/-/commit/8b46d1c6ca20b8c99b979569c7432a97d8fc20a1)
  - [Proposal 327: A First Take at PoW Over Introduction Circuits](https://gitlab.torproject.org/tpo/core/torspec/-/blob/main/proposals/327-pow-over-intro.txt)   

R&D
---

- [libsecp256k1 0.4.0 released](https://github.com/bitcoin-core/secp256k1/blob/master/CHANGELOG.md#040---2023-09-04)
- [Draft implementation of Schnorr adaptor signatures in libsecp256k1-zkp](https://github.com/BlockstreamResearch/secp256k1-zkp/pull/268)
- [Bitcoin-like Script Symbolic Trace (B’SST) released](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-August/021922.html)
- [Compressed transaction proposal](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-August/021924.html)
- [Thoughts on private collaborative custody with FROST](https://gist.github.com/nickfarrow/4be776782bce0c12cca523cbc203fb9d/)
- [Actuarial System To Reduce Interactivity In N-of-N (N > 2) Multiparticipant Offchain Mechanisms](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021942.html)

Bitcoin Core
------------

- [Full Specifications for Taproot Assets published](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021938.html)
- [BIP324 v2 transport connection support merged in a non-exposed way](https://github.com/bitcoin/bitcoin/pull/28196)
- [Auto-CPFP when spending unconfirmed UTXOs](https://github.com/bitcoin/bitcoin/pull/26152)
- [Removing provably unspendable UTXOs from UTXO set](https://github.com/bitcoin/bitcoin/pull/28400)
- [p2p: Diversify automatic outbound connections with respect to networks](https://github.com/bitcoin/bitcoin/pull/27213)
- [p2p: Restrict self-advertisements with privacy networks to avoid fingerprinting](https://github.com/bitcoin/bitcoin/pull/27411)
- [Remove arbitrary restrictions on OP_RETURN by default](https://github.com/bitcoin/bitcoin/pull/28130)

Lightning
--------

- [CLBOSS returns for automated channel management on CLN](https://lists.ozlabs.org/pipermail/c-lightning/2023-September/000239.html)
- [Remotely control your lightning node from your favorite HSM](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004084.html)
- [Practical PTLCs](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004088.html)
- [LDK can pay BOLT12 invoices](https://github.com/lightningdevkit/rust-lightning/pull/2371)
- [LDK watch towers](https://github.com/lightningdevkit/rust-lightning/pull/2337)
- [Scaling LN with simple covenants](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004092.html)
- [SimLN: realistic payment activity generator for lightning](https://github.com/bitcoin-dev-project/sim-ln)
- [DoS: Fake Lightning Channels](https://morehouse.github.io/lightning/fake-channel-dos/)
