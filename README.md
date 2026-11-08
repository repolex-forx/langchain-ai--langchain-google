# Repolex Knowledge Graph of langchain-ai/langchain-google

RDF knowledge graph data for [langchain-ai/langchain-google](https://github.com/langchain-ai/langchain-google), parsed by [repolex](https://repolex.ai).

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
rlex download langchain-ai/langchain-google
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4d0b214207bf5a8c7eaae49d193dc2787b8229ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4d0b214207bf5a8c7eaae49d193dc2787b8229ef
│           └── chunk-001.nq.gz
└── blob
    ├── 01100a5bf9b5b75f0009dfd9d90042860b4f6139.nq.gz
    ├── 01370249ed3d6d2fc6b31681d7fe3b7592c57416.nq.gz
    ├── 01e2148dcf10522d9080ae49fc8bd9fb9fc542a3.nq.gz
    ├── 0335cc2fee03221c114b508e20058bfb6433cdd5.nq.gz
    ├── 033c0dfdde53f63af026c612f69dab402ea88579.nq.gz
    ├── 04a0e01b873d100fabff1e00c35c0d57c2e1747a.nq.gz
    ├── 05f817d61166cc97f9fb5327d0b9eb24ce57257c.nq.gz
    ├── 06efd37cadf56c0bc9d6e7ebf11bff57e3fd5efe.nq.gz
    ├── 07ab2edca0c8263d74f788ac405554c56d10ce95.nq.gz
    ├── 07c24b14111f538c866a6e7769b1933a3d5b9165.nq.gz
    ├── 080b75329d8454714490d57958f444c0c4183520.nq.gz
    ├── 0855bac409202404ea6a5b3cb60dcb7f691d0526.nq.gz
    ├── 0949c62480f22d1da99579f22cca4eddeea7e1b5.nq.gz
    ├── 0954f67d4347322c9c472ff092a04097fdf694ab.nq.gz
    ├── 0ae34f7e0564839c7020606b4923c2c8d4af6c84.nq.gz
    ├── 0bf79ec428244d0a6efe1443cd8ec6ccfb231b74.nq.gz
    ├── 0de4d4475086d8527b3d55500a7304d727fc417f.nq.gz
    ├── 0edd77e6883bce89ad5485f9cd8511bfc49b8e07.nq.gz
    ├── 0f07326cd001055e764787d005052511f3ece75d.nq.gz
    ├── 11c9c3a6c0d806f6c091a739081e2f59c0e998a9.nq.gz
    ├── 124436fc4810887f7a92c3fa2371b2bfe2ced917.nq.gz
    ├── 12856b5d9882c329f7abbfbe074064291b08bc8b.nq.gz
    ├── 14211f7225cb2b1854aba5a9d5b9701602df86d2.nq.gz
    ├── 145e4c2d70525641b5e3030463c4c69ac54a92fe.nq.gz
    ├── 16fa24df89509c8cee08cd2eef3b89f965b20e0f.nq.gz
    ├── 1830fbd2e8af6229843ca129a1c31204dceb4df4.nq.gz
    ├── 19a6d44340cac85c8b11cc47e254b6b36131b1de.nq.gz
    ├── 19d350c1d2e4fd20db36d7dc2596302d2c23f33b.nq.gz
    ├── 1a0b2145e5e5feefe0438dd44c6e0396cbb9ca6c.nq.gz
    ├── 1b835bb2be40726d79219fc934020adee9296fda.nq.gz
    ├── 1dc997b7cd3ede28facc0cd89e78219600419427.nq.gz
    ├── 1e32c3ee15689c136e14e4225e9a74955befd193.nq.gz
    ├── 1f18258ab41b90cfb7c1193a0475c718c0c4ee19.nq.gz
    ├── 2259fd05bb92bd260b92a8ba66f6c52548fb9fb5.nq.gz
    ├── 24aa5f82686bf3878e8dfef9f63698b239460e9f.nq.gz
    ├── 24d66cfc4ed8f9c03a38c7c16afccc6c8727c8a2.nq.gz
    ├── 25251f13333c9727afd9579be5bdddc1d62a325d.nq.gz
    ├── 259ff9a31f5c0862d5eb69c4bf6e091063d30820.nq.gz
    ├── 27dde9fe93e8ac05cddf22c124b08ea44e13f6f4.nq.gz
    ├── 28f0c1831fd121e8d5bf67b65ff133a4587629d9.nq.gz
    ├── 2a60b6ca953d38ad65e135671e3980395600723a.nq.gz
    ├── 2ab8784abe277dd7868c993c887f6901ce25859b.nq.gz
    ├── 2bc9ff2f300baa7e2cc9e8b44ca23ed9d19c5cba.nq.gz
    ├── 2c54850c320959aa61eefb76e40abfc3cfc71bc5.nq.gz
    ├── 2c8017abd6650907a71f179ca836bd562759d91e.nq.gz
    ├── 2f21f0deab28d282a49e690a7e281239f174823e.nq.gz
    ├── 302d8e4a736ed5a0564a4f61121dc9028f967917.nq.gz
    ├── 30a9d5d8e859afcb08c45cb29ef18f36215d3107.nq.gz
    ├── 30f1da1b9783759ea5925b7c3622ac2969f1bd47.nq.gz
    ├── 30fdf94a551904e044b07a9fa2fa130f3c482f29.nq.gz
    ├── 3114b95d9db200d275d5d894adbdced06fbcdef4.nq.gz
    ├── 316b7c162532a92a86a9270cbf5afafd8ad17049.nq.gz
    ├── 32acea2b75d56c3107ec02a8fd066cde61b803fd.nq.gz
    ├── 3308e5d2aa7cdf3180986883056975c9865b49fc.nq.gz
    ├── 33aa1236d45f465c4ec6894731b00a60483291d7.nq.gz
    ├── 33dee9b396cc389e09add671f4c0998b86d9b70d.nq.gz
    ├── 33e0e851cfa537d6200162e45fbe6528415476be.nq.gz
    ├── 35881fd6ab1645b01dbe2bc8e47ad6617adc3907.nq.gz
    ├── 35a7db90d5293e41c06e7647a69fb64799ecf535.nq.gz
    ├── 363df8b4ba879f2c530acca220a8a63b8d2d613e.nq.gz
    ├── 371d635c54f0c74c0d10e373b78bb038ede8d0c5.nq.gz
    ├── 38eb9d665d655ab18533c7e9d13ddb246d6f05b0.nq.gz
    ├── 3b3b436a761ac0412aa649b4fe9f02c9671269b0.nq.gz
    ├── 3bd571eb20659f9d3ebd0f8155a46fc01158f9b4.nq.gz
    ├── 3bfd6079b78cf4a318228f831bc7600bc7421684.nq.gz
    ├── 3bfdd612e13a967dbd0f589a9670c555456c78ec.nq.gz
    ├── 3c732f9290084254a8e9685eaa4b2e8de7f3797f.nq.gz
    ├── 3ca3042aae9ec013007fd23a247092dd01a213b7.nq.gz
    ├── 3db78eb45821478d1294db59d445bc407ca52251.nq.gz
    ├── 3dfe8b236c87a149d0477a9bc5173988d2775524.nq.gz
    ├── 3f1cead1da5084079cc46421ce923fb4bfa8967e.nq.gz
    ├── 3f9416d6e3cdcfe978ff4a379f96bf0f55e49333.nq.gz
    ├── 40361b23818c2fc39f1cc26726b2dde8dbc88a2c.nq.gz
    ├── 4246768673f7710c6ce8168a3fff7fa73f071cf5.nq.gz
    ├── 426b65090341f37bc64935cdc681cc8a8fb02a32.nq.gz
    ├── 42eaf1570d9768c73db77ed37779ee0d5bab200b.nq.gz
    ├── 4344c112f7b3a297ce96a3462562632e1cc8496a.nq.gz
    ├── 43c761f753011f07fe9e319d647cb4958c1da9a4.nq.gz
    ├── 445a69575aca09dd665382ef90af979a7088c25c.nq.gz
    ├── 447037d7719c5e797d491e5ffe7215ba7e96ec38.nq.gz
    ├── 452860c21af88170b015646a7c199527681a6dfe.nq.gz
    ├── 45433e42497a354b931d60edeb0b88015da39c39.nq.gz
    ├── 4587d235f91da3fd77046794eb94059a516ac87b.nq.gz
    ├── 46800eed59342ce8b41341df3e4ef0634c9c6886.nq.gz
    ├── 469b47f8d4f8c196d470a9d85f0fd778b35a8c48.nq.gz
    ├── 470f532154b1cd171a2c389be95d3c89ddf4fec1.nq.gz
    ├── 47d0b0b7ef8a51aa289c1e35edd35f2ad0f944ea.nq.gz
    ├── 480d28d82bcf274603649767aa7957eb6b551413.nq.gz
    ├── 4947476990d161891d4871eb57561637ec04b52c.nq.gz
    ├── 49dd8f5f50d2a4419a2df06a5c92ab5987336edd.nq.gz
    ├── 4b41b79b26f0b897a6f820743edb477673a762c0.nq.gz
    ├── 4d3c61f08fb977d35473c8917c2091c9c051d591.nq.gz
    ├── 4d9c37304622cb3a80fc6c3df667f7f6ea290345.nq.gz
    ├── 4d9cf9ba5dd5b09d32b0ba2f3e47c2817aa05f6e.nq.gz
    ├── 4f203ecd4144431221cbb96814e9555be822a8e5.nq.gz
    ├── 4f5054d1dec3a9fef23c021d4c9ae1258a39a305.nq.gz
    ├── 52432e14ed195386a7cb159f455299542303a338.nq.gz
    ├── 532f405e72551ec273357f976a9c476d2f982851.nq.gz
    ├── 53cddf010a6987329d4a105f67f8d8cc15b1d3d1.nq.gz
    ├── 544fe597c8d45d536e1abe72bba5d83ed61c046c.nq.gz
    ├── 559286d4eed2c50b2679beb2ac451b597beb6836.nq.gz
    ├── 55e9cd4f66cd6ec75d2db6bf1d7f9eaedfa7ab78.nq.gz
    ├── 56756edddd178ef07eb068d3401db65bfe48501d.nq.gz
    ├── 57163d108319b28ea104e473b9ef382114d956d3.nq.gz
    ├── 57afa82d0339cc7b8991a4de5b8d54b5ca585794.nq.gz
    ├── 58d9a72eea37c42723008c625b657c0db7263eeb.nq.gz
    ├── 591b38016a08fab43098b80558730046d1117b1c.nq.gz
    ├── 5c2ac51e822ce958d789adddef3ca187c78f52ba.nq.gz
    ├── 5c597a32aaf3d8d1931c8724f01d8e670bf05c96.nq.gz
    ├── 5d0f8def88d6b7db3ebdcaa18015ba312a1b2fb2.nq.gz
    ├── 5d4910d01161457f9ab92c0fd705159b818b4e68.nq.gz
    ├── 5d7496751ce6e650733d06121be8029ad8451e06.nq.gz
    ├── 5f5545b731cbea48b9dbf5b0da15c78154106f6c.nq.gz
    ├── 5fbe0f074175f0976e9af0a897814adc5e1c5250.nq.gz
    ├── 618164f9fc75f9d69cbc5721753d5b06316476a7.nq.gz
    ├── 62a1444bd79ec29d03456126c51097edf4e68c58.nq.gz
    ├── 6449e32f0ed17bd544c6ce96df265de51895664a.nq.gz
    ├── 64d5265eb32cf4c19c59206864db411ec93c3852.nq.gz
    ├── 652b3acbf2c29e692a5e5e662c2596cd5afbe80d.nq.gz
    ├── 66940f8b90116977999ab3e905beb5b260b846a4.nq.gz
    ├── 66be31dbecef53bd14462e9dbffade3f20959783.nq.gz
    ├── 67647ee57c37773f50323adb383fb05cce254bd4.nq.gz
    ├── 695613c7ba8fd6d98c3dd463c73f703d79c926d6.nq.gz
    ├── 6b1644e614de1ac37496e9039aee87559579a377.nq.gz
    ├── 6d0bdd219c38b5ec8ab6041b5aca1708a912edb8.nq.gz
    ├── 6e9befd5bd25c5ed4603250a9cb14a4de3f2cd66.nq.gz
    ├── 6ed99110ff939efe4d27e289f25fedfaf87a5ee6.nq.gz
    ├── 6ef5e63dc54cb76cb38321ece96771d373d9e4b1.nq.gz
    ├── 6f21c12ea0eca012ec3e7338442a9f8b25e6eb58.nq.gz
    ├── 6fc2edb19a8458fc013cea82e5f3a9a3b7ff5cb7.nq.gz
    ├── 6fe7a045a96f8d60488e97dd131a9326a83df979.nq.gz
    ├── 71936bfeec78f63cf7ea41a8dd70699cee019b44.nq.gz
    ├── 719d9b67fe06325490d57b37e004a7c9e11f5a7f.nq.gz
    ├── 71f8d32b15f4160003b3309d028e3b70b1c61975.nq.gz
    ├── 748ab06efff5d793c0b3d8f1772098f7d41a8533.nq.gz
    ├── 74f0f7625fe02e7c66b6465c1096169c292b82a0.nq.gz
    ├── 75577984c0b3171689aa24ab65285a04cf4e2d31.nq.gz
    ├── 756c0c88016d57a83c99ff621f2d1b49c180bb91.nq.gz
    ├── 76ebc12279cfa444cebeede9a41a7507e7674b78.nq.gz
    ├── 77323fd951d83e8d5cfffed58750fafb6622179b.nq.gz
    ├── 7a51c7678435940af6ea31d0ab400209de13561f.nq.gz
    ├── 7c549a96a15096d9dcec5a3b7878b048d5c06909.nq.gz
    ├── 7dcfd0e22de5ac72ec0ae13f5fabd3687d6767d0.nq.gz
    ├── 7ffe21a6c79d80dc84bafef06c6bad93ba16e142.nq.gz
    ├── 80294bfa69c7086647b59ae5fffbdd904e7a3a5e.nq.gz
    ├── 802a5f22d6298ff36798094424e0302d9692eb6e.nq.gz
    ├── 81083c56e5ba708b1f33abc062d880ffe0d9fbd0.nq.gz
    ├── 81eb4aff201270b79d40c3b6ffc0232cfc83429c.nq.gz
    ├── 827d02623081c0d3f89de7294fd35c8d4eed29de.nq.gz
    ├── 83d7dbfae8ce77e60a62203f728833907a165a7a.nq.gz
    ├── 84ed40e282e006bcba063e0104284e5a685d21e1.nq.gz
    ├── 85437b33a2e7ab288ac993956394a1a11d4b0b39.nq.gz
    ├── 85a082148ce3f0f5a39b0b8858ede06f9862d032.nq.gz
    ├── 876e5de40ec28ed77e6fe63f7cdd3be7530c23f2.nq.gz
    ├── 8872c20720a3b2526650fa46c3bcfcc0464629d8.nq.gz
    ├── 8a09b4ecba1ac16d7c8cdff7569b54fd6cdbe8e3.nq.gz
    ├── 8b5ee84f9fcee0af9e9ead6f2dab60d3d593dd27.nq.gz
    ├── 8bcd78a962acddfbd902b1b3c564f362789c67ac.nq.gz
    ├── 8d3028f92600f283f0243013aeac2ca17fde5c0a.nq.gz
    ├── 918f8df97d0986292b48542f1cba904e3cfc6424.nq.gz
    ├── 941efe3753b111335997237df52cf56ba9d026d4.nq.gz
    ├── 9465d164eb8b4bc1009d3c2bad5703099b3caa90.nq.gz
    ├── 9493476d6ba6395336753302e70b93a51f1ba26d.nq.gz
    ├── 94f687ef352995a62354ec26e8fcdf956fc654f5.nq.gz
    ├── 9560e3b8e4c579768eb013182e877973a9173d42.nq.gz
    ├── 976322971fa78a51e9009771255e559ac4d584f6.nq.gz
    ├── 994c08c0afc9187688837c96116d43dd23ce6463.nq.gz
    ├── 9a3bf7d4c4500bb305ba485e8d030f03517b1337.nq.gz
    ├── 9b1a8930f8bcfc53af327eea99015da54d17c672.nq.gz
    ├── 9c451073a531781435844a7e6e4c47ef1918c102.nq.gz
    ├── 9db08b95b60e3d2d1e06ea18a9c61930a662cf1c.nq.gz
    ├── 9e0f1cc7b65d24291051d62f7025be59f8aa7fcd.nq.gz
    ├── 9f5f5c945863e0f4a5b1fe2db47d0bdfbff1bc26.nq.gz
    ├── a043ef1d570486c0a2f749f4bba0b90bb9ebeb54.nq.gz
    ├── a13aaffb435dbc27b718fd7b6afd250ed1b6b8f8.nq.gz
    ├── a15e636a77f5d2bcdb9bc42b6ccf3f895ce35c0f.nq.gz
    ├── a1838e549a62ccb13de74c1cf76551f0a086ffb2.nq.gz
    ├── a30e76f00ecc9fc01c7e3b901962ff0fe444ce04.nq.gz
    ├── a32bc62049aae0164fb14633380a5c3d1f002328.nq.gz
    ├── a34cb326deadc553e2ce1398d4d2e4da24cf9302.nq.gz
    ├── a38353544db98c55c19d296a9d79c0fbeb29be29.nq.gz
    ├── a8f52994527b3d3cadb76fe7f04e16a78698577f.nq.gz
    ├── a996168dad42c5e7a241def712c7fcf06743513f.nq.gz
    ├── ab371be8d653f7bc7b7abdc055f6783329b5150d.nq.gz
    ├── ab4f5797a2d9ee60ad74e7ec277e8abdf9b7765f.nq.gz
    ├── ab8f59726c6ad8bfbcc46c6455057114b11d85b5.nq.gz
    ├── ad4a0d0fe2dc2e261e33d9891d8afcc002b69d9f.nq.gz
    ├── ad7a94d04763bf9f5a883b9d8c47def0f5b9a5ac.nq.gz
    ├── ae060853f0830a649153b8935f5952a4bb636930.nq.gz
    ├── af36d9d4031184343306b83cb2e459c9d88c40bb.nq.gz
    ├── af702d3e6f4a70bf6db7054bc3e61b316675bef1.nq.gz
    ├── b048221b86d3cc8a223a85d8b26362b19c6dde4a.nq.gz
    ├── b0c2151a1946997cb384de78dbbf3403e8ff4149.nq.gz
    ├── b10cd05b2f99e2493bd37be240066ce2bce0b5f3.nq.gz
    ├── b42260da5a6242d6b426709d3ede0328bbcd14ba.nq.gz
    ├── b4422b405a08c416cac550a9ba54af8578f68a11.nq.gz
    ├── b48e03013b25cf1f4799bb10d455b0db9fc4b628.nq.gz
    └── b5601a49df2af012b490e95047bbd3bf13e4934b.nq.gz

7 directories, 200 files
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

[langchain-ai/langchain-google](https://github.com/langchain-ai/langchain-google)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
