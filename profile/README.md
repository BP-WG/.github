Libraries and software for creating applications with bitcoin protocol.

Main projects:
- bitcoin consensus-level data types and structures (transactions, blocks etc)[^1];
- client-side-valdiation with bitcoin ([deterministic bitcoin commitments][dbc] and [signle-use-seal][seals]);
- wallet-related libraries in [`descriptor-wallet`](/BP-WG/descriptor-wallet) repo;
- [BP Node][node]: efficient indexing bitcoin node written in rust (electum server replacement);
- StingerJet: WIP on a languague for better wallet descriptors.

[^1]: At present time [`rust-bitcoin`](/rust-bitcoin/rust-bitcoin) is used as a consensus library; 
however a more modern and efficient re-implementation is WIP happening in [`bp`](/BP-WG/bp) repo.

[dbc]: https://github.com/BP-WG/bp-core/tree/master/dbc
[seals]: https://github.com/BP-WG/bp-core/tree/master/seals
