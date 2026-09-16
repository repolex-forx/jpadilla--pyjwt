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
│   │   └── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
│   └── repolex
│       └── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│           └── chunk-001.nq.gz
├── blob
│   ├── 029c6db562d749878243df5cf12c04731feeca8c.nq.gz
│   ├── 02c44d06f19ccc72e9e58b85683f9a5210fe5abd.nq.gz
│   ├── 039355eec4a31459f7e5bb9187206ef5bfd0e5ab.nq.gz
│   ├── 0428a512944932b8158b3be2b43f61751edc1d70.nq.gz
│   ├── 05fc712928a8326ac71f8e90be25286bfc3676e5.nq.gz
│   ├── 07262074e021b047b4b216135c3f4cf34d477588.nq.gz
│   ├── 0a0a7540c78f406fbf2b5bd89545fd84a4acc6d7.nq.gz
│   ├── 0ab7e4b4bc700e83b8afe569713fba0a4c3b1003.nq.gz
│   ├── 0e5eed3b5e6f5a1b66bd2fa0d5a361e34e496b7a.nq.gz
│   ├── 0f4d1c71bb69aea8eb4865b31baf59f0a8d53fa9.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 1290788f5afc75d6e2573035ae73686df1163e9c.nq.gz
│   ├── 1682ae8073cda04526c483bac76a83e456b45141.nq.gz
│   ├── 17b0d8ace81b7b3596ee1d9b3018a14a6e5d7540.nq.gz
│   ├── 1968cb4413c238b96cfb1320ec1bec28b0793814.nq.gz
│   ├── 1d35ece5d12be5f86f2caf2abcb2c059f4ccc4ee.nq.gz
│   ├── 20790a0a2ac2a2baa48bb72f62fcb60a8e51ac51.nq.gz
│   ├── 21a3c1a51f43c840dab2650599a5d31d6019d361.nq.gz
│   ├── 221e2e2fa670dd0d56e03cd88d7f7e068a66bd48.nq.gz
│   ├── 28c54be17a2634689239e446e13c88545b80dd99.nq.gz
│   ├── 2ad2314c887b565a76fe466eac4c36811c2bf8e4.nq.gz
│   ├── 2cb7d0e6f11585fd7fbe5b4053f85a9dc63b779f.nq.gz
│   ├── 2d57bbc9ebda991ab2cad05c3a73fc6dd935b784.nq.gz
│   ├── 2db90fc1b97817d3d3810ed8ae430e127db23542.nq.gz
│   ├── 2f42b5daf51e9ad66a50af0e46731d40d0f79973.nq.gz
│   ├── 339ed4bc0e77a03a36ecbd09760119bd51917b11.nq.gz
│   ├── 342cc8049a0ba9922d4eb653cad78370d6583997.nq.gz
│   ├── 429c2d7918d08a161d7f1189e9bcb44d526397a2.nq.gz
│   ├── 4a6428e6ac81552c238d2bed2eea08ddb31b8640.nq.gz
│   ├── 4ae7cc3f5c3c1141f9431bf96ce8fb62854bddd5.nq.gz
│   ├── 4ffdb5f2eb65897a5a44ac6e8bfdb9defd7bac23.nq.gz
│   ├── 51b4a8d1c44653406c2b4ca2089e7cdd0fea7f9c.nq.gz
│   ├── 540b33d1155b8379ac13c30189184464ca17d9ea.nq.gz
│   ├── 5449f3c8370c30582461e8dfb95dea85740948bb.nq.gz
│   ├── 564b38fed0ec5d258b9251f31ff844de213a069f.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56e89bb7782f4b5f61c9b2197258dcbf45335d33.nq.gz
│   ├── 57559fc43350e21458fe270b19c2384d6652feef.nq.gz
│   ├── 5b8168ed83b18a1e6e158da44b8c4a6d0d368f27.nq.gz
│   ├── 5cf69467a14a1a163c01d2db0183cd2e624d3092.nq.gz
│   ├── 61439d0cec17c58ed27e5f630088a6c14a757640.nq.gz
│   ├── 615dcf38cf3c9bf0799d035c6b3284aa37db0655.nq.gz
│   ├── 61bfdf03415c70aac51185e6738a8fab9e6f1b01.nq.gz
│   ├── 6451fe9543d65f389aabdf99cb2004d557b365eb.nq.gz
│   ├── 6863f178d70edb9d02efdb818a0381eacc7df58c.nq.gz
│   ├── 71797d40f94ab855b5eb309269b048da008cf5f6.nq.gz
│   ├── 72c8e52d063b99723fa06c35501582d7af0a73f8.nq.gz
│   ├── 73e5aaa68925d2abd1ec26587ed41e10e604fd3c.nq.gz
│   ├── 76832305153d7397df43278459f9fe0b4e92ee13.nq.gz
│   ├── 80254429342662f035c661b535dd18318699abe0.nq.gz
│   ├── 82133027c9eb6dd3ff20c82704ecf25650e474f5.nq.gz
│   ├── 88e2b6ad752425c0c372874e5b3b7695408e7ee3.nq.gz
│   ├── 8a41a36d10882888cd5398f697bc1a2a04706214.nq.gz
│   ├── 8b54204a6bf7b2627941e7383cb1958ee6a54615.nq.gz
│   ├── 8f16d3c004aaa09b9c2e65a3ec5908602cc21b6b.nq.gz
│   ├── 90b7e4d92c92ed742c4607a3ca24ae6efee0d72b.nq.gz
│   ├── 9119f172e7fbd7822fa0b10a3d1b8fe413b3433a.nq.gz
│   ├── 93be658dfe7258ab55828bbd2f08846499e778e3.nq.gz
│   ├── 946d39bfd7fe4bc5c9b4573e934fe75500a3025f.nq.gz
│   ├── 94ca7f77af38333d61b1ac1f9d2867875648d63f.nq.gz
│   ├── 963e62c8cca55839364a5155314f63391ba822d2.nq.gz
│   ├── 968ab08fce4b8c8b9405f9530f11b1649648d232.nq.gz
│   ├── 9718326247bf22c086c6ac6ee672182140b7f3eb.nq.gz
│   ├── 9ce0a10194fd4a0b01666ff6e1c6d778dbebbc14.nq.gz
│   ├── 9f7edc0434cb75bb25c113964cb97f728ed60278.nq.gz
│   ├── a0950e963002f3ff17f3f94697f83dda3e5a149e.nq.gz
│   ├── aa0bd47ff3d8d1280aa47fe4dc64a36495c59957.nq.gz
│   ├── ab315fa8b66ddd109ca6712729d8dc5fc9e8c603.nq.gz
│   ├── acff4539249ad5230db7e98e2ff2057a56ce228e.nq.gz
│   ├── b81e8f4bad3d85a28b5b977406243d7be6db68df.nq.gz
│   ├── ba04941d82e2b44ca5573e6080ed1a4282795941.nq.gz
│   ├── be2cfd5f9c63e3aeb37931b715f9982732a355cd.nq.gz
│   ├── c725aafae3a282eaeb4c6dda254709d0ef640989.nq.gz
│   ├── c7c0fb7c6b7dcfe49b6d002c09d35e130be8069b.nq.gz
│   ├── ceee672fc143b6cba9bd18c8f0d5cc3fc7362cf1.nq.gz
│   ├── d06d1e5511b9b8c277b00c8e45866b02edfff49d.nq.gz
│   ├── d637a2084ff997e853839ccbfcd01710dbe21e88.nq.gz
│   ├── d76a7d10750b736f7af1fe3db0576093d074b788.nq.gz
│   ├── e4428d17f1186088568890ec518b0a7789ea5f7e.nq.gz
│   ├── e624136e36c8fe83a06293f5ac8101919268fc19.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7edad7c7ae4414ad6b4565714b717bd5f769e66.nq.gz
│   ├── e936e260ddd3f4501935918adbf4f24f66f216af.nq.gz
│   ├── ea3bd443c247e888ed042a9264e3a4d2025e45e2.nq.gz
│   ├── f3f3ca5726ad724df43a4b5645468fe1f14ef886.nq.gz
│   ├── f690179c4a4df1234e8624de23babc002eac0ab7.nq.gz
│   ├── f86e4cf9dbf7e2e6aca3d56ea75b40675cd97ac0.nq.gz
│   ├── fd0ecbc889c067a562b3a745c9d2d7934f87d64b.nq.gz
│   ├── fe75697d65b7fdcb748cf43ca93bef7520c5d568.nq.gz
│   └── ff1a9b59f544d5d681bba5521da11b7dd17129d6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
├── filetree
│   └── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 100 files
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
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
