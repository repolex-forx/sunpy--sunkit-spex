# Repolex Knowledge Graph of sunpy/sunkit-spex

RDF knowledge graph data for [sunpy/sunkit-spex](https://github.com/sunpy/sunkit-spex), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download sunpy/sunkit-spex
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 92782fb80dffa7c217663e037bc55976aba12f07
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 92782fb80dffa7c217663e037bc55976aba12f07
│           └── chunk-001.nq.gz
├── blob
│   ├── 0124f98a2bf035f75b4d410ff23a3b59457d68ad.nq.gz
│   ├── 014b2b297ad470aaa3d297197bf036d1982891f1.nq.gz
│   ├── 017b02002d0b86d469d64626acda5a9679efbb50.nq.gz
│   ├── 020add015f91c73914d1ae016bc2a894ed6a9d8f.nq.gz
│   ├── 04d7286990d2a5980fcbf80af86e92bd16ce65ed.nq.gz
│   ├── 085be8b7692e8989434e18267606f17d98774ba7.nq.gz
│   ├── 092d85d2366076b52e7873f965b6dabd80443b4d.nq.gz
│   ├── 0cb1b4431ffe9e7976214ec6903114aee8f50944.nq.gz
│   ├── 151a235649a7c224e34f783ef8adfa5a4682c525.nq.gz
│   ├── 1dfe07e8429e26d8371ef13f14beb48b17d29599.nq.gz
│   ├── 1fd2cb2b34dab5c23206ef741824da2723f86ea2.nq.gz
│   ├── 1febea6dce3d451bfc4f72577c82e8ce07c1979d.nq.gz
│   ├── 20b38d534c259eac35629feca4fe5977589daa28.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2140b1c29df0d36a7c367603b000f892cd758e8f.nq.gz
│   ├── 21a5e41430b8683d9a84621447f0b45ffa7b8ddd.nq.gz
│   ├── 2687b33ebe47539d72d835c50389190516681328.nq.gz
│   ├── 276bc84f254d5985ab5cde5920e8b89cc0c58665.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 28559f2b34d999814f77aef762123dee2d624f3f.nq.gz
│   ├── 2935b247f9a1b91930bb14a6e3efff184302de9e.nq.gz
│   ├── 2a1a5c5d54fdccf4b1897d502151b288ff4768fd.nq.gz
│   ├── 2bd936a0b6004b9875cb05ea22072fa9e309f3ce.nq.gz
│   ├── 30d403dd5f465b2b5899559c68561e0d3c2148ea.nq.gz
│   ├── 349686c67fee6401c5b0c15df53d8979e9386cc7.nq.gz
│   ├── 38309e166ce181809c7b34fa0d77b0ffef603171.nq.gz
│   ├── 39cd580c3c18ad4df268a7df2f4fcc5eb310ad11.nq.gz
│   ├── 3bcfbeb2697723d3eccb62cee317325b6ea9953e.nq.gz
│   ├── 3c264d71cf8e0333e7a16d5f1e3b83b0c0bd098c.nq.gz
│   ├── 3cde92de71051d9325124430fda83a28d7b838c1.nq.gz
│   ├── 3d74b99df9209b6f867bb955402c4d1d59e0d8ac.nq.gz
│   ├── 407b66660d75a9a35e40cffaa61ba1a8370118c6.nq.gz
│   ├── 413a097073124f91c757169ef0338d0557e1beea.nq.gz
│   ├── 42acaffb2573ca3559253eac9d3f25c8c8fd4ec9.nq.gz
│   ├── 469d6b61f9922478c5483a80aecfee0f08b403ce.nq.gz
│   ├── 47628ae283e46b0f70bb1b8a34d9b620f151c668.nq.gz
│   ├── 48a342cf7644790ff05b837965d35dfb5a683e39.nq.gz
│   ├── 4a61406aacc757d417a89b513f29a274002ff511.nq.gz
│   ├── 4b509585e49ab3bf877aa54a5196c07881446d12.nq.gz
│   ├── 4ca294746e8727b6e8320361ed5cc3e06c0c9acf.nq.gz
│   ├── 4d5dc8c4f74cda279f01fb9d10ede8c123468715.nq.gz
│   ├── 4de9ccc1a3b504c5c8c6936574004483f94aafd1.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 56c937b9347fc16159478edf1cbbdcfb236fd114.nq.gz
│   ├── 58ca9fbe8b5da79d2121db5ec21614890da17ca8.nq.gz
│   ├── 597f8bc78027a75cb979db0b60586e2d7400efee.nq.gz
│   ├── 5a8cda9a93c98271b5339165dff3724ff0fcf5dc.nq.gz
│   ├── 5c48ccb39ee1c9d016e8752fe0c6afa2821649d0.nq.gz
│   ├── 5dcd282ffcbc6302e7f16b538bb2f60c5d91743d.nq.gz
│   ├── 6161cb173bff9eb45fa8490b5b9e35706fb93df3.nq.gz
│   ├── 64492fdff7ee89d8ecd1255b5be0a1840728f638.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6a765b7fa8aeb81a988f71c154c431fab184f48c.nq.gz
│   ├── 6a92d41caea026c40785ab19731353ebe7fe9a5f.nq.gz
│   ├── 6b42ff36913717958059fc092007cbd1c7aad9a4.nq.gz
│   ├── 6b6965e8620be7b9fd97811da6867203fba44cf0.nq.gz
│   ├── 6ece151a3e9b434dee07712f0fe35eaa0e4ce95f.nq.gz
│   ├── 7062819840f14521cc55994d2f5cc7c0e0294eac.nq.gz
│   ├── 72c50939148918320dc392fa83c090ecb3e2f942.nq.gz
│   ├── 753fc75abc03e87c7dec42c4c58f2c7a93503623.nq.gz
│   ├── 7722b7ec342a201f3d1148c8f391a1e02d742a46.nq.gz
│   ├── 782344050ad9c291e42a231e2665045c82eb1ccf.nq.gz
│   ├── 78edacddb85680fe3bfc318b1786cb62fbaafd6c.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7c6fe25b6f0d997a472d0ca27e065dbe3a74d1f4.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 838b45731c902e27136554667fb12a421858e8d8.nq.gz
│   ├── 84025431fb846a9365080bb11908f186e6910174.nq.gz
│   ├── 8be7f4b48eb391f1e3ea467ca30ee07bb7a159a6.nq.gz
│   ├── 8fa6e758ae67c36b848799b2c65b9a1d99583481.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 95605c8538723f17603d7b204ff9061f9e5c0df6.nq.gz
│   ├── 9631bedd09217fe2ed18b3cd2314b81553319125.nq.gz
│   ├── 979cbe2a1e654f287ce3636fab7ce36978c717e3.nq.gz
│   ├── 988debf51060eb223212788187f60b37891ac768.nq.gz
│   ├── 9c54deba3fe66b42136859531f980b513a1c183c.nq.gz
│   ├── 9f3e65e807f2c9104cd79354d629fe8a5802873b.nq.gz
│   ├── a1878f25cb8b9b1c9294c88a8a9be343323d7bea.nq.gz
│   ├── a18c99700d18b7e8ad98ca23df276d4484ba9f8e.nq.gz
│   ├── a1ff163a42e583f14e34f6ed73394dba1968cddf.nq.gz
│   ├── a2cd3cafefcd31d5fa61302ed4672685910a6ffe.nq.gz
│   ├── a2df6425da945649c0bf802f0b2125e924418aaa.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── a4a519a2a0674063ddfc3abe2b7db2876f59fe03.nq.gz
│   ├── a4df4333a2f21124e27fe20ac1662d48281071df.nq.gz
│   ├── a55a4f8afc2495a5978d8b55e70133ce8b3be68a.nq.gz
│   ├── b178d954bd928f5a43cb19b269f21c2072eff403.nq.gz
│   ├── b1dbf25c11892bebc6459d44896f6764d9f487b8.nq.gz
│   ├── b2197db0a77fdd0e30edc19be9e08658bb934a21.nq.gz
│   ├── b3709e8dfc865a6c2701ddd88d70c8297702eb64.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── b6a6a88e378f33357ddf422e0662723bad01a455.nq.gz
│   ├── b6c19270221eeea7a4ef67a5dbe8f90f89ec00bd.nq.gz
│   ├── b7ea6f12e393c1e0c0bade0bf15b057d32e569a9.nq.gz
│   ├── bbd82769f05049793603676126c6da13a91beb14.nq.gz
│   ├── be6a1082428f79ddb813f3134cab556a41142bf2.nq.gz
│   ├── be8632eb8f1c112fdabb35d60eb24abc717122b2.nq.gz
│   ├── c52d235b8765692a4535dd42b118552f1a16bac3.nq.gz
│   ├── ce24b0e6c5545d3f8b737af961f507620a823ea6.nq.gz
│   ├── cea9cac26553a284883715c1d76651d317fd2b3e.nq.gz
│   ├── cf41a1117196cbfe1fbaf6647b685f85c8d2fb15.nq.gz
│   ├── d04da2b4cc33cb8af8ad3e6449acf5bb64aef441.nq.gz
│   ├── d3349349e5a2bd8dcdb4c98619640650902657c0.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d6a6f070317d943d7715bae8c9306afd772ec496.nq.gz
│   ├── d7a64db6fa95a139a7e9bc32398a486c6e34dcd1.nq.gz
│   ├── d846efdf576cc8e00d2e0abb859d986a392ab882.nq.gz
│   ├── d92bf8483d1a3e40916c2c6fd8d1170094039e37.nq.gz
│   ├── db317ec777bac1e18f7bda0f7599fa8609f34c1a.nq.gz
│   ├── dce9beff10d847d56c6cf617af8569c44248d90e.nq.gz
│   ├── dea5cedb6511a1a65508ea90976d838b836c6ad8.nq.gz
│   ├── e148589db20804f5d42adcafcfc9c7f49397b322.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e39ae34afa7ab6b94c5c46f862fcc1d6440ce012.nq.gz
│   ├── e4864e0da5744783c93fb4a25e19e8b8aa44b8fb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7399bda1bb64cb5e5648c7b921fc9080c2e687f.nq.gz
│   ├── e87267db43e16ca44e6dc89eb813b644dc0ef071.nq.gz
│   ├── e90d05cb2cbd45750ab27686641f64171df6b950.nq.gz
│   ├── e9571c214530bad39c753d6cde7d5a0a78c6e93b.nq.gz
│   ├── eb0678f5504a676d35971b978846b432e5dcfff2.nq.gz
│   ├── ebb22341d155821c4f9574a82c63a2acb6f43d11.nq.gz
│   ├── f04ee29577a7458a746eecf226d1f24d2de00169.nq.gz
│   ├── f368af5cfc407691a12eb31c05fa3e37ea2c2408.nq.gz
│   ├── f4616824d25a3b439f96d19fdc3d52038298e6fc.nq.gz
│   ├── f5004b145afa4259be96774be242697606113a29.nq.gz
│   ├── f545c485027978df84c54aeefbc4ec03cf9ac2ac.nq.gz
│   ├── f5e060d994576b16cd27587f2fff08d55a91d601.nq.gz
│   ├── fc0518e494bd78b7007023e0790316c6f1c70704.nq.gz
│   ├── fc15b38df9b47e88eacd9cd2447966d80cf1b3ac.nq.gz
│   ├── fc4e564eae7bef0204044ccf6b9b3eeb317fc090.nq.gz
│   ├── fe226bd88dc4e59f60bf0fee84d0f5b36d5f5b13.nq.gz
│   ├── ff071aefeb4777c97332ab08415b991b14647cf4.nq.gz
│   └── ff6499d7058d2ac465e7c76d579071ea30f7ea45.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 92782fb80dffa7c217663e037bc55976aba12f07.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 143 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[sunpy/sunkit-spex](https://github.com/sunpy/sunkit-spex)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
