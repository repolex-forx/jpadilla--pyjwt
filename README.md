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
│   │   ├── 070015d79ed5277c6d76fa8f996fb9698257afe4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 285afade1d14eb810615c5bc751ea2c6a7a3314a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3f735fdf68cc865a6241aae1fcf92a410c73fbdb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 482364776109cb597af7f679161dcf9c3ef5d0ea
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bf8e70f26309b0a5ceda49ce0a7e97e89eee764
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702
│   │   │   └── chunk-001.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 72bb76cb343bb6d0f40fcd0d136898b8ba08c323
│   │   │   └── chunk-001.nq.gz
│   │   ├── 74399b1856573d8545b8dbbcac0db29a5656979d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7ae1dee63dab887d39ea4ca3365e81392a1c2396
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8041cb607a733a9b5fffe1e9136d55a40bcea25b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83ff831a4d11190e3a0bed781da43f8d84352653
│   │   │   └── chunk-001.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 908ee84aeefb8126a94e48e88ba9916d9d2512b3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98620ab2a396a5c887a494259d49552c2093e1ad
│   │   │   └── chunk-001.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│   │   │   └── chunk-001.nq.gz
│   │   ├── b35d522135044ba10ac41e7db5b95348cb4c4707
│   │   │   └── chunk-001.nq.gz
│   │   ├── b65e1ac6dc4d11801f3642eaab34ae6a54162c18
│   │   │   └── chunk-001.nq.gz
│   │   ├── bc966214de9852258dd00dd2efc01ce6c9a22ac6
│   │   │   └── chunk-001.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9006103b56359b3ad788bb2e380ef17dfe59b05
│   │   │   └── chunk-001.nq.gz
│   │   ├── d25c92ca5e9980ca7bc8b31420bf36e3f4a9e3f0
│   │   │   └── chunk-001.nq.gz
│   │   ├── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│   │   │   └── chunk-001.nq.gz
│   │   └── daf79c1d2143d969e4ba19ec0692cfac773fa6be
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 070015d79ed5277c6d76fa8f996fb9698257afe4.nq.gz
│   │   ├── 285afade1d14eb810615c5bc751ea2c6a7a3314a.nq.gz
│   │   ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556.nq.gz
│   │   ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb.nq.gz
│   │   ├── 3f735fdf68cc865a6241aae1fcf92a410c73fbdb.nq.gz
│   │   ├── 482364776109cb597af7f679161dcf9c3ef5d0ea.nq.gz
│   │   ├── 5bf8e70f26309b0a5ceda49ce0a7e97e89eee764.nq.gz
│   │   ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0.nq.gz
│   │   ├── 697344d25990641b8b2aa85f0a60634b590b5702.nq.gz
│   │   ├── 72ad55f6d7041ae698dc0790a690804118be50fc.nq.gz
│   │   ├── 72bb76cb343bb6d0f40fcd0d136898b8ba08c323.nq.gz
│   │   ├── 74399b1856573d8545b8dbbcac0db29a5656979d.nq.gz
│   │   ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8.nq.gz
│   │   ├── 783f324e5d2155462515ced45718fc164dd04db2.nq.gz
│   │   ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5.nq.gz
│   │   ├── 7ae1dee63dab887d39ea4ca3365e81392a1c2396.nq.gz
│   │   ├── 8041cb607a733a9b5fffe1e9136d55a40bcea25b.nq.gz
│   │   ├── 83ff831a4d11190e3a0bed781da43f8d84352653.nq.gz
│   │   ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2.nq.gz
│   │   ├── 908ee84aeefb8126a94e48e88ba9916d9d2512b3.nq.gz
│   │   ├── 98620ab2a396a5c887a494259d49552c2093e1ad.nq.gz
│   │   ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30.nq.gz
│   │   ├── b65e1ac6dc4d11801f3642eaab34ae6a54162c18.nq.gz
│   │   ├── bc966214de9852258dd00dd2efc01ce6c9a22ac6.nq.gz
│   │   ├── bd9700cca7f9258fadcc429c1034e508025931f2.nq.gz
│   │   ├── c9006103b56359b3ad788bb2e380ef17dfe59b05.nq.gz
│   │   ├── d25c92ca5e9980ca7bc8b31420bf36e3f4a9e3f0.nq.gz
│   │   ├── d7c54dbebdab2ae17f7948fd4432b15e1bb82852.nq.gz
│   │   └── daf79c1d2143d969e4ba19ec0692cfac773fa6be.nq.gz
│   └── repolex
│       ├── 070015d79ed5277c6d76fa8f996fb9698257afe4
│       │   └── chunk-001.nq.gz
│       ├── 285afade1d14eb810615c5bc751ea2c6a7a3314a
│       │   └── chunk-001.nq.gz
│       ├── 3993ce1d3503b58cf74699a89ba9e5c18ef9b556
│       │   └── chunk-001.nq.gz
│       ├── 3ebbb22f30f2b1b41727b269a08b427e9a85d6bb
│       │   └── chunk-001.nq.gz
│       ├── 3f735fdf68cc865a6241aae1fcf92a410c73fbdb
│       │   └── chunk-001.nq.gz
│       ├── 482364776109cb597af7f679161dcf9c3ef5d0ea
│       │   └── chunk-001.nq.gz
│       ├── 5bf8e70f26309b0a5ceda49ce0a7e97e89eee764
│       │   └── chunk-001.nq.gz
│       ├── 6223ba13780a941a3f4c9dec62f282bdd9b5afb0
│       │   └── chunk-001.nq.gz
│       ├── 697344d25990641b8b2aa85f0a60634b590b5702
│       │   └── chunk-001.nq.gz
│       ├── 72ad55f6d7041ae698dc0790a690804118be50fc
│       │   └── chunk-001.nq.gz
│       ├── 72bb76cb343bb6d0f40fcd0d136898b8ba08c323
│       │   └── chunk-001.nq.gz
│       ├── 74399b1856573d8545b8dbbcac0db29a5656979d
│       │   └── chunk-001.nq.gz
│       ├── 7665aa625506a11bae50b56d3e04413a3dc6fdf8
│       │   └── chunk-001.nq.gz
│       ├── 783f324e5d2155462515ced45718fc164dd04db2
│       │   └── chunk-001.nq.gz
│       ├── 79c23d7d9d32364be8f94680d8eda7135c3a15d5
│       │   └── chunk-001.nq.gz
│       ├── 7ae1dee63dab887d39ea4ca3365e81392a1c2396
│       │   └── chunk-001.nq.gz
│       ├── 8041cb607a733a9b5fffe1e9136d55a40bcea25b
│       │   └── chunk-001.nq.gz
│       ├── 83ff831a4d11190e3a0bed781da43f8d84352653
│       │   └── chunk-001.nq.gz
│       ├── 868cf4ab2ca5a0a39da40e5a14dd740b203662b2
│       │   └── chunk-001.nq.gz
│       ├── 908ee84aeefb8126a94e48e88ba9916d9d2512b3
│       │   └── chunk-001.nq.gz
│       ├── 98620ab2a396a5c887a494259d49552c2093e1ad
│       │   └── chunk-001.nq.gz
│       ├── a4e1a3d1218b01c5806420b8f16d9308ac4adc30
│       │   └── chunk-001.nq.gz
│       ├── b65e1ac6dc4d11801f3642eaab34ae6a54162c18
│       │   └── chunk-001.nq.gz
│       ├── bc966214de9852258dd00dd2efc01ce6c9a22ac6
│       │   └── chunk-001.nq.gz
│       ├── bd9700cca7f9258fadcc429c1034e508025931f2
│       │   └── chunk-001.nq.gz
│       ├── c9006103b56359b3ad788bb2e380ef17dfe59b05
│       │   └── chunk-001.nq.gz
│       ├── d25c92ca5e9980ca7bc8b31420bf36e3f4a9e3f0
│       │   └── chunk-001.nq.gz
│       ├── d7c54dbebdab2ae17f7948fd4432b15e1bb82852
│       │   └── chunk-001.nq.gz
│       └── daf79c1d2143d969e4ba19ec0692cfac773fa6be
│           └── chunk-001.nq.gz
└── blob
    ├── 01dde5d303229d1e2a72a9a0f37c154dbb057d0f.nq.gz
    ├── 029c6db562d749878243df5cf12c04731feeca8c.nq.gz
    ├── 02c3241b79b29f358f29531a434974f1dc014405.nq.gz
    ├── 02c44d06f19ccc72e9e58b85683f9a5210fe5abd.nq.gz
    ├── 02f4679cbb55a854419b18af322d93db1b295312.nq.gz
    ├── 02fbc3bb17e6ed3ba11cb38a00f932f75b0e0a50.nq.gz
    ├── 039355eec4a31459f7e5bb9187206ef5bfd0e5ab.nq.gz
    ├── 040e81b9d8a13a7bacad82cb542dde35f5c95bed.nq.gz
    ├── 0428a512944932b8158b3be2b43f61751edc1d70.nq.gz
    ├── 04e525940aa40ea48215e9710ff6ae19e078633b.nq.gz
    ├── 053dd117e287c93bb65b1f45124df564de1b0c84.nq.gz
    ├── 0571dd3913fa0499d0b6b8467707dd4059191d02.nq.gz
    ├── 05fc712928a8326ac71f8e90be25286bfc3676e5.nq.gz
    ├── 0631c99cd76ba513711d69d8e89b4d6ce96b3eeb.nq.gz
    ├── 07262074e021b047b4b216135c3f4cf34d477588.nq.gz
    ├── 07ace1179f7888170ad340af9a967b65e76a572d.nq.gz
    ├── 07d151100c05d633ffb4012e08b07b4e2278aad0.nq.gz
    ├── 07d30a65c65af715c034ea1b270418d65baa26aa.nq.gz
    ├── 07f6fead0135687cae6a8d2962713164bf5812aa.nq.gz
    ├── 08b6991571d8be70f429f53474d0af0876549ba0.nq.gz
    ├── 090b26a744f23a20bbd993fa55e53fe302c32d08.nq.gz
    ├── 0966e402f139b3f389d4a7d190c78da8d9bf1278.nq.gz
    ├── 0a0a7540c78f406fbf2b5bd89545fd84a4acc6d7.nq.gz
    ├── 0a0e2954f4aeaf098bc607c238264fc8fd87cfe7.nq.gz
    ├── 0ab7e4b4bc700e83b8afe569713fba0a4c3b1003.nq.gz
    ├── 0c02eb925c9a5578d5bd7b04be7566c9d59065cd.nq.gz
    ├── 0c6794bc30d8fe786c94873f27c53d7727f3ec27.nq.gz
    ├── 0d5344467d6b5484de9eb458cdd1141b0b3bda22.nq.gz
    ├── 0d54382556ae1319c9b5988ce3e0fe6089d9d222.nq.gz
    ├── 0d98588203881862523e90deac6050776c98231d.nq.gz
    ├── 0e5eed3b5e6f5a1b66bd2fa0d5a361e34e496b7a.nq.gz
    ├── 0e78d45958e92a78fa3170820451763cc5b608d8.nq.gz
    ├── 0e8f210aa914d69fd642f43808128118350514d2.nq.gz
    ├── 0f4d1c71bb69aea8eb4865b31baf59f0a8d53fa9.nq.gz
    ├── 0fe0761f1a5bd1aaaa4e6e71299939fcb06efac5.nq.gz
    ├── 102af87137381554016d9fede240bda8254e9dcb.nq.gz
    ├── 109a8bf77e46617f6b0f34d4b2782fa7a2d79cd3.nq.gz
    ├── 10beb94e98eade865dc1a805ab56c4818b645bbf.nq.gz
    ├── 10d7816380f8da55a84ed06dec15e04b0fec13b4.nq.gz
    ├── 111197aff31ba57e03efe2427c693cf54f586b00.nq.gz
    ├── 1122af868aea437feab752be6539c02ebd75cc51.nq.gz
    ├── 11d8cd0807c4a71051bc41b75bf7af57f33a6430.nq.gz
    ├── 122dcb4e16fdc9dc1023afb97432c45f26b60270.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 126fc9b7dc324692efb69c211c2e1ba1d7f3e0c5.nq.gz
    ├── 1290788f5afc75d6e2573035ae73686df1163e9c.nq.gz
    ├── 12a162b61a5895726ad1dbe59f0a2c87b4770f1e.nq.gz
    ├── 12d6ec0a298f00e6b82d0ab9ffbc0687bcfc2903.nq.gz
    ├── 131e67bc78d54d936d17acb81190f9bcc298e3ad.nq.gz
    ├── 134368834172627a3a06605aad7c802cc1f5f9af.nq.gz
    ├── 13db2b38c1b4318b3c681ecf864d23340c14ce88.nq.gz
    ├── 1408af28b1396a0631240765d080b27179fd1d53.nq.gz
    ├── 144cf63969cda48c7b4c9056962a23ec63c742d4.nq.gz
    ├── 14b8a8d7890f178412f57d578addb308bc97ee26.nq.gz
    ├── 152c23726da318ca41ec0aa4676abd49950634d7.nq.gz
    ├── 1672acf68e964323115314faba584526ffdf5eb6.nq.gz
    ├── 1682ae8073cda04526c483bac76a83e456b45141.nq.gz
    ├── 16cae0662e48f605db54cdf86ba1008dba5a4003.nq.gz
    ├── 177f5ff5572b1c61b9696696b2132df75b15e77b.nq.gz
    ├── 17b0d8ace81b7b3596ee1d9b3018a14a6e5d7540.nq.gz
    ├── 17ffa8446464b619a0d8ca0cea9c302020f084cc.nq.gz
    ├── 1830eff6cb330586aad93e8684d749202643737c.nq.gz
    ├── 1968cb4413c238b96cfb1320ec1bec28b0793814.nq.gz
    ├── 1a2f5efaeddd618e2aad19af82bed415b8a25d47.nq.gz
    ├── 1a39552777649745723dcda6ac84a1b8f91041bf.nq.gz
    ├── 1a7f93b6ea4563594c08b1f904c53e010700e25e.nq.gz
    ├── 1ab3d955415c5b4eefe1f6a8df2774d352125ec0.nq.gz
    ├── 1b466a3d7e7bf488489b5dd98a3a4f69c07ad220.nq.gz
    ├── 1d04e6df6263d85cffdd15bb46e9752846267ce7.nq.gz
    ├── 1d35ece5d12be5f86f2caf2abcb2c059f4ccc4ee.nq.gz
    ├── 1d3a1c47ce0e2dbc43db70f0e16e2659704e135d.nq.gz
    ├── 1dd5a19a1778c9d6a7cc2035d1d8c20ea5c563de.nq.gz
    ├── 1f1c37171d6f7c07741b94c6306b9b72c6a71fab.nq.gz
    ├── 1f8865afbd93e9ab684d19badf991fbe9cfd580c.nq.gz
    ├── 1fb0890b88e0bcd8213f19e7bb60809ffe947355.nq.gz
    ├── 1fbe10d19d61a8837adfd0c02c5c4c3c5cfc384e.nq.gz
    ├── 2049b29fdc9cb5bf1d8e44ff09bd5f20c72b988f.nq.gz
    ├── 20790a0a2ac2a2baa48bb72f62fcb60a8e51ac51.nq.gz
    ├── 211f0dfdb46f2ab2f08ffc73dde5e57087d5d69b.nq.gz
    ├── 21a3c1a51f43c840dab2650599a5d31d6019d361.nq.gz
    ├── 21fac3fe7dfc54dd743c709a6a47471791ee7fba.nq.gz
    ├── 221e2e2fa670dd0d56e03cd88d7f7e068a66bd48.nq.gz
    ├── 223b22be3dc78678f4e0bf6c5d086d01b30277b3.nq.gz
    ├── 2255db811d622270e0f94a51f4d78d350b06295d.nq.gz
    ├── 22623484ce57a9201132158cbc07dec7aa3ec09b.nq.gz
    ├── 229b2ebbbc901935f951a93de7dea83f4d0524b5.nq.gz
    ├── 2432563056a460c59d6e615968df456da3ec49cd.nq.gz
    ├── 2511b2ee9bd417aad2d3a898a84c023eeadd6327.nq.gz
    ├── 2523680617f46a4cdab689cb29265994e02f34cf.nq.gz
    ├── 266082ae687e7de6d6d9899d61436b423e9ef3cb.nq.gz
    ├── 26c79b243f3689d334a3b39544055d2c12484608.nq.gz
    ├── 26d1dfc24df0f23a63c225b06a190801125483e1.nq.gz
    ├── 26f6b001b6c63c3b8bb75183a0cf98f3f6aa7be1.nq.gz
    ├── 284225847dbf96b444931361388a12129d3e87da.nq.gz
    ├── 28c54be17a2634689239e446e13c88545b80dd99.nq.gz
    ├── 28da7a845cb054b4e8093f5dbe8f81d27694adff.nq.gz
    ├── 29f93f43225598ecd0210ad92483e7f5d497bc17.nq.gz
    ├── 2a6aa596ba0e59b43aeea923b3eac49b010751ba.nq.gz
    ├── 2a8cf599bc3422f6d8d27d4c3a24912ff9fa6f08.nq.gz
    ├── 2a91426d0f815610bad3b2272f3826d672966d13.nq.gz
    ├── 2ad2314c887b565a76fe466eac4c36811c2bf8e4.nq.gz
    ├── 2b38b4a4b25fbfed7d835d6369c12ebb1ea9c411.nq.gz
    ├── 2c1391875164e99be58cb32cf2138d3559942edc.nq.gz
    ├── 2cb7d0e6f11585fd7fbe5b4053f85a9dc63b779f.nq.gz
    ├── 2d57bbc9ebda991ab2cad05c3a73fc6dd935b784.nq.gz
    ├── 2d5c9eb30f87b04869ed0d59b34c8ad163b42f96.nq.gz
    ├── 2dad7d7b16b6238710bdf979ece84a8cc10764c3.nq.gz
    ├── 2db90fc1b97817d3d3810ed8ae430e127db23542.nq.gz
    ├── 2e5c272cab559315fcdf3d2f1841875fd1761fba.nq.gz
    ├── 2ed7fdde0e84f730cbf48e1539b9c843a469ef0b.nq.gz
    ├── 2f2ee59eff897f27c8b7c49a1fae09fd2b41ef11.nq.gz
    └── 2f42b5daf51e9ad66a50af0e46731d40d0f79973.nq.gz

65 directories, 200 files
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
