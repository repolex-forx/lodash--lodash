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
│   │   ├── 141c10f6fe92464f3930f04f4818fee7a034eac2.nq.gz
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   ├── 7467a2a2eb8493acdba518e25afab3266560240f.nq.gz
│   │   ├── a82a364c2293f74fcb321113ed5947fb1e3c7acf.nq.gz
│   │   ├── c65250ec39a536e1044dfd970dd050144ac647a4.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   ├── dataflow
│   │   ├── 141c10f6fe92464f3930f04f4818fee7a034eac2.nq.gz
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   ├── a82a364c2293f74fcb321113ed5947fb1e3c7acf.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   ├── lsp
│   │   ├── 141c10f6fe92464f3930f04f4818fee7a034eac2.nq.gz
│   │   ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│   │   ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│   │   ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│   │   ├── 7467a2a2eb8493acdba518e25afab3266560240f.nq.gz
│   │   ├── a82a364c2293f74fcb321113ed5947fb1e3c7acf.nq.gz
│   │   ├── c65250ec39a536e1044dfd970dd050144ac647a4.nq.gz
│   │   └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
│   └── repolex
│       ├── 141c10f6fe92464f3930f04f4818fee7a034eac2.nq.gz
│       ├── 548e9cac26bc28fc6f3d2d9cab59fcd3138b8d6f.nq.gz
│       ├── 5defe7d97543b79e40aeb2ce1f4492240aa5a581.nq.gz
│       ├── 6ce9df8504b4b9c628f10ecf89cb160b03166753.nq.gz
│       ├── 7467a2a2eb8493acdba518e25afab3266560240f.nq.gz
│       ├── a82a364c2293f74fcb321113ed5947fb1e3c7acf.nq.gz
│       ├── c65250ec39a536e1044dfd970dd050144ac647a4.nq.gz
│       └── e0971cd02cde517b4be70cf7ec3b198a98cdb608.nq.gz
└── blob
    ├── 00b2f3d1ca250a9dad4b01ae87dd2bb945c6b714.nq.gz
    ├── 02141a5d9408b39f1bed8682ed95e10bf84f48ff.nq.gz
    ├── 0276f4ea93f4cc29f822793c39f76a4536a0e78b.nq.gz
    ├── 02c82644f89e5dfec43e98aaac81731546119edc.nq.gz
    ├── 02f308a11e701a568b1600aca3abf7d5d5b14172.nq.gz
    ├── 034c7092d5d4929693968226c1fc3efbf0e36b2c.nq.gz
    ├── 035bc77361d5febf9526aef30b8fd93f539ad9be.nq.gz
    ├── 04f8421523340f6e81997759db48d4a0d5417025.nq.gz
    ├── 05f40104feec71a59d49a356480f30b3437888d7.nq.gz
    ├── 0618e208c3488f9d332eff840219c4b37806a396.nq.gz
    ├── 062516acd99bfa1ec331924686c7b49065e0fa4f.nq.gz
    ├── 08210e2d72ba5ba8e48ffd633bffbb4944ddc678.nq.gz
    ├── 085ccaecaf5fa5c34bc14cd2c2ed5cbbd8e25dcb.nq.gz
    ├── 086e1aaf6a5f8c3f4e1b37bd0356adb6acc02429.nq.gz
    ├── 099cbf35d455e13d49010e736c40bab22c3d1a23.nq.gz
    ├── 0a7c552e0dc123d7cd91c9bf63115c253432d392.nq.gz
    ├── 0b24501dc3c1da4543d1264898045ea393091881.nq.gz
    ├── 0bca8c8929e361a5493332cb78bee3fe84fae5c6.nq.gz
    ├── 0c377e307e54c7d1ac78b316b6b949085aa368a6.nq.gz
    ├── 0d8dbe40bbae53e21a638e2bd1694a20e4ff198e.nq.gz
    ├── 0ddb9a1764a7244e13fb3ae0ed1ae7a286e9e138.nq.gz
    ├── 0ea45c3cd7e310c70f7300a409b07cb4edf2deb6.nq.gz
    ├── 0ee5497874cec4a5599e562dd7c00b8c57bc5a44.nq.gz
    ├── 0f8dbc0fe47ed2a18dfa42ade884ce76fee33c3e.nq.gz
    ├── 0fb24d0c855313ee1d6d4ee23f082b7e360987a3.nq.gz
    ├── 1034d66fb4405598401302e3e624b1674d2bf1e4.nq.gz
    ├── 10998ae7b37f7462d6d8780c092b2c42f2b87249.nq.gz
    ├── 11b23cb1b92b7d1c33c8d9d0649601897d71c8d2.nq.gz
    ├── 12c7797fdc6a98f9e3bd37d8416fe33a057deaae.nq.gz
    ├── 13a41d284b8d5fe700a5ad145a5507664d3f032f.nq.gz
    ├── 14a3da825e9acbdca905ef2364a7fdcbe5ebc55c.nq.gz
    ├── 14f8aa87eae0c2616608e5b35d161d1daa860faa.nq.gz
    ├── 15a74d10e694d26db0754e7c9cc2b3a5135373bf.nq.gz
    ├── 16cf7bf57417d2d487b7476b4aa7a41d0e1fccb5.nq.gz
    ├── 1714f2ddcf20368ba225ad8f7d014b0122a6ac54.nq.gz
    ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
    ├── 1aa746ccee0a254332bb4f32567e38e699813862.nq.gz
    ├── 1b3c6925b55a93083c1fde3e55bba95be93235f4.nq.gz
    ├── 1c13cef9640800558263fe56a38a09dbb37472e7.nq.gz
    ├── 1c8397f333036b2d4bc28db5d21c9454cd4c9692.nq.gz
    ├── 1ca539d7166974f6dc5d5e375fb1c5000aca1744.nq.gz
    ├── 1dba81c94a2b26bf8c3ed7617d9dc779471dd3b7.nq.gz
    ├── 1e93d90354424284c84482c658ec946959237f66.nq.gz
    ├── 1f33a3315f505d625e38fb5027aef8c2297ae467.nq.gz
    ├── 1f4f8818edcd1784af69b58018203a8affb3d07f.nq.gz
    ├── 200a37083d6d9f325c493ffe490dde115521f2bd.nq.gz
    ├── 21682c3dcaf11f001770e2a883348b9aac2006ca.nq.gz
    ├── 2174d03a9c91a29a40ce8e9cfd715e9b9320f178.nq.gz
    ├── 21bf42bb3b37e10d37a91979db1091d90766da8e.nq.gz
    ├── 2250669eeb3f354195f23393db7fe5a09b7f4481.nq.gz
    ├── 22949c3bfe06e17e37e6aa55d029f4ebef22f348.nq.gz
    ├── 23602599258f2eace30cf5845617c5dcd9c627e7.nq.gz
    ├── 236cf6768e301ce2700f8edaf8224bd258b99121.nq.gz
    ├── 240404ce794ee534a6afdd00d7439c706442a266.nq.gz
    ├── 25692dda796f0169383f92b8b973cd6e3864bc06.nq.gz
    ├── 25758722479507828f54419f351f16b2c3cf58ac.nq.gz
    ├── 257b224ff44d308b371a5c34048baccc1b0cf390.nq.gz
    ├── 26d38009705311631479a650f8d62ded966668c9.nq.gz
    ├── 26e8d582a25b33e2ab54a7f98cb6aed4a14ff8da.nq.gz
    ├── 26fe37542f865a5fc668ceaaa597261351416abf.nq.gz
    ├── 2756b44b95d9896c311bf43ebf3ad8958988a09b.nq.gz
    ├── 28941b07eff6f7ca22016531e48d3e7187e8e8d9.nq.gz
    ├── 29e355d33a615b15b348c0018639349f8341fb4c.nq.gz
    ├── 2a620987e0e1b7e9ad3213c1c0541cc7db5afea0.nq.gz
    ├── 2b8a670ecd14d71acea1a18c9e0cacedf5f4d181.nq.gz
    ├── 2d1da80be67fce7e88d36e4e26100a73fc85db71.nq.gz
    ├── 2d75261bb675f5f878a9ca549340d11694287ea9.nq.gz
    ├── 2db17322778f1baecfaeafea7111894915652302.nq.gz
    ├── 2dfa72800e5c50446c46bf4637f496b8db922e35.nq.gz
    ├── 2e95ca6f525428366b3c49bda6353af22e72b4bb.nq.gz
    ├── 2f7a1326adca7cff64de64a5a5fee28fd40c0e7d.nq.gz
    ├── 302545f4038e59c89a3647d2d176f92f436953ec.nq.gz
    ├── 30ce3e1c37f100baf1947106acf5d875c8a3f580.nq.gz
    ├── 3148292385c828ff5621c85fedd342dbdfd8819c.nq.gz
    ├── 32252a3f5906112bc995bbabe6872a9a25d75a8b.nq.gz
    ├── 32a912d3f99b49638d3701a51a136f22d20e83ae.nq.gz
    ├── 32d4ff4c3ee0df45998d1e7aa3d2093bf845b6bb.nq.gz
    ├── 33d2c4d4649ec35b7771213977d7c83180907ccd.nq.gz
    ├── 3512d42fb43c83e2cdd86804c8ef276bda006fef.nq.gz
    ├── 36f52664f84c54389f3b9ffc7e2853927790f048.nq.gz
    ├── 3774ff986139c8a7534e14bc8987fe80418dcc1b.nq.gz
    ├── 3775a4111c42af0b02444742e302156b073afbfa.nq.gz
    ├── 3778a27b4ad1e089aa282ac15bc4669702932d99.nq.gz
    ├── 37a7af5c7d0af06a39087261b84d079d17a6fedb.nq.gz
    ├── 39dbad8e30ea5fdce752a18d75a2d0648c8b79d6.nq.gz
    ├── 39efec5e09c75bd5f805078d35c56b6ed6ac5dd6.nq.gz
    ├── 3a8e1b7dcd4454e3ba8f59c99dd1e91ebe943c0e.nq.gz
    ├── 3ad5c1fabab7fe772141e48c2acd440ba688aee2.nq.gz
    ├── 3b196c48ecb30a673782aee86970b115c1e88e37.nq.gz
    ├── 3ba864b0f94e2ac0f7d46089647481a89a075f54.nq.gz
    ├── 3c4f07240cc0aeec0c1195395778f58928b4ab58.nq.gz
    ├── 3c5448223d5cd270fec82e0178f9059f9eba1b55.nq.gz
    ├── 3db0f361799c5fd3c8d44453c0e74eed59fe203e.nq.gz
    ├── 3ef3b6a5fff3f54c2ceb107d251bb22484383588.nq.gz
    ├── 3fa7a9d086942f1e8b4bb7940117969ae7537a89.nq.gz
    ├── 3fede079b5ea9d418c72e66eb298af99a926dd8f.nq.gz
    ├── 4121653823006c29b4469c8a21bb9c1fb26aab50.nq.gz
    ├── 423fe5a963552fecb71305fe83578cb5ef6d9b4a.nq.gz
    ├── 42768ad24baee2070da44a50b55f216cd1a6c7bc.nq.gz
    ├── 42c9d5a95b6e894553b5326063b232597d89bd43.nq.gz
    ├── 43424e43788196b52efc4d560237a087b50304de.nq.gz
    ├── 448bf171d53aef7d9b555d219d8864719b97dffb.nq.gz
    ├── 46b67479eeb16aee4eb885fa9e3e0f26ac3609fe.nq.gz
    ├── 4726e62208e024a017a7c5325e160e202976d7d9.nq.gz
    ├── 4752d1dcb57448c4900496e758d6d38f30a24349.nq.gz
    ├── 47d156244dc0e17d6c53c206f7117a6e4ebc0f2c.nq.gz
    ├── 47f2ef0a9ae3d037e466a4d4c08e27b1b468b3ce.nq.gz
    ├── 4a29737e34fb3f6347ef51357f7a04125cb6022d.nq.gz
    ├── 4a44df3f3484758528a7a6ff9a7865104d22f56b.nq.gz
    ├── 4a48ab9b5a8b494bfc6b3c1e27dbb8b3ab599288.nq.gz
    ├── 4a64d2664889b56d1a94fc2efffc92c67d05e1b7.nq.gz
    ├── 4a786d7533fc6e2dc969ecdf9f83b37cba306179.nq.gz
    ├── 4b4d8e3bc55ca15dddda43efdb6d59dba7cc8f03.nq.gz
    ├── 4bd6d1999ea141e15c0509102d5d6e0bcdf244b4.nq.gz
    ├── 4d3f25e37caba43a03d80213f5575270f9316c0d.nq.gz
    ├── 4d9fdaa5d2d8f1dd76d41e9a2d370ccbf30a5ba7.nq.gz
    ├── 4e34c827daa5f826c3f1033728f52469194d66e5.nq.gz
    ├── 4e5c08a90cb142857dd8b180cbcb6757f7727306.nq.gz
    ├── 4ef55e8d080e42564bd391790d85fe5f7d83e2d0.nq.gz
    ├── 4f81a651468e89ce321c5067c233f87da86a6666.nq.gz
    ├── 4ff9cf5bc90883fb2a570baec454281df47fec60.nq.gz
    ├── 501130796a5fa80c352b87defde9def6510f91fc.nq.gz
    ├── 52cf7facbd9412f7a7259e8e22cd235032b8f8a2.nq.gz
    ├── 54aa2c407132ef9fd9d830406fe4bf2f3f692cd1.nq.gz
    ├── 54e2ed1cd080ecaeca80ab4a3bc4bac997570d9c.nq.gz
    ├── 54e7fab451792859690363bc1bbbfffbcfc15cb9.nq.gz
    ├── 55970e00659ee82fd180064211a881d3aa53cf08.nq.gz
    ├── 55b982d7c8e69c12497a020b798010f570d5cdaa.nq.gz
    ├── 5684a4485977a607f5a1ce969a715ca6d6fe5120.nq.gz
    ├── 576de3fe05f2b49603d4f35ecd70d3dde8aa7de5.nq.gz
    ├── 57eaeee95b5b4189a9080e775e5ba3d6b602f0d3.nq.gz
    ├── 57ff29e1f996d65ce1776bd068ca0a172ec79ef8.nq.gz
    ├── 58a87718dcf286b9c18383b9d921a3e57a324e21.nq.gz
    ├── 58b805fea8404054e4a3b0afbb3990a5be64b401.nq.gz
    ├── 59c0c1afebc1457effb64e8e9e641e5f99318408.nq.gz
    ├── 5a206d2aa58fe5e8aa074dddf388c68c0e753941.nq.gz
    ├── 5a4907b00a3159ead6136134334a577c0f57f7ea.nq.gz
    ├── 5b0b38c4b5df3fa18b898e27a8eb5278e516ec18.nq.gz
    ├── 5b2687543f380c72cd7bf9e5d354f6ce87130e49.nq.gz
    ├── 5b63f8baa09e68e396471bf5377cb38cef2e5334.nq.gz
    ├── 5b7c5f4baf7dbf0a09f91812e92c41658304cf29.nq.gz
    ├── 5b8ee929b493910450e9819d6064992b97e9b192.nq.gz
    ├── 5d063e21f339b48d9780806bcb02940b5ddbf413.nq.gz
    ├── 5d3d9ed76b93c42de627345264d6d5fae7498503.nq.gz
    ├── 5d616c77b5bd035add73e26420abb8c9e70f8861.nq.gz
    ├── 5e38f29d5b9b8338deaca9408b1f791e447f9e77.nq.gz
    ├── 5f7fd42a5e7513396392df4355c4e6bef5b5e192.nq.gz
    ├── 603aeb330cb044745430981d9cb03b978841ffdd.nq.gz
    ├── 617092d8980f3ef029fb64aa8fce0cb4882adf35.nq.gz
    ├── 61d28c08e87390c81eac892c4fa3117cadf3411e.nq.gz
    ├── 62292dcb333e4e8dac08c0dc1e574b3741d043ef.nq.gz
    ├── 632af43abf8727208e5c713e7a6034feb1b12a24.nq.gz
    ├── 63cb9e086f755220ebb9372d473a1032540aa213.nq.gz
    ├── 63d850fe2857920f0ddae1f01cb827561ec1cc2d.nq.gz
    ├── 64193fdee3713543b89d151ebf53cd7dad9c0134.nq.gz
    ├── 64c6d0a209a3d9784dd0d4e4c898ff62598d0b24.nq.gz
    ├── 65069f0f38c4609a1c68795977c4d1bb72dd1a37.nq.gz
    ├── 658c1ffb2f18c6b2d7cfee58c93cdeb8f11ec858.nq.gz
    ├── 6855c861bb6a45c58111d2d9106b9620e8ded7a5.nq.gz
    ├── 6865c960497cdd5663acb5548596d00dba342063.nq.gz
    ├── 68986c3b0bd1b8a198dd8a6ae9226850a09766f7.nq.gz
    ├── 68a5c17700e7a69ef4224c127023410b9bba9e15.nq.gz
    ├── 691d92e92b2fb6594d8e328f23d8b40ff97d6096.nq.gz
    ├── 6969d4bd246f926c3fd5d429d8550f6a72c71490.nq.gz
    ├── 6a960d49e108eb183c8a616cce2d60b46f568db3.nq.gz
    ├── 6ab73f57ae0cd1680de8ef40dc4c93f2ecaf5c62.nq.gz
    ├── 6adf726ce44610251d9dacfa3ae0d1a4f8c914e5.nq.gz
    ├── 6c1873d8e62c86f0947a00c99ee67904dadbb8d3.nq.gz
    ├── 6d2a8a7b8abccaaac6e29a723fec2b3238182d63.nq.gz
    └── 6d597743295850518fb98a23437c7770b97fe646.nq.gz

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

## Source repository

[lodash/lodash](https://github.com/lodash/lodash)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
