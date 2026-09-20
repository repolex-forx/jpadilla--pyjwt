# Repolex Knowledge Graph of jpadilla/pyjwt

RDF knowledge graph data for [jpadilla/pyjwt](https://github.com/jpadilla/pyjwt), parsed by [repolex](https://repolex.ai).

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
lexq download jpadilla/pyjwt
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702
│   │   │   └── chunk-001.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83ff831a4d11190e3a0bed781da43f8d84352653
│   │   │   └── chunk-001.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98620ab2a396a5c887a494259d49552c2093e1ad
│   │   │   └── chunk-001.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│   │   │   └── chunk-001.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9006103b56359b3ad788bb2e380ef17dfe59b05
│   │   │   └── chunk-001.nq.gz
│   │   └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556.nq.gz
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb.nq.gz
│   │   ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc.nq.gz
│   │   ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2.nq.gz
│   │   ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5.nq.gz
│   │   ├── 83ff831a4d11190e3a0bed781da43f8d84352653.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2.nq.gz
│   │   ├── 98620ab2a396a5c887a494259d49552c2093e1ad.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2.nq.gz
│   │   ├── c9006103b56359b3ad788bb2e380ef17dfe59b05.nq.gz
│   │   └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852.nq.gz
│   └── repolex
│       ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556
│       │   └── chunk-001.nq.gz
│       ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│       │   └── chunk-001.nq.gz
│       ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0
│       │   └── chunk-001.nq.gz
│       ├── 697344d25990641b8b2aa85f0a60634b590b5702
│       │   └── chunk-001.nq.gz
│       ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│       │   └── chunk-001.nq.gz
│       ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8
│       │   └── chunk-001.nq.gz
│       ├── 783f324e5d2155462515ced45718fc164dd04db2
│       │   └── chunk-001.nq.gz
│       ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5
│       │   └── chunk-001.nq.gz
│       ├── 83ff831a4d11190e3a0bed781da43f8d84352653
│       │   └── chunk-001.nq.gz
│       ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│       │   └── chunk-001.nq.gz
│       ├── 98620ab2a396a5c887a494259d49552c2093e1ad
│       │   └── chunk-001.nq.gz
│       ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│       │   └── chunk-001.nq.gz
│       ├── bd9700cca7f9258fadcc429c1034e508025931f2
│       │   └── chunk-001.nq.gz
│       ├── c9006103b56359b3ad788bb2e380ef17dfe59b05
│       │   └── chunk-001.nq.gz
│       └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│           └── chunk-001.nq.gz
└── blob
    ├── 029c6db562d749878243df5cf12c04731feeca8c.nq.gz
    ├── 02c44d06f19ccc72e9e58b85683f9a5210fe5abd.nq.gz
    ├── 02f4679cbb55a854419b18af322d93db1b295312.nq.gz
    ├── 039355eec4a31459f7e5bb9187206ef5bfd0e5ab.nq.gz
    ├── 040e81b9d8a13a7bacad82cb542dde35f5c95bed.nq.gz
    ├── 0428a512944932b8158b3be2b43f61751edc1d70.nq.gz
    ├── 0571dd3913fa0499d0b6b8467707dd4059191d02.nq.gz
    ├── 05fc712928a8326ac71f8e90be25286bfc3676e5.nq.gz
    ├── 0631c99cd76ba513711d69d8e89b4d6ce96b3eeb.nq.gz
    ├── 07262074e021b047b4b216135c3f4cf34d477588.nq.gz
    ├── 07ace1179f7888170ad340af9a967b65e76a572d.nq.gz
    ├── 07d151100c05d633ffb4012e08b07b4e2278aad0.nq.gz
    ├── 07d30a65c65af715c034ea1b270418d65baa26aa.nq.gz
    ├── 0a0a7540c78f406fbf2b5bd89545fd84a4acc6d7.nq.gz
    ├── 0a0e2954f4aeaf098bc607c238264fc8fd87cfe7.nq.gz
    ├── 0ab7e4b4bc700e83b8afe569713fba0a4c3b1003.nq.gz
    ├── 0c02eb925c9a5578d5bd7b04be7566c9d59065cd.nq.gz
    ├── 0c6794bc30d8fe786c94873f27c53d7727f3ec27.nq.gz
    ├── 0d5344467d6b5484de9eb458cdd1141b0b3bda22.nq.gz
    ├── 0d54382556ae1319c9b5988ce3e0fe6089d9d222.nq.gz
    ├── 0d98588203881862523e90deac6050776c98231d.nq.gz
    ├── 0e5eed3b5e6f5a1b66bd2fa0d5a361e34e496b7a.nq.gz
    ├── 0f4d1c71bb69aea8eb4865b31baf59f0a8d53fa9.nq.gz
    ├── 0fe0761f1a5bd1aaaa4e6e71299939fcb06efac5.nq.gz
    ├── 102af87137381554016d9fede240bda8254e9dcb.nq.gz
    ├── 109a8bf77e46617f6b0f34d4b2782fa7a2d79cd3.nq.gz
    ├── 1122af868aea437feab752be6539c02ebd75cc51.nq.gz
    ├── 122dcb4e16fdc9dc1023afb97432c45f26b60270.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 126fc9b7dc324692efb69c211c2e1ba1d7f3e0c5.nq.gz
    ├── 1290788f5afc75d6e2573035ae73686df1163e9c.nq.gz
    ├── 13db2b38c1b4318b3c681ecf864d23340c14ce88.nq.gz
    ├── 14b8a8d7890f178412f57d578addb308bc97ee26.nq.gz
    ├── 1672acf68e964323115314faba584526ffdf5eb6.nq.gz
    ├── 1682ae8073cda04526c483bac76a83e456b45141.nq.gz
    ├── 16cae0662e48f605db54cdf86ba1008dba5a4003.nq.gz
    ├── 17b0d8ace81b7b3596ee1d9b3018a14a6e5d7540.nq.gz
    ├── 1968cb4413c238b96cfb1320ec1bec28b0793814.nq.gz
    ├── 1a39552777649745723dcda6ac84a1b8f91041bf.nq.gz
    ├── 1ab3d955415c5b4eefe1f6a8df2774d352125ec0.nq.gz
    ├── 1b466a3d7e7bf488489b5dd98a3a4f69c07ad220.nq.gz
    ├── 1d35ece5d12be5f86f2caf2abcb2c059f4ccc4ee.nq.gz
    ├── 1d3a1c47ce0e2dbc43db70f0e16e2659704e135d.nq.gz
    ├── 1f1c37171d6f7c07741b94c6306b9b72c6a71fab.nq.gz
    ├── 1f8865afbd93e9ab684d19badf991fbe9cfd580c.nq.gz
    ├── 1fb0890b88e0bcd8213f19e7bb60809ffe947355.nq.gz
    ├── 20790a0a2ac2a2baa48bb72f62fcb60a8e51ac51.nq.gz
    ├── 21a3c1a51f43c840dab2650599a5d31d6019d361.nq.gz
    ├── 21fac3fe7dfc54dd743c709a6a47471791ee7fba.nq.gz
    ├── 221e2e2fa670dd0d56e03cd88d7f7e068a66bd48.nq.gz
    ├── 2255db811d622270e0f94a51f4d78d350b06295d.nq.gz
    ├── 229b2ebbbc901935f951a93de7dea83f4d0524b5.nq.gz
    ├── 2432563056a460c59d6e615968df456da3ec49cd.nq.gz
    ├── 266082ae687e7de6d6d9899d61436b423e9ef3cb.nq.gz
    ├── 26c79b243f3689d334a3b39544055d2c12484608.nq.gz
    ├── 28c54be17a2634689239e446e13c88545b80dd99.nq.gz
    ├── 28da7a845cb054b4e8093f5dbe8f81d27694adff.nq.gz
    ├── 2a8cf599bc3422f6d8d27d4c3a24912ff9fa6f08.nq.gz
    ├── 2a91426d0f815610bad3b2272f3826d672966d13.nq.gz
    ├── 2ad2314c887b565a76fe466eac4c36811c2bf8e4.nq.gz
    ├── 2b38b4a4b25fbfed7d835d6369c12ebb1ea9c411.nq.gz
    ├── 2c1391875164e99be58cb32cf2138d3559942edc.nq.gz
    ├── 2cb7d0e6f11585fd7fbe5b4053f85a9dc63b779f.nq.gz
    ├── 2d57bbc9ebda991ab2cad05c3a73fc6dd935b784.nq.gz
    ├── 2d5c9eb30f87b04869ed0d59b34c8ad163b42f96.nq.gz
    ├── 2db90fc1b97817d3d3810ed8ae430e127db23542.nq.gz
    ├── 2f2ee59eff897f27c8b7c49a1fae09fd2b41ef11.nq.gz
    ├── 2f42b5daf51e9ad66a50af0e46731d40d0f79973.nq.gz
    ├── 2f81b1f711f025928acb42e767f5e9b4dfcf3d1d.nq.gz
    ├── 3034d04671c5b7abf496ce22963b0701cf722cea.nq.gz
    ├── 308899aa6a65ef59d088565dc249f0e07bdc074a.nq.gz
    ├── 31250d57f21c8a17ad4c97a3e0c682723dcd5849.nq.gz
    ├── 319a38d4de37c1040042451430b707e4ede4212a.nq.gz
    ├── 320777c962e11e4bbff31aa990f02988bef93860.nq.gz
    ├── 3208c39f3912998b15fe582a54bdc2b62a8593ac.nq.gz
    ├── 337de96a2ab2bdf5b054f0a119ee4c7019778956.nq.gz
    ├── 33857161ed9d54c95def8e55714c574537333d6d.nq.gz
    ├── 339ed4bc0e77a03a36ecbd09760119bd51917b11.nq.gz
    ├── 34091b5e7f90bb09453ef68d9b35762463ad182f.nq.gz
    ├── 342cc8049a0ba9922d4eb653cad78370d6583997.nq.gz
    ├── 34f4c3c523318f317ebfb5638de640949db95d9c.nq.gz
    ├── 35c7fa951e5f70cfc1620f1cea91ff3429026d87.nq.gz
    ├── 35f9cc22092c46ef06984420c7f96add2bf1fe77.nq.gz
    ├── 367ca30c8ead6aee9f813513fb908cb754da5e62.nq.gz
    ├── 3a201436c5b5064c32f117f6a1590a8af2af3b84.nq.gz
    ├── 3a58006403df07f5c94040fbafcf1d5144515b58.nq.gz
    ├── 3bf7f97be76c894dbdd410abf7fa01fb4a5afc83.nq.gz
    ├── 3c10e07f8ef0e11596cbd4176c7d23b071073343.nq.gz
    ├── 3e42da170e43b6f878148b60f6d918a4a822c2e2.nq.gz
    ├── 3efdc0db28ba2553d997dac180eef522cff8129a.nq.gz
    ├── 40a745d865c02679f758ceb5bda28a8f907c2528.nq.gz
    ├── 417f91d85b87ccba6d57f1ceb2cabdd924fe7529.nq.gz
    ├── 41d71c2184498d06282b442a365f4c1ed4f1f9df.nq.gz
    ├── 420212d9d1f1b7e2e443a7dc6311c302c2701155.nq.gz
    ├── 429c2d7918d08a161d7f1189e9bcb44d526397a2.nq.gz
    ├── 432631e7ce5e9c35a22ab286e01827373b5c6b11.nq.gz
    ├── 434e22c2c6db6d4bd2f541420bfa7e1096df9b1d.nq.gz
    ├── 43de2c532cf6ecfce67f5979c1b082cae24d9f7e.nq.gz
    ├── 44b5103705525821b16eaf4a54abb09fa8a13653.nq.gz
    ├── 44ccf0b3ed8c97d2b4b2a0596c346cdee37e409e.nq.gz
    ├── 456c7f4d80b6ec98c284693ec3819b291ad837e1.nq.gz
    ├── 457a4e3580ccc21cb69317008478d20d600abcbc.nq.gz
    ├── 46a1a532e75af58fd596c5e3124068206188c66b.nq.gz
    ├── 4712e2e53dcc4e668f5582a6aedd4e1340655250.nq.gz
    ├── 4754db605e83f563cef02b1974c266fd97c63e26.nq.gz
    ├── 48d739ad68e8a1412bfe165ab7e051591d0d5a9b.nq.gz
    ├── 498a544a8102419c670603b473dad3bf42bf0534.nq.gz
    ├── 49aa77a8e7312fd7819dd8c04a630117e8c4c6d9.nq.gz
    ├── 49d1b4881a9b758863ca613d84fd1c835d63c3ac.nq.gz
    ├── 4a6428e6ac81552c238d2bed2eea08ddb31b8640.nq.gz
    ├── 4a7790e2ce1875c7f10e701eee4cfc0f23485f85.nq.gz
    ├── 4ae7cc3f5c3c1141f9431bf96ce8fb62854bddd5.nq.gz
    ├── 4b4bdcd1dba5195ea702974da7b9924bac348390.nq.gz
    ├── 4bb1ee1fa4a8e1be09a51d25da52c5dab916259c.nq.gz
    ├── 4ec0fcb8f7dbd2b102e7260527995194671c86b6.nq.gz
    ├── 4ffdb5f2eb65897a5a44ac6e8bfdb9defd7bac23.nq.gz
    ├── 506dc82047ef77d1946348939acc0553e0fabc0c.nq.gz
    ├── 509f788f530e0958d8f120b95778c88c2579d3ce.nq.gz
    ├── 50f5d1e81d90e34f6ea3eefe4d6a7b1691fc54b1.nq.gz
    ├── 51b4a8d1c44653406c2b4ca2089e7cdd0fea7f9c.nq.gz
    ├── 533b72f0f5d220969e07a8a7f612e12a7fcf8c84.nq.gz
    ├── 538078af140d32a68061aa8d5f067b7768042539.nq.gz
    ├── 53c0547399f30ec168361801e6a8fd59a90bda83.nq.gz
    ├── 53fd150e80094e7b34c256997c95bfc85d26313a.nq.gz
    ├── 540b33d1155b8379ac13c30189184464ca17d9ea.nq.gz
    ├── 5449f3c8370c30582461e8dfb95dea85740948bb.nq.gz
    ├── 54663e1dca39694e521dc5e34745137be9c80ed1.nq.gz
    ├── 55deca5297c1368ca8f7c6b04f3663a29f533847.nq.gz
    ├── 564b38fed0ec5d258b9251f31ff844de213a069f.nq.gz
    ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
    ├── 56de90c961794f1dfdb2eca9c99a363ca4bde6a6.nq.gz
    ├── 56e89bb7782f4b5f61c9b2197258dcbf45335d33.nq.gz
    ├── 57559fc43350e21458fe270b19c2384d6652feef.nq.gz
    ├── 5822ebf609476db99839e4791744378807183ffc.nq.gz
    ├── 5b8168ed83b18a1e6e158da44b8c4a6d0d368f27.nq.gz
    ├── 5cdf5654b0ad5b0052d1c6214e5a23c3d2fa9836.nq.gz
    ├── 5cf69467a14a1a163c01d2db0183cd2e624d3092.nq.gz
    ├── 5d6c6fb66e9412c0bf88bebc18dcef5f7d6eb70a.nq.gz
    ├── 5e0b244cd49a46d704d494b15e6f637d7986aeca.nq.gz
    ├── 613b91dd0bab0ad123de647fbbce9ef9c690f2e3.nq.gz
    ├── 61439d0cec17c58ed27e5f630088a6c14a757640.nq.gz
    ├── 615dcf38cf3c9bf0799d035c6b3284aa37db0655.nq.gz
    ├── 61bfdf03415c70aac51185e6738a8fab9e6f1b01.nq.gz
    ├── 63406706fef7986f6f996685e0420296f720d42c.nq.gz
    ├── 63e679454757b812331a517442a7a6df313b3104.nq.gz
    ├── 6451fe9543d65f389aabdf99cb2004d557b365eb.nq.gz
    ├── 654ee0b744b35a81bb01fe9c4f1bccd041e2cab8.nq.gz
    ├── 6863f178d70edb9d02efdb818a0381eacc7df58c.nq.gz
    ├── 68d09c1c44ce0171b62bf56806e49705d01e77b7.nq.gz
    ├── 6b3f8ab160108989240e6cda1a26f76cd9c300c2.nq.gz
    ├── 6d136999714685baad635917a0a55af9352b5ccf.nq.gz
    ├── 6d49d24e1ef28937944978d4a875cc922987a3b7.nq.gz
    ├── 6da2ccdfcaffc21998bf29171dbc815a3e801a55.nq.gz
    ├── 6f6cb899f4cce02a951c3639d8693f2be7c7b827.nq.gz
    └── 70a5e537dc184080e9721b64528607852b192748.nq.gz

36 directories, 200 files
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

[jpadilla/pyjwt](https://github.com/jpadilla/pyjwt)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
