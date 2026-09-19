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
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702
│   │   │   └── chunk-001.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│   │   │   └── chunk-001.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│   │   │   └── chunk-001.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2
│   │   │   └── chunk-001.nq.gz
│   │   └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2.nq.gz
│   │   └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852.nq.gz
│   └── repolex
│       ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│       │   └── chunk-001.nq.gz
│       ├── 697344d25990641b8b2aa85f0a60634b590b5702
│       │   └── chunk-001.nq.gz
│       ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│       │   └── chunk-001.nq.gz
│       ├── 783f324e5d2155462515ced45718fc164dd04db2
│       │   └── chunk-001.nq.gz
│       ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│       │   └── chunk-001.nq.gz
│       ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│       │   └── chunk-001.nq.gz
│       ├── bd9700cca7f9258fadcc429c1034e508025931f2
│       │   └── chunk-001.nq.gz
│       └── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│           └── chunk-001.nq.gz
└── blob
    ├── 029c6db562d749878243df5cf12c04731feeca8c.nq.gz
    ├── 02c44d06f19ccc72e9e58b85683f9a5210fe5abd.nq.gz
    ├── 02f4679cbb55a854419b18af322d93db1b295312.nq.gz
    ├── 039355eec4a31459f7e5bb9187206ef5bfd0e5ab.nq.gz
    ├── 0428a512944932b8158b3be2b43f61751edc1d70.nq.gz
    ├── 05fc712928a8326ac71f8e90be25286bfc3676e5.nq.gz
    ├── 07262074e021b047b4b216135c3f4cf34d477588.nq.gz
    ├── 07ace1179f7888170ad340af9a967b65e76a572d.nq.gz
    ├── 07d30a65c65af715c034ea1b270418d65baa26aa.nq.gz
    ├── 0a0a7540c78f406fbf2b5bd89545fd84a4acc6d7.nq.gz
    ├── 0ab7e4b4bc700e83b8afe569713fba0a4c3b1003.nq.gz
    ├── 0d5344467d6b5484de9eb458cdd1141b0b3bda22.nq.gz
    ├── 0d98588203881862523e90deac6050776c98231d.nq.gz
    ├── 0e5eed3b5e6f5a1b66bd2fa0d5a361e34e496b7a.nq.gz
    ├── 0f4d1c71bb69aea8eb4865b31baf59f0a8d53fa9.nq.gz
    ├── 0fe0761f1a5bd1aaaa4e6e71299939fcb06efac5.nq.gz
    ├── 109a8bf77e46617f6b0f34d4b2782fa7a2d79cd3.nq.gz
    ├── 1122af868aea437feab752be6539c02ebd75cc51.nq.gz
    ├── 122dcb4e16fdc9dc1023afb97432c45f26b60270.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 126fc9b7dc324692efb69c211c2e1ba1d7f3e0c5.nq.gz
    ├── 1290788f5afc75d6e2573035ae73686df1163e9c.nq.gz
    ├── 14b8a8d7890f178412f57d578addb308bc97ee26.nq.gz
    ├── 1672acf68e964323115314faba584526ffdf5eb6.nq.gz
    ├── 1682ae8073cda04526c483bac76a83e456b45141.nq.gz
    ├── 17b0d8ace81b7b3596ee1d9b3018a14a6e5d7540.nq.gz
    ├── 1968cb4413c238b96cfb1320ec1bec28b0793814.nq.gz
    ├── 1a39552777649745723dcda6ac84a1b8f91041bf.nq.gz
    ├── 1ab3d955415c5b4eefe1f6a8df2774d352125ec0.nq.gz
    ├── 1b466a3d7e7bf488489b5dd98a3a4f69c07ad220.nq.gz
    ├── 1d35ece5d12be5f86f2caf2abcb2c059f4ccc4ee.nq.gz
    ├── 1d3a1c47ce0e2dbc43db70f0e16e2659704e135d.nq.gz
    ├── 1f1c37171d6f7c07741b94c6306b9b72c6a71fab.nq.gz
    ├── 20790a0a2ac2a2baa48bb72f62fcb60a8e51ac51.nq.gz
    ├── 21a3c1a51f43c840dab2650599a5d31d6019d361.nq.gz
    ├── 21fac3fe7dfc54dd743c709a6a47471791ee7fba.nq.gz
    ├── 221e2e2fa670dd0d56e03cd88d7f7e068a66bd48.nq.gz
    ├── 2255db811d622270e0f94a51f4d78d350b06295d.nq.gz
    ├── 229b2ebbbc901935f951a93de7dea83f4d0524b5.nq.gz
    ├── 2432563056a460c59d6e615968df456da3ec49cd.nq.gz
    ├── 28c54be17a2634689239e446e13c88545b80dd99.nq.gz
    ├── 28da7a845cb054b4e8093f5dbe8f81d27694adff.nq.gz
    ├── 2a91426d0f815610bad3b2272f3826d672966d13.nq.gz
    ├── 2ad2314c887b565a76fe466eac4c36811c2bf8e4.nq.gz
    ├── 2c1391875164e99be58cb32cf2138d3559942edc.nq.gz
    ├── 2cb7d0e6f11585fd7fbe5b4053f85a9dc63b779f.nq.gz
    ├── 2d57bbc9ebda991ab2cad05c3a73fc6dd935b784.nq.gz
    ├── 2db90fc1b97817d3d3810ed8ae430e127db23542.nq.gz
    ├── 2f42b5daf51e9ad66a50af0e46731d40d0f79973.nq.gz
    ├── 3034d04671c5b7abf496ce22963b0701cf722cea.nq.gz
    ├── 320777c962e11e4bbff31aa990f02988bef93860.nq.gz
    ├── 337de96a2ab2bdf5b054f0a119ee4c7019778956.nq.gz
    ├── 33857161ed9d54c95def8e55714c574537333d6d.nq.gz
    ├── 339ed4bc0e77a03a36ecbd09760119bd51917b11.nq.gz
    ├── 34091b5e7f90bb09453ef68d9b35762463ad182f.nq.gz
    ├── 342cc8049a0ba9922d4eb653cad78370d6583997.nq.gz
    ├── 34f4c3c523318f317ebfb5638de640949db95d9c.nq.gz
    ├── 35c7fa951e5f70cfc1620f1cea91ff3429026d87.nq.gz
    ├── 35f9cc22092c46ef06984420c7f96add2bf1fe77.nq.gz
    ├── 3a201436c5b5064c32f117f6a1590a8af2af3b84.nq.gz
    ├── 3a58006403df07f5c94040fbafcf1d5144515b58.nq.gz
    ├── 3bf7f97be76c894dbdd410abf7fa01fb4a5afc83.nq.gz
    ├── 3efdc0db28ba2553d997dac180eef522cff8129a.nq.gz
    ├── 40a745d865c02679f758ceb5bda28a8f907c2528.nq.gz
    ├── 41d71c2184498d06282b442a365f4c1ed4f1f9df.nq.gz
    ├── 420212d9d1f1b7e2e443a7dc6311c302c2701155.nq.gz
    ├── 429c2d7918d08a161d7f1189e9bcb44d526397a2.nq.gz
    ├── 432631e7ce5e9c35a22ab286e01827373b5c6b11.nq.gz
    ├── 43de2c532cf6ecfce67f5979c1b082cae24d9f7e.nq.gz
    ├── 44ccf0b3ed8c97d2b4b2a0596c346cdee37e409e.nq.gz
    ├── 456c7f4d80b6ec98c284693ec3819b291ad837e1.nq.gz
    ├── 457a4e3580ccc21cb69317008478d20d600abcbc.nq.gz
    ├── 4754db605e83f563cef02b1974c266fd97c63e26.nq.gz
    ├── 48d739ad68e8a1412bfe165ab7e051591d0d5a9b.nq.gz
    ├── 49d1b4881a9b758863ca613d84fd1c835d63c3ac.nq.gz
    ├── 4a6428e6ac81552c238d2bed2eea08ddb31b8640.nq.gz
    ├── 4a7790e2ce1875c7f10e701eee4cfc0f23485f85.nq.gz
    ├── 4ae7cc3f5c3c1141f9431bf96ce8fb62854bddd5.nq.gz
    ├── 4b4bdcd1dba5195ea702974da7b9924bac348390.nq.gz
    ├── 4ec0fcb8f7dbd2b102e7260527995194671c86b6.nq.gz
    ├── 4ffdb5f2eb65897a5a44ac6e8bfdb9defd7bac23.nq.gz
    ├── 509f788f530e0958d8f120b95778c88c2579d3ce.nq.gz
    ├── 50f5d1e81d90e34f6ea3eefe4d6a7b1691fc54b1.nq.gz
    ├── 51b4a8d1c44653406c2b4ca2089e7cdd0fea7f9c.nq.gz
    ├── 533b72f0f5d220969e07a8a7f612e12a7fcf8c84.nq.gz
    ├── 540b33d1155b8379ac13c30189184464ca17d9ea.nq.gz
    ├── 5449f3c8370c30582461e8dfb95dea85740948bb.nq.gz
    ├── 54663e1dca39694e521dc5e34745137be9c80ed1.nq.gz
    ├── 55deca5297c1368ca8f7c6b04f3663a29f533847.nq.gz
    ├── 564b38fed0ec5d258b9251f31ff844de213a069f.nq.gz
    ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
    ├── 56e89bb7782f4b5f61c9b2197258dcbf45335d33.nq.gz
    ├── 57559fc43350e21458fe270b19c2384d6652feef.nq.gz
    ├── 5822ebf609476db99839e4791744378807183ffc.nq.gz
    ├── 5b8168ed83b18a1e6e158da44b8c4a6d0d368f27.nq.gz
    ├── 5cdf5654b0ad5b0052d1c6214e5a23c3d2fa9836.nq.gz
    ├── 5cf69467a14a1a163c01d2db0183cd2e624d3092.nq.gz
    ├── 5d6c6fb66e9412c0bf88bebc18dcef5f7d6eb70a.nq.gz
    ├── 613b91dd0bab0ad123de647fbbce9ef9c690f2e3.nq.gz
    ├── 61439d0cec17c58ed27e5f630088a6c14a757640.nq.gz
    ├── 615dcf38cf3c9bf0799d035c6b3284aa37db0655.nq.gz
    ├── 61bfdf03415c70aac51185e6738a8fab9e6f1b01.nq.gz
    ├── 6451fe9543d65f389aabdf99cb2004d557b365eb.nq.gz
    ├── 654ee0b744b35a81bb01fe9c4f1bccd041e2cab8.nq.gz
    ├── 6863f178d70edb9d02efdb818a0381eacc7df58c.nq.gz
    ├── 68d09c1c44ce0171b62bf56806e49705d01e77b7.nq.gz
    ├── 70cf628d70ce0f53b25eec4abfceb50aacad27a9.nq.gz
    ├── 71797d40f94ab855b5eb309269b048da008cf5f6.nq.gz
    ├── 72c8e52d063b99723fa06c35501582d7af0a73f8.nq.gz
    ├── 73e2e8914f01ec4ef21340b510640929eeb3f9b0.nq.gz
    ├── 73e5aaa68925d2abd1ec26587ed41e10e604fd3c.nq.gz
    ├── 76832305153d7397df43278459f9fe0b4e92ee13.nq.gz
    ├── 77a05b303b9d9fbf4afb1c9740b3c52f72b4b9a9.nq.gz
    ├── 7a07c3363e2cfed32b38df757953c097dcb9a9e0.nq.gz
    ├── 7cc583bd7d312054d9a5d8fc03d580fec67f475b.nq.gz
    ├── 7cecfbf71d5d0c38420e9284b8578109824f06db.nq.gz
    ├── 7d45039e6d519d83513446331f776071eef4bb69.nq.gz
    ├── 7d4c48493df322d4812553e63e7759787b8ed213.nq.gz
    ├── 7d9935205688a3cb45902017884633a490d59055.nq.gz
    ├── 80254429342662f035c661b535dd18318699abe0.nq.gz
    ├── 8066cf24e71b0d661bc0076ad3e37346f9005cad.nq.gz
    ├── 80b0ca56e5a666882f36e8d48fb00ee1b85b6725.nq.gz
    ├── 81c5ee41a0b3b1aae483b4f6ff57528ec86687bb.nq.gz
    ├── 82133027c9eb6dd3ff20c82704ecf25650e474f5.nq.gz
    ├── 82b92994ccf232504afd04f22ff248f6c37b96b7.nq.gz
    ├── 8494024230d63642d8fbc0a29040406599748a79.nq.gz
    ├── 8762a8cbb3408b5b30901d4dd39fc53097eb31d8.nq.gz
    ├── 878b786087d104539bad156dcf6831f1f8ce2cec.nq.gz
    ├── 881b808a6001a1def177766cf4d07a1af890884b.nq.gz
    ├── 88e2b6ad752425c0c372874e5b3b7695408e7ee3.nq.gz
    ├── 8a41a36d10882888cd5398f697bc1a2a04706214.nq.gz
    ├── 8a51097d4a5ae8a137ba4ddefc41ff8f4fc4b7b4.nq.gz
    ├── 8a7e05e59981edc9ce156ce2da6ba2ad220e81bf.nq.gz
    ├── 8ac6ecf744abede788992cd6d761deb3b92a5dc3.nq.gz
    ├── 8b54204a6bf7b2627941e7383cb1958ee6a54615.nq.gz
    ├── 8bc23195bacfe42ef7a826ebae52cecde0a7b695.nq.gz
    ├── 8dd730b5293c4f733eaa62273244e91c9fbfd0a3.nq.gz
    ├── 8e1c2286e7ea936292f525c44bcc1b0ee30c6560.nq.gz
    ├── 8f16d3c004aaa09b9c2e65a3ec5908602cc21b6b.nq.gz
    ├── 8f199cee7086da3a3b2bca47f7719e9fe44fc884.nq.gz
    ├── 8f78dc3804dfb032ec80aef201e62c15263f1866.nq.gz
    ├── 90030a7e89e9c49d709d8fe9d02c19a4890801f4.nq.gz
    ├── 90b7e4d92c92ed742c4607a3ca24ae6efee0d72b.nq.gz
    ├── 9119f172e7fbd7822fa0b10a3d1b8fe413b3433a.nq.gz
    ├── 914b4db63b17d41a2b3354e354ab68bcf3663df1.nq.gz
    ├── 919b6af9e473054ec709606be9d06ccd6779bd77.nq.gz
    ├── 9378fa49325db5ac3488c12c3fd379b02552f8e3.nq.gz
    ├── 938631f7ffe6bffa3fc7e7af5f675803000b4ed6.nq.gz
    ├── 93be658dfe7258ab55828bbd2f08846499e778e3.nq.gz
    ├── 93ff726f6a3fd163cee16ed6cd3ecde58c27cb32.nq.gz
    ├── 9433b1ff81c1d593b0453f208b5436ffafdda71a.nq.gz
    ├── 946d39bfd7fe4bc5c9b4573e934fe75500a3025f.nq.gz
    ├── 94ca7f77af38333d61b1ac1f9d2867875648d63f.nq.gz
    ├── 962c4982f4c70fd2f487b45180bcc32495b6c2d8.nq.gz
    ├── 963e62c8cca55839364a5155314f63391ba822d2.nq.gz
    ├── 968ab08fce4b8c8b9405f9530f11b1649648d232.nq.gz
    ├── 9718326247bf22c086c6ac6ee672182140b7f3eb.nq.gz
    ├── 9a673c3e91ce6dcb74fee7123a8800638857af1f.nq.gz
    ├── 9a8992ca6b9d2be153e203b11465a8e6e7cdc570.nq.gz
    ├── 9b45ae48c4e0f2c7627c152bf0059e57f17b73ca.nq.gz
    ├── 9b5c1f24d2cad5836831dab6491a4a370ddc5220.nq.gz
    ├── 9be50b20e08113f8488bfc0f9fdf3ff774f06fd7.nq.gz
    ├── 9ce0a10194fd4a0b01666ff6e1c6d778dbebbc14.nq.gz
    ├── 9d4b67449546e06b200aa08a4f8e4ea876eb3121.nq.gz
    ├── 9f7edc0434cb75bb25c113964cb97f728ed60278.nq.gz
    ├── a0950e963002f3ff17f3f94697f83dda3e5a149e.nq.gz
    ├── a12e8ca3f7f73be66f9658efb2472e5d4290388f.nq.gz
    ├── a2868bf04094c158e70128fa37e3c7d9c58d9751.nq.gz
    ├── a84cd5fb4b3f3bceafac226a5cb0cddc890fefae.nq.gz
    ├── aa0bd47ff3d8d1280aa47fe4dc64a36495c59957.nq.gz
    ├── aa29addfcabb91a848b3c143e020872ca17398a0.nq.gz
    ├── ab315fa8b66ddd109ca6712729d8dc5fc9e8c603.nq.gz
    ├── ab7928481a1213b0ac8c8670a0c2c4c98d5bda5d.nq.gz
    ├── acff4539249ad5230db7e98e2ff2057a56ce228e.nq.gz
    ├── b0b23f427ad05f8931450443ecc2ba8af98835c9.nq.gz
    └── b49b5f58af797bbd434dc8d6e4bcbe363b398fb8.nq.gz

22 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
