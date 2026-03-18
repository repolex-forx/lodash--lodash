# Repolex Knowledge Graph of lodash/lodash

RDF knowledge graph data for [lodash/lodash](https://github.com/lodash/lodash), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download lodash/lodash
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   ├── dataflow
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   ├── lsp
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   └── repolex
│       ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│       ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│       ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│       └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
├── blob
│   ├── 02141a5d9408b39f1bed8682ed95e10bf84f48ff.nq.gz
│   ├── 0276f4ea93f4cc29f822793c39f76a4536a0e78b.nq.gz
│   ├── 02c82644f89e5dfec43e98aaac81731546119edc.nq.gz
│   ├── 04f8421523340f6e81997759db48d4a0d5417025.nq.gz
│   ├── 05f40104feec71a59d49a356480f30b3437888d7.nq.gz
│   ├── 0618e208c3488f9d332eff840219c4b37806a396.nq.gz
│   ├── 085ccaecaf5fa5c34bc14cd2c2ed5cbbd8e25dcb.nq.gz
│   ├── 099cbf35d455e13d49010e736c40bab22c3d1a23.nq.gz
│   ├── 0b24501dc3c1da4543d1264898045ea393091881.nq.gz
│   ├── 0c377e307e54c7d1ac78b316b6b949085aa368a6.nq.gz
│   ├── 0ddb9a1764a7244e13fb3ae0ed1ae7a286e9e138.nq.gz
│   ├── 0ee5497874cec4a5599e562dd7c00b8c57bc5a44.nq.gz
│   ├── 0fb24d0c855313ee1d6d4ee23f082b7e360987a3.nq.gz
│   ├── 1034d66fb4405598401302e3e624b1674d2bf1e4.nq.gz
│   ├── 10998ae7b37f7462d6d8780c092b2c42f2b87249.nq.gz
│   ├── 14f8aa87eae0c2616608e5b35d161d1daa860faa.nq.gz
│   ├── 15a74d10e694d26db0754e7c9cc2b3a5135373bf.nq.gz
│   ├── 1714f2ddcf20368ba225ad8f7d014b0122a6ac54.nq.gz
│   ├── 1c8397f333036b2d4bc28db5d21c9454cd4c9692.nq.gz
│   ├── 1f33a3315f505d625e38fb5027aef8c2297ae467.nq.gz
│   ├── 200a37083d6d9f325c493ffe490dde115521f2bd.nq.gz
│   ├── 21682c3dcaf11f001770e2a883348b9aac2006ca.nq.gz
│   ├── 2174d03a9c91a29a40ce8e9cfd715e9b9320f178.nq.gz
│   ├── 23602599258f2eace30cf5845617c5dcd9c627e7.nq.gz
│   ├── 236cf6768e301ce2700f8edaf8224bd258b99121.nq.gz
│   ├── 240404ce794ee534a6afdd00d7439c706442a266.nq.gz
│   ├── 25758722479507828f54419f351f16b2c3cf58ac.nq.gz
│   ├── 257b224ff44d308b371a5c34048baccc1b0cf390.nq.gz
│   ├── 26fe37542f865a5fc668ceaaa597261351416abf.nq.gz
│   ├── 2756b44b95d9896c311bf43ebf3ad8958988a09b.nq.gz
│   ├── 29e355d33a615b15b348c0018639349f8341fb4c.nq.gz
│   ├── 2a620987e0e1b7e9ad3213c1c0541cc7db5afea0.nq.gz
│   ├── 2d75261bb675f5f878a9ca549340d11694287ea9.nq.gz
│   ├── 2db17322778f1baecfaeafea7111894915652302.nq.gz
│   ├── 33d2c4d4649ec35b7771213977d7c83180907ccd.nq.gz
│   ├── 36f52664f84c54389f3b9ffc7e2853927790f048.nq.gz
│   ├── 3774ff986139c8a7534e14bc8987fe80418dcc1b.nq.gz
│   ├── 3778a27b4ad1e089aa282ac15bc4669702932d99.nq.gz
│   ├── 37a7af5c7d0af06a39087261b84d079d17a6fedb.nq.gz
│   ├── 39efec5e09c75bd5f805078d35c56b6ed6ac5dd6.nq.gz
│   ├── 3a8e1b7dcd4454e3ba8f59c99dd1e91ebe943c0e.nq.gz
│   ├── 3ad5c1fabab7fe772141e48c2acd440ba688aee2.nq.gz
│   ├── 3db0f361799c5fd3c8d44453c0e74eed59fe203e.nq.gz
│   ├── 3ef3b6a5fff3f54c2ceb107d251bb22484383588.nq.gz
│   ├── 42768ad24baee2070da44a50b55f216cd1a6c7bc.nq.gz
│   ├── 42c9d5a95b6e894553b5326063b232597d89bd43.nq.gz
│   ├── 43424e43788196b52efc4d560237a087b50304de.nq.gz
│   ├── 4726e62208e024a017a7c5325e160e202976d7d9.nq.gz
│   ├── 47d156244dc0e17d6c53c206f7117a6e4ebc0f2c.nq.gz
│   ├── 4a64d2664889b56d1a94fc2efffc92c67d05e1b7.nq.gz
│   ├── 4d3f25e37caba43a03d80213f5575270f9316c0d.nq.gz
│   ├── 4d9fdaa5d2d8f1dd76d41e9a2d370ccbf30a5ba7.nq.gz
│   ├── 4e5c08a90cb142857dd8b180cbcb6757f7727306.nq.gz
│   ├── 501130796a5fa80c352b87defde9def6510f91fc.nq.gz
│   ├── 52cf7facbd9412f7a7259e8e22cd235032b8f8a2.nq.gz
│   ├── 55b982d7c8e69c12497a020b798010f570d5cdaa.nq.gz
│   ├── 5684a4485977a607f5a1ce969a715ca6d6fe5120.nq.gz
│   ├── 58b805fea8404054e4a3b0afbb3990a5be64b401.nq.gz
│   ├── 5b0b38c4b5df3fa18b898e27a8eb5278e516ec18.nq.gz
│   ├── 61d28c08e87390c81eac892c4fa3117cadf3411e.nq.gz
│   ├── 63cb9e086f755220ebb9372d473a1032540aa213.nq.gz
│   ├── 64c6d0a209a3d9784dd0d4e4c898ff62598d0b24.nq.gz
│   ├── 658c1ffb2f18c6b2d7cfee58c93cdeb8f11ec858.nq.gz
│   ├── 6865c960497cdd5663acb5548596d00dba342063.nq.gz
│   ├── 68986c3b0bd1b8a198dd8a6ae9226850a09766f7.nq.gz
│   ├── 6a960d49e108eb183c8a616cce2d60b46f568db3.nq.gz
│   ├── 6d2a8a7b8abccaaac6e29a723fec2b3238182d63.nq.gz
│   ├── 6d597743295850518fb98a23437c7770b97fe646.nq.gz
│   ├── 70565a83cce61a6ce84ced32713fe11dfe32ad32.nq.gz
│   ├── 722fd3f1269bb9583042011c611203d302e4e45f.nq.gz
│   ├── 7270bebc060808be33ab2b51539999522b11bf4b.nq.gz
│   ├── 7314d2c07e0740348c8c3d2d0f1b0ad5e66c68a8.nq.gz
│   ├── 75930cb5967b648de0a1df877d2ca88883d7e01c.nq.gz
│   ├── 75aa0780ca597ae36130fed1e89c2ab8b692d2dd.nq.gz
│   ├── 7b2a42ef6012883a3e306531f9a34f16a224f856.nq.gz
│   ├── 7d2ec9ff9c57e4d9983777a66adc84d4df29b9a3.nq.gz
│   ├── 7e0c04944707ca2a60b09fa3d4b17b8238632091.nq.gz
│   ├── 7f0a30502026980b3eb0df7019602f6a04f4fd43.nq.gz
│   ├── 8144e63787d3015e5ab2219bf24fab87b9fe1141.nq.gz
│   ├── 84972788620159cbf2bfc443acbdea47350e69de.nq.gz
│   ├── 849f47472179214c8ee26dd50f908b9a24e63ee0.nq.gz
│   ├── 86663a23782acd841738a5e1c6eba149f6434a27.nq.gz
│   ├── 868012434599b589e3d75190202fe6b4a16270cd.nq.gz
│   ├── 8689d97548112b9b5f817d02ac45ad88dd8f03ba.nq.gz
│   ├── 87a21cf3fde225b78b31f314c227de822ead10fb.nq.gz
│   ├── 87adb6951bbf65e88020848f66e35587fe2db278.nq.gz
│   ├── 8ccd0ea786eaad67e346b4630030f1f97aedbd62.nq.gz
│   ├── 8d35837e10c96c2edc28770510186937aa3f748e.nq.gz
│   ├── 8db97c2104b6479a74c6a268ab7175e60d8a5ff5.nq.gz
│   ├── 8ee8116a543768052b707bb7c7b31ec6cfecea6a.nq.gz
│   ├── 8fd02e0d57076c1bbd6a50bc9abe3ddd20b3b011.nq.gz
│   ├── 91c0b11db77ac50434c3211c8e2dc15af340c687.nq.gz
│   ├── 935626073f85f7a286e48febe48539a85004a77d.nq.gz
│   ├── 937bf586643ccd546e550c30205fd780a699fb59.nq.gz
│   ├── 946bf6db30d3a939b7fb75e03f064de3bda60cd4.nq.gz
│   ├── 957bd9f2adabb791aee25df923efebc85e86c0da.nq.gz
│   ├── 9b34b18369aec4d21e91ca68b356be31e1be30c7.nq.gz
│   ├── 9d0afb50b9ac765747cfa59546662ecf3cacaea9.nq.gz
│   ├── 9e0760f1845c045fbd9e1df3ea3218b973976d9a.nq.gz
│   ├── 9efedcb4424bf230d650afe10b2abc86ac31aaec.nq.gz
│   ├── a0e9f806fa46bf2850cd8f34cb0bead7ddb82e86.nq.gz
│   ├── a0f839dc598edd80d093e1cf954134a916db5af0.nq.gz
│   ├── a23ef787244e34f72e9bac0c19ee7e0be47981f8.nq.gz
│   ├── a2561df971728d988424100c74c817916eca1979.nq.gz
│   ├── a4111791f2ca0197e5faeaf2081351ff162318f9.nq.gz
│   ├── a4b5b4405f1e86602ec22d8dbb8fd0f336fb2819.nq.gz
│   ├── a4da11ae6ca8d4966074b2f7e5529ab07ea79005.nq.gz
│   ├── a6cc9e94a9bd8ce95daa8a6cbb19460463b0eb1d.nq.gz
│   ├── a96ce43fc2d88ae45929cd7544f920fd23af48ba.nq.gz
│   ├── aa21dee6a776c73d1c84d5fc7e7f24ba7f412722.nq.gz
│   ├── aa7e45a98ec330b78095522d516c3afcad29cfe2.nq.gz
│   ├── aacd9b86028cf2b5871bd31fcdcf433190b1cc22.nq.gz
│   ├── acbbd30c06523ea5b7d921684a86b3d60f1c9384.nq.gz
│   ├── ad24053066b2535b3b44cf6a77d9fec3f17cb935.nq.gz
│   ├── af689d3aa7cce466d007c1afda79acdee8a00532.nq.gz
│   ├── af7f537e391f08327e417c7be6323c917d5d3788.nq.gz
│   ├── b0d1e1afdccb1e1fdfebc2851b354d00ba3fb68e.nq.gz
│   ├── b194ad1deb5534df29e611a3014f9138c7504d51.nq.gz
│   ├── b1ae21d8b23f25359f21b6c69f0eb2dd29016466.nq.gz
│   ├── b1f3e50a87dbb3d402323e342068183e6e56c38c.nq.gz
│   ├── b4142ae94fd94dfd6d6dd1036429e233c33df063.nq.gz
│   ├── b5778403b61d721d63f45f72ed1a9fe99a93a422.nq.gz
│   ├── b5dd5dde1f94461d3ca179b9b4dce5e4777864f2.nq.gz
│   ├── b5fa4b2f29cf9e8f70e598178ac3fd1332dd2603.nq.gz
│   ├── b70b1d24d881014f43bbc8f6ac6e5d84921c0ece.nq.gz
│   ├── ba43b7514b3bc744935364b343ec61e6e2084615.nq.gz
│   ├── bc9202c89cadb11de13d5cc279b932fefaade84a.nq.gz
│   ├── bcb7b8c06452cc95c50f418983c959525a978307.nq.gz
│   ├── bcecc4c0daf92a00f11e24d922c23e36d9ecca3f.nq.gz
│   ├── be0291f12ae4800c5287812e4b2fae05a11edeb1.nq.gz
│   ├── bfebe3cf77992e45ea3c7e2e81db652a88899b23.nq.gz
│   ├── c1570c2520a911f862f3ccd327d4e796916d610a.nq.gz
│   ├── c28bcdf24a88d4d1266486af283b3557011e916f.nq.gz
│   ├── c5ff65324b8e3f26995ab753691cff9e8b6c5805.nq.gz
│   ├── c93a0773ff6b1bc4e8bc5e2d6a50313d27ad01aa.nq.gz
│   ├── cc33761c4bfa0a47dc8a019df697bb3bf93ef3e3.nq.gz
│   ├── cd37a0d52de85c54f3e502c9a4fb6c93c4ebcc46.nq.gz
│   ├── cd8131707e2da6851985d247340f39cc68490436.nq.gz
│   ├── cde5bfc880adb0461fc268b38ad33e6c72205d1b.nq.gz
│   ├── ceab12c14136268387658464e2c97ff7a447681b.nq.gz
│   ├── d4da85adaf9ea9e1d7cc35345f1366061b42c50f.nq.gz
│   ├── da1e5334c19375c7855e04792661bf2cc15b7e14.nq.gz
│   ├── daacb5e504f400adfe195b7bd6c596d208988f77.nq.gz
│   ├── dadad22fa7ea591bc7484e51572dfd5fc547237f.nq.gz
│   ├── db58007bb828b1bc66898657fe4b8d14f7da1923.nq.gz
│   ├── dc6f233649be2ac4bbd06c1e5be59bf208472548.nq.gz
│   ├── dd9eb0e3ef6ae354e2ceb653ad48839d27ba83e4.nq.gz
│   ├── ddd6fc35d8c8b68c3017367e614051ffdf2db104.nq.gz
│   ├── de51084e8489f498b89dd9a59d82eb9564b7d050.nq.gz
│   ├── de6869b0a3571958caf6d6c616205b9564ea135e.nq.gz
│   ├── e0a31d0c03bbb67b8e5d5794e8aed397b39916f2.nq.gz
│   ├── e0d8492004d16096fe369bbe07bbad7691f4fe6c.nq.gz
│   ├── e10affebb48dc2aa7a70c575b87b901d91de1aca.nq.gz
│   ├── e26728ab36b9d612af0edb49ea297da5d6c4b96a.nq.gz
│   ├── e2803b21c8cbb2da4a9972c07cefe648640e2ab4.nq.gz
│   ├── e33e63f7e4022cf76de199fbadc3cadcefbe0bd2.nq.gz
│   ├── e419272912bd9fe9b74d512fde1c86b5f4754972.nq.gz
│   ├── e4d5038d5fd8a6b4b1a76a20490a98ae517be1ad.nq.gz
│   ├── e98c8ab091e2a526f06a3eb67e5650f4da923017.nq.gz
│   ├── eb4b11efe5ee01103c2d5fa2f0f6b8921e640cce.nq.gz
│   ├── edf662f36f32f39352a4033cde8c43baef3611e5.nq.gz
│   ├── f1b52347f3389a36a86c4a130ec07463f1644a31.nq.gz
│   ├── f3670f19ff39068ee272632b63935bf4a1eae01c.nq.gz
│   ├── f367b427e60e67272b9a2bec37f71054a3269f74.nq.gz
│   ├── f4312b2ffbc485366e5b3eb2d52fac976597b256.nq.gz
│   ├── f4afb5c14a9776bdf83b07b793f469d896328102.nq.gz
│   ├── f570f7bdd90b660fe0bfa0fd5de065083c54e41f.nq.gz
│   ├── f79bb00587dc955f1b7159274b441e7cb1b9f688.nq.gz
│   ├── f80319b0a4e21532f5139acd618ce6782117b2d2.nq.gz
│   ├── f879363bc75e9cd96e479655916a4e4ec7bba3d9.nq.gz
│   ├── f8e5dc5c8082adb9971f265f07e9dac7b55509c9.nq.gz
│   ├── f945ba866f3f63057af9dc2432b2fee63e7670b0.nq.gz
│   ├── fba33b8a57d351da68abc3340dd4e589bc55764d.nq.gz
│   ├── fbccab54d050bb7d2f503df9fb040d6328cda5ea.nq.gz
│   ├── fc44fa3663851bb3de457cb5a7be3d93abbf7150.nq.gz
│   └── ffaf31710ebf6798081f387736e36500b5525efd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
├── issue
│   └── issue.nq.gz
└── pr
    └── pr.nq.gz

12 directories, 200 files
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

## Source repository

[lodash/lodash](https://github.com/lodash/lodash)

---
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
