# Repolex Knowledge Graph of huggingface/huggingface_hub

RDF knowledge graph data for [huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub), parsed by [repolex](https://repolex.ai).

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
lexq download huggingface/huggingface_hub
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 23ac74fafdbac7a96fe9395da3a17ac23df81ff8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 23ac74fafdbac7a96fe9395da3a17ac23df81ff8.nq.gz
│   └── repolex
│       └── 23ac74fafdbac7a96fe9395da3a17ac23df81ff8
│           └── chunk-001.nq.gz
└── blob
    ├── 001c3fe8b2f37a64e890888ca3d521c10ec8f03b.nq.gz
    ├── 0095c26700b0d9ef636bee882b86a467e403af67.nq.gz
    ├── 00d275ed00c711577c91e209f1a27ea48a955083.nq.gz
    ├── 00d4c9b671a656e5576a471c3026853cd809e62c.nq.gz
    ├── 019ec26f2d72898813afef7bea179c0e60246bb6.nq.gz
    ├── 01e90b09eee694eb1f090bb19dd98db706f22c6f.nq.gz
    ├── 02656e346a7adea5eefd1a1db7e9995b5aa675c5.nq.gz
    ├── 049394af1dc15925d01de3f4c87eee33c3f6a161.nq.gz
    ├── 049865a9f0b0f4a51734173b5e0e443c5f2e16d4.nq.gz
    ├── 04e66c8f2d0fab3826bb15e58805ee091232ed09.nq.gz
    ├── 0501421d64accb3f6c52e84548bd84841949142a.nq.gz
    ├── 05db2d705b57176ffdf8e59407472ecea36abd07.nq.gz
    ├── 067d427681ca99f6d87e4e285b94f4d43d966548.nq.gz
    ├── 079aff5d28836b79934afccdb10f227b929e62d7.nq.gz
    ├── 0853cd561c19adfe342702508d273e19291ba005.nq.gz
    ├── 097a18d6462f48b4173801560d8cc0f403959bff.nq.gz
    ├── 097c798fa72db767d601b9cf6800750ead3fe0fa.nq.gz
    ├── 0a8ebf284cdb56692f4fd5aa5c165b7afbf4e802.nq.gz
    ├── 0ab91101cf25c3d942db38b29c6343e67a258d5a.nq.gz
    ├── 0acb8f04fe8dd09edcc5199b6e2649671d7b3418.nq.gz
    ├── 0bb198932e041992960a6ee36ea83be8587a1b29.nq.gz
    ├── 0c43f7f13e82c06f973cf2d925560b6a501300da.nq.gz
    ├── 0c5a9d55a81fab6fc71e1226e7776a7a68ee688f.nq.gz
    ├── 0cafd4e7b30906e7add6f33bc130818e8ec3ce87.nq.gz
    ├── 0d473338cc14749417d085c64f7f181c92fee298.nq.gz
    ├── 0d5a18ebdd1eb3b066d988dd7f2fcb079d1d671b.nq.gz
    ├── 0e7e2fcbbfc4650cacaf22f96a11b407863b32e5.nq.gz
    ├── 0e936bc809284cfcdfdca4ada46f5cf7437246e3.nq.gz
    ├── 0ebb9a9bc667bdb0d2afd7bb8e482fc18f6634d7.nq.gz
    ├── 0ed0c7cf4860758cd185abcdeb8576997e8e12e5.nq.gz
    ├── 10e22c3d1eb83dbb52c4a633fb66f19b3f35d8e7.nq.gz
    ├── 1265c1efef0064fbb87343297db90fffea36dffd.nq.gz
    ├── 12b00332b3b8ac4d7d4557cfb7e65f782d2ce5f4.nq.gz
    ├── 13fb33262962a108d12b589cb81e474f1562d11e.nq.gz
    ├── 1430c20a181aa9b52f7ba3aaee93e8f8045712d6.nq.gz
    ├── 146e85ba8f022fa61db38ce2ec1a88d244c26ca6.nq.gz
    ├── 15a3b10c0dbb96913a398408388e652a4ef1317f.nq.gz
    ├── 15bdd320fc91e851564c3fdc4c958c02218091e8.nq.gz
    ├── 15fe3ad3b83d912713ae660b4552ba4a16669d98.nq.gz
    ├── 16f2f02428dd5c2ce6437534af0397801bda45c5.nq.gz
    ├── 17818d1858c05e6e3483ae3d4d2cae9284a2db70.nq.gz
    ├── 17f4c561b33ede51b228fef657254116fb29882c.nq.gz
    ├── 18cdb9c02417e48dea9ceb4e24b37e043e9eeeac.nq.gz
    ├── 1944c08f485909f9a1cfbb7c7151cb9550f2dddd.nq.gz
    ├── 19e00669609ff64b9b1a673046b34796441d0e94.nq.gz
    ├── 1affc7861e0d5a0cb216bc0f873f8aec2ddc26c9.nq.gz
    ├── 1b7a8080c235831b0a29f989d7dc2042d60c28d7.nq.gz
    ├── 1bc5b21478611c1c786a0e78bdfca7da8e1ab64f.nq.gz
    ├── 1c6d3993f6886298b12f29f249e09bf11b4cd63a.nq.gz
    ├── 1d0bc95a5cb36f682eebb1094c8e94f103c21009.nq.gz
    ├── 1d635187d7ed2f92eb239dc1e4ee4754394dad4c.nq.gz
    ├── 1db05f184aa51d6aba32bd35a773d2951010e2e5.nq.gz
    ├── 1e790b5eb1b40710072ef5fc2597b9e6c3325355.nq.gz
    ├── 1eb8250d20f1c9df6afaf15a62035ddce459b83e.nq.gz
    ├── 1f11b0980bf11fe378b88b308f8f3ff6c06f9797.nq.gz
    ├── 1f7004c185492d52fe692a3e021a63ae72e41e0b.nq.gz
    ├── 1faae9bc9843ff245be37dbd9d80853392400eda.nq.gz
    ├── 1fc1cd8da82b8b57f1f31ac352b46a2b1e89c1d1.nq.gz
    ├── 1fdefdde28317aec68e682b07c06af453d8f52fe.nq.gz
    ├── 20b5e16b409cf1241f18c3f373ce5a20a72968f9.nq.gz
    ├── 20fa4a3885115cab968c60a297ad4a108baf1295.nq.gz
    ├── 223ff8ca31c0a6fc599e40035a616a60d34b8fba.nq.gz
    ├── 2349c4444ea31ea8d9804d21df98ae365652ae02.nq.gz
    ├── 23f2828bbfebda0a633b4b3c6883432e4a534c79.nq.gz
    ├── 24405ec4fa1d1ebf802813bc1af3ce2840ef2f9c.nq.gz
    ├── 24a5238ab6b33ea13df79a1ea197b4f07b39c1ec.nq.gz
    ├── 25741662e393d331355458e4ae1f0cbf17a33fe4.nq.gz
    ├── 259c976c40f677514fce0ed42b26a6b6d838d07d.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 264af6fba5f5f56547312f90b0a3364ef344217a.nq.gz
    ├── 272ddaa8dd802bb8287c7787cae32438d532c78e.nq.gz
    ├── 27833f28e3e2030680fb72b95a547521bc08831b.nq.gz
    ├── 27c70c7e2b201fea407abe166feb7c3cc4a28fff.nq.gz
    ├── 27e96cb4911e0ae520d68596f3dd5f2c4a854ea7.nq.gz
    ├── 282b627b54489751bb5e8098f87881e52eda637a.nq.gz
    ├── 285139fd694390cc0d041935577f807fab8c61f9.nq.gz
    ├── 288f4b08b9428980e99ca06703442eab62fad277.nq.gz
    ├── 292aec19ab55593b21f61bca78a0ef1553e40e17.nq.gz
    ├── 2a6b37c61bc33869b67437465eb6e01f0acca07a.nq.gz
    ├── 2ba4a6349a8de1c565263ec73d235d36f88b68cf.nq.gz
    ├── 2c7a4da7026e34b6bdadcaa3adddf8322b9ccce6.nq.gz
    ├── 2d60ea27eedbfe28096435c84e4002c0d9a64bc6.nq.gz
    ├── 2e155c7f63fd046c94589ec8bb7762b1bb798b2b.nq.gz
    ├── 2e6500ed46eeaba7fcb147b41a2dab7f7befc690.nq.gz
    ├── 2ee819be6af745cccd7aea24d7894977f070a385.nq.gz
    ├── 2f8c029f8e542837567ec2723e50d1490be4891b.nq.gz
    ├── 302ab5af4ef322214ae2c2e7aef8d710db68e8e9.nq.gz
    ├── 303c66babf87e10e33c498d0a2380b50381f5065.nq.gz
    ├── 307b93a7729b7ddba8be337cc9129d24590e583f.nq.gz
    ├── 318f933c4d39d6c226a29dcea7fe5cae4ba53098.nq.gz
    ├── 319207878f2e8250a1977c2658f8f39e0f2898cc.nq.gz
    ├── 320f098ab08148308f00a9bbaabea141de0545f2.nq.gz
    ├── 335af1ce094436fb1677278e40834af2b90f38eb.nq.gz
    ├── 33944e737375cf9ff2ba81b97d2feb5eb8cf163f.nq.gz
    ├── 33aec9ad7e3f4e22a16cdb535317e77b42fc05ed.nq.gz
    ├── 33b474209283527402367a10cd4e6c16e0eed54a.nq.gz
    ├── 34141eba09123c06fbca55c929a19a0264e5788e.nq.gz
    ├── 341f8f9e1280cda51050d8865d35be1c877319bc.nq.gz
    ├── 3482ae6eac59a60a085693b1750ee058759bae35.nq.gz
    ├── 3496f82349c09bfcb55f6dc6988d9a29edd36800.nq.gz
    ├── 34f12e11f373090d351911fc8cb1b0bde5296208.nq.gz
    ├── 35efbfc92375606d8dd56b57b7fdd3addb97a044.nq.gz
    ├── 3810fc594af5cf0712cb0cb0db077383220b175a.nq.gz
    ├── 38546c6d34db786c62861e1706f747a21b7012bf.nq.gz
    ├── 3870fcddeb5e40f3dccee5d34a6c7a6076f28486.nq.gz
    ├── 388d3cdaa0c46ac8fbc507947fd14a33efc80eae.nq.gz
    ├── 395a733756c9b5ed8ed868c8f3e95684395de7f7.nq.gz
    ├── 39f5f09c118b8256aabfedd7667e24740f674a5b.nq.gz
    ├── 3a3cd2284b222985f58fdc9bdb11a18281956ff0.nq.gz
    ├── 3a78c08716b34b5c4be33d5ac60b59d0d37bbacc.nq.gz
    ├── 3a9bf25f449991d9213105da9cc93fc41780123b.nq.gz
    ├── 3aafdf148135397556b4bb762862377eafdafd14.nq.gz
    ├── 3b7bec4826815d1151f0447765ff74531c639200.nq.gz
    ├── 3c8b2b33f3ed64c409647a41695f73cbff4147cb.nq.gz
    ├── 3c9a14a0410011e6ba79d525ff8e89c6dc11e93e.nq.gz
    ├── 3caab0f5ed2c84dfd7896979cbc50a29d38a940c.nq.gz
    ├── 3cb6c04877f6a6d3c23ebe403d21a7caec2da8a3.nq.gz
    ├── 3d6847a3e0ebef6c87c04f6b5701021bf12f7834.nq.gz
    ├── 3d6e12fd45cb48723dc6c5994a8a44c26741a427.nq.gz
    ├── 3d9856c920f6d2eca2bb14b9678584419347c12e.nq.gz
    ├── 3f3c2a9c8896213e8ef9ceabdfa3de1bdf1c0a2e.nq.gz
    ├── 3f883a014e291c4a7cafc9c2e2d7abb7e3e66101.nq.gz
    ├── 40e53ab016d3a6f2098d26eadab9cf51805c31b1.nq.gz
    ├── 413fac30fdc6238972767066701308600df199d7.nq.gz
    ├── 4247443e36a41af0ae55b4e1bdb5bcbbfe3fb52d.nq.gz
    ├── 429d49c2d6a5258445875039e4492c4efd05dce3.nq.gz
    ├── 42a21568c9c652eb307cf2bd44ee9aa06ab4df7b.nq.gz
    ├── 42b03a841b793fd4cb301bf51695bd35054a6af2.nq.gz
    ├── 444ac16c3ffb414b868663c9df4f28e61fc37685.nq.gz
    ├── 44e228871f9ee1720dad476f5dc41a0a3ba8ce0a.nq.gz
    ├── 4531cc6d6758f3df8518397f902f8747dbcf058c.nq.gz
    ├── 455e5e49abeb8bf9536f515275ce5e181f928a0b.nq.gz
    ├── 46ccaf0028e48d087056ecd51b2039c115353657.nq.gz
    ├── 46ec8fce3403d0b13569763f1afa8760f68f33e2.nq.gz
    ├── 472a452d35888f0c44b7ab4fea433651f6450370.nq.gz
    ├── 47e672a57639a3b577bb03237acf004c8000d134.nq.gz
    ├── 4833b82d5471ae8c90f4c8a7971e59f9f5b7ec53.nq.gz
    ├── 4864c85c80a4b6d062f25b99de4b7b903de50bef.nq.gz
    ├── 48807ba0d82d2c631ea8cf87d48622a04df0f148.nq.gz
    ├── 4995bd5d3543b871cc6215ccc8b990966c5d06fc.nq.gz
    ├── 49d088214505b9604964ab142e7f8a5b38ccd5ef.nq.gz
    ├── 4a4fd8456c3bbadbf74704820370b5be57f8db76.nq.gz
    ├── 4cb8d6e418c76accd1ecd61158b4bdd265e12f71.nq.gz
    ├── 4db6c7e551af34d6a6d0863bbc7cce9f2bf2a722.nq.gz
    ├── 4dbdd3cfaaef145f6847c2a5c8ff5b5746275897.nq.gz
    ├── 4dbf3cf55c67beebf4e6959ef180b30e29341a7c.nq.gz
    ├── 4ee1925b6912932b777340c937927fbd01cb2181.nq.gz
    ├── 4f2c0ebce070bbde4900e919a3aca7cfc331e747.nq.gz
    ├── 4f473ed106c7d168784ae8e96db18f46237d065e.nq.gz
    ├── 4f8fe69c2e2e8c73cedd098df4c1850e2a5dbc51.nq.gz
    ├── 502b22658b44d2221b535cbd943348bb93213245.nq.gz
    ├── 5095044d0036cd1cad28c3682c83bae789e659a8.nq.gz
    ├── 515e469cf5873284efceb1267ad54bd1f75fbf11.nq.gz
    ├── 51b160123946ed038de5532de7452eb7bef0a205.nq.gz
    ├── 51d14b1f6d7f9d5ccc1d185805f52d28c90ad495.nq.gz
    ├── 51d33d76acb06444a8dc2417d3a8a6de50fa32dd.nq.gz
    ├── 53785d8fe398f7ec45d2b931f43baebaa679de54.nq.gz
    ├── 53aaf9303a47e04fc06542587f7a8f228cb99305.nq.gz
    ├── 5457f04111bd90a04cc0812de3f94d3968ae392f.nq.gz
    ├── 5601a6335faf41d968e4a6c341887174322c7a90.nq.gz
    ├── 56328b419c868452206c210fb45e5813c0133ed4.nq.gz
    ├── 5659521ca6d52aef9f0dbce495635c7c8843fc3f.nq.gz
    ├── 5813707f90982c6b88c9173c023120a100df4afb.nq.gz
    ├── 5857fa4df88f6fd22c9821ae18a628a81fd8981a.nq.gz
    ├── 592092f64ab564946d7f28470bfd3dcf14177fed.nq.gz
    ├── 59b998ea711c36f45526503668727b8da26abcac.nq.gz
    ├── 59ed8110b28f4891d67e754fdfbfa47a26f85be1.nq.gz
    ├── 5bd733cd6db9cd1b4b0045709c8bdfcfa7b0c069.nq.gz
    ├── 5e6ee3c0d6f1fd0f7592dde3ebae69e77d7de3b2.nq.gz
    ├── 5ea9d56b46d278a268c1699ebade797227a35c96.nq.gz
    ├── 60690016cc3c9a03ccbf554041370202020c5ac2.nq.gz
    ├── 6255342454144b262ea48102fa7f20caec656a62.nq.gz
    ├── 62d7bf1d0d4395fb980bc4d17af028182d0e8361.nq.gz
    ├── 63f9047346c358b265679178612621c52f2b999c.nq.gz
    ├── 66161daf18af8e49c8d707d963ceae5d3ddc3187.nq.gz
    ├── 67b60a98288c1016f750e143766023c7c1a1be57.nq.gz
    ├── 67dd7c28b3cddd21d495ada70b7689a098accfd6.nq.gz
    ├── 67e8ac807e7b157d849ef3d372a0cac76aab231d.nq.gz
    ├── 67ec4cab0df98fec461e2309834d8d81a2408bcd.nq.gz
    ├── 6ab7c14d8ab032c2e9bf24c835520182cb1b5e5f.nq.gz
    ├── 6afd8a705c2e39c3cf056055eeb2211a0b5b11ea.nq.gz
    ├── 6bc3ac1e2a4b3a597bcfd50a431c4682a140fa73.nq.gz
    ├── 6c2a62016124c7b3814c840a0a6d9460e7b9db1f.nq.gz
    ├── 6c4383952bc8b1ee6e556cb4b324daaa22377044.nq.gz
    ├── 6c55ebf218ca3314993aacd7eaa8c1910b5ab63e.nq.gz
    ├── 6c6a7a177a842ecca96f3db3f6202cbdc5718283.nq.gz
    ├── 6cb9fff641fd4ed2d8e797e59ae7b5f21f94c838.nq.gz
    ├── 6d94537901fe769ee5eeb9cae112b263099f5fab.nq.gz
    ├── 6dbd0fd3ef7d5c1344b0ae74703f6fda62314a99.nq.gz
    ├── 705fdcc38bd9024967223bcf6f6c7dee7c3d1280.nq.gz
    ├── 7105b5870229e27e1aeef0920ba23c6c091ba6c2.nq.gz
    ├── 71262aa1e83c36622889bf75ee6e936253cd5711.nq.gz
    ├── 7289bac58e8ce2e816d6009d6e29295d80b960dd.nq.gz
    ├── 73dc1b544cb6f5c05ba26edf075db2e9e9e4ae03.nq.gz
    ├── 7459ab6d384cfb2637d1deeb386da4f692a69175.nq.gz
    ├── 752b3a227b28cec759e7ef1107ef77b4e9964165.nq.gz
    └── 75fac898fdafe945746bf7be0d6bc70ec03ec0e7.nq.gz

8 directories, 200 files
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

[huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
