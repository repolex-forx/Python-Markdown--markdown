# Repolex Knowledge Graph of Python-Markdown/markdown

RDF knowledge graph data for [Python-Markdown/markdown](https://github.com/Python-Markdown/markdown), parsed by [repolex](https://repolex.ai).

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
lexq download Python-Markdown/markdown
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13
│   │   │   └── chunk-001.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│   │   │   └── chunk-001.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│   │   │   └── chunk-001.nq.gz
│   │   └── f99f176d248d0e472b0960d06a7aaf649bb1da25
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6.nq.gz
│   │   └── f99f176d248d0e472b0960d06a7aaf649bb1da25.nq.gz
│   └── repolex
│       ├── 08dacae618775831243f6bbab47d9be590d511f2
│       │   └── chunk-001.nq.gz
│       ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│       │   └── chunk-001.nq.gz
│       ├── 2932f183921943687ca3d72b3908a937bd495d24
│       │   └── chunk-001.nq.gz
│       ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│       │   └── chunk-001.nq.gz
│       ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│       │   └── chunk-001.nq.gz
│       ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│       │   └── chunk-001.nq.gz
│       ├── be1c2839dd587a858f91c710e56667cba9f5329d
│       │   └── chunk-001.nq.gz
│       ├── d9c8431e404d614812e39a11109afbe9981bba13
│       │   └── chunk-001.nq.gz
│       ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│       │   └── chunk-001.nq.gz
│       ├── e524b8fe938738cb4492411a34cce89051cb9695
│       │   └── chunk-001.nq.gz
│       ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│       │   └── chunk-001.nq.gz
│       ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│       │   └── chunk-001.nq.gz
│       └── f99f176d248d0e472b0960d06a7aaf649bb1da25
│           └── chunk-001.nq.gz
└── blob
    ├── 00445ecad4bced3b453913aef08d54032be4d93b.nq.gz
    ├── 00c7b5e1b2bdcfd7c87b0f80df924728213e9a53.nq.gz
    ├── 018400824f07bacccd0f30cc0449920fb424bcdc.nq.gz
    ├── 01c118fa68b886bb4b699ae5fbb473f2a466c8a3.nq.gz
    ├── 01c2316d2ba6d0e2c0e3679a43794ccfc33bdc3a.nq.gz
    ├── 01fcd4eb2cfdf6c52bfa6ea4c5036747102bebd7.nq.gz
    ├── 0228ddf020907a733e5f15c189474fdd2176b55b.nq.gz
    ├── 02d86edd31a0f7dfca8870e70680666db7060645.nq.gz
    ├── 0358551706acb01da9a18c389bdd13c1ca01401c.nq.gz
    ├── 0388070ac5efb5a1a45baeac51406031884d1acc.nq.gz
    ├── 03ff4e9e213aa6dd68f222cde1415071479160d8.nq.gz
    ├── 0425971848ad602f0330e932fbc2219d66d11586.nq.gz
    ├── 04587560d9a76677ff8cf64a5b6e1112de1c08dc.nq.gz
    ├── 047996acf07ebff5685aa709f98c01b3e88fa0f3.nq.gz
    ├── 05d808252f83a7242193f77bf3a3175b23984726.nq.gz
    ├── 05fde239e66dd89e89dac1efb40c7100a7a94888.nq.gz
    ├── 0649870476a456bf13e254a6c2af6a4a2ad431a6.nq.gz
    ├── 06a01d763e0338b973411f7c84c19867ce0d8947.nq.gz
    ├── 06a51078256a4ab38d5c6bba38bb467a8a83ad59.nq.gz
    ├── 070881731e5b86e19788c5af449c75c0665dd684.nq.gz
    ├── 070c4cce0fdb0379360b9e337b618704c32db0e8.nq.gz
    ├── 070fa27fc81b3105f029418ff20b6896c579b38a.nq.gz
    ├── 0756514d9d54242586dacc8fdf25595721c0fe71.nq.gz
    ├── 0872aaaf5dfba614b12b9a95aa35c19bbb459e1a.nq.gz
    ├── 08fb8ef848397987acbd41de305ed5eac09a65ac.nq.gz
    ├── 093abb01442dca16e88064ec88d5a7a149a340b7.nq.gz
    ├── 095f17d26630ec79406594c8f6650bf5314a9474.nq.gz
    ├── 09b8cf619f6e16198baa1a51670f499415cf26af.nq.gz
    ├── 09dd523c1e9185035c5dfe0eda9e70657fee0d22.nq.gz
    ├── 0a41c4f7667b3d9eb42c3eb2ebd7120123a3a17c.nq.gz
    ├── 0b0af424587fc21738eb626bf434dfbc84698ca7.nq.gz
    ├── 0bd129cd1fd95752bce38931960ebf8a4ca22dc6.nq.gz
    ├── 0c317d1bb9076d655b2287d7760175f7fa72eab0.nq.gz
    ├── 0ce7772a73ac98772313fd2bd1b881f6d467ee95.nq.gz
    ├── 0e56161308f69fd7a3b3375ca4d0c1c51dd0a463.nq.gz
    ├── 0e626b977c19c9e78a31807b045c59e50c26abde.nq.gz
    ├── 0e89d406ffe2526544dccacd132fc4a2f7e7eaf2.nq.gz
    ├── 0e9527f9311d129ac9ae5bca7666f37c3dfcfb59.nq.gz
    ├── 0f63cdd36ab2f06222a18380bfe7ab5e47c3bfcf.nq.gz
    ├── 0f897b2e37b59e9c402ef946427feb8bdb71a8d2.nq.gz
    ├── 10a2d3337402c67cc85d024dd496bcc98ffb8e35.nq.gz
    ├── 10dee11848e85a0b528f6b8b5ed30cf477bc89ea.nq.gz
    ├── 114227da5ca6f747bd65864292ee5a2d710b88f2.nq.gz
    ├── 11cb5adc90dca19a2f2640670278561ed76eae3a.nq.gz
    ├── 12856652773c6a08727e5221c7cab3dae818b72d.nq.gz
    ├── 12e5c953762efce8ffc6dada7728c407c0d4a21b.nq.gz
    ├── 1305c54766ccd84eb4beb39b4a4e5abd51f9ca5e.nq.gz
    ├── 13b3c35f8dd5a6e24ce89174c9a1e395e92b1017.nq.gz
    ├── 13cdea5b1e0794b1bbf9b405cb4457d8b78f5bcd.nq.gz
    ├── 13ecf7c2287842532b662dbf5540caa15f8ec725.nq.gz
    ├── 147d3b93c018c3256160301f18945d9121acdb95.nq.gz
    ├── 14aa2dc272d0a056c71049fb4ff80d54d36f9adb.nq.gz
    ├── 14ec034aac7e8419a72210ddaa4c3fb9a24f6d81.nq.gz
    ├── 1594bda27b4130726fd43d0aa1f3ede6487d1905.nq.gz
    ├── 16447a010b1601e51952da95d39da8f56ea37f4b.nq.gz
    ├── 165bbe346a3cf6dfa7525b0457d34930635ffe6f.nq.gz
    ├── 16fe4027ca3e2727c6d652a41dc37ebf3aaedf72.nq.gz
    ├── 17549f031fd7fc27232d2660c7fdda41a7e849c3.nq.gz
    ├── 177df1ee416ccaa7779f5d969645c4337edc0034.nq.gz
    ├── 18dc114582307427c4ed972a473f2cda7747f681.nq.gz
    ├── 19028bb3e731ec3197e02b633154344c7a971f56.nq.gz
    ├── 1941ce288c17072db17c168d86f9ba6b841f5ae8.nq.gz
    ├── 19aa92b8718f05cdb98f425b7859765cf338aecc.nq.gz
    ├── 19b9d526d148220666ee79c832e8ad29132ec1f6.nq.gz
    ├── 19f4cf1128a167a8607a3fd669004178223308f1.nq.gz
    ├── 1a0ae12c2ad23ff0cb5052fe95e6d7540618dab9.nq.gz
    ├── 1a1de345e0a03fd4ceff91becd6e464a38dff575.nq.gz
    ├── 1a3544fb35694383b5d03ad1b412dad9b6b3d2e3.nq.gz
    ├── 1a38be6e6a4c724bcc4e0caa8c10161b937b8b20.nq.gz
    ├── 1bdca393dc0e74dfd476004583ed9460a2026774.nq.gz
    ├── 1c7185b2db7a6b2addc76ae9b573959d6708e02a.nq.gz
    ├── 1cf18bb4330846eba97ce76e340245fdde15a5bd.nq.gz
    ├── 1db47dc59060645b24a90c8463bee7ccf6062386.nq.gz
    ├── 1dbf404a04dcc1d9d53bdf3353c5623ab406ac81.nq.gz
    ├── 1ded18d6305dec16e09d860fac8a7a62967fd3e1.nq.gz
    ├── 1df68854157cb6b6f1de04614828a6a6902f87ab.nq.gz
    ├── 1eae842b8ba4a531e2815eda7d27263d199db92f.nq.gz
    ├── 1eb54502db5611c47a8b729444dc959430a9654b.nq.gz
    ├── 1ee6029737580073b7123c37ae1aa4683e0e7972.nq.gz
    ├── 1f4ab23901e34861977a8e617cdf618bd6c21295.nq.gz
    ├── 1f80c7ea6cda4317b579f74144436208afb299c6.nq.gz
    ├── 1fa82189979d8e18a1f2fe176b01a208f7d5a38f.nq.gz
    ├── 2094203aee6eb93d11d9f0029ac26c82b3b6d896.nq.gz
    ├── 20e9afa74cfbd546c6168b7d4b40dc4b42bde236.nq.gz
    ├── 20ee6d7c91f93024052ca17dea92f67607341126.nq.gz
    ├── 210933ecee10f02d1457929c06e159e0b050e753.nq.gz
    ├── 21388762e7e213d05f12d0449228ff79fa9babe7.nq.gz
    ├── 21fceacecf984a27650c762e8e566be819c37b32.nq.gz
    ├── 22b949834b84ca83ba580a641cbd4a5c5859bf75.nq.gz
    ├── 230ba3435605ea5375ccc205254f8444c7df6c78.nq.gz
    ├── 23d56034a8a40d264109da4aa61059381a66e93d.nq.gz
    ├── 241bb6d40e06a46b6b055c5e90f535557ec192a8.nq.gz
    ├── 2424dbc842a2dd41531f575e7d6a832936b7fffe.nq.gz
    ├── 246b60d1cfd167562355bc5f51bff2d75384172a.nq.gz
    ├── 24de5d95895c2750c573954f5c5356339d669a64.nq.gz
    ├── 25530d60cba2546282f0c59505baea8c2a193d1b.nq.gz
    ├── 259c47f746972bc5f34fe8ea47825b6f1bca67d3.nq.gz
    ├── 259df6336f8829b27649a6f19058646d662a9213.nq.gz
    ├── 25abb16eda498751dce83173994da9546877acfc.nq.gz
    ├── 26513242c0caecba0831c4d13e363ac1d97a5f98.nq.gz
    ├── 2652d97ad1b4686e38b8f4122911bb80e8e16139.nq.gz
    ├── 268633ddfa8e9cc1c78f92de38ef9a1455c77f71.nq.gz
    ├── 275ab388dc6c7e7a1212bea770b30848cc5ccda8.nq.gz
    ├── 29107c775ad03f6a4d8934392c0edc5a1ce70a34.nq.gz
    ├── 2914f6844fa3766370d0a45c49b2ee3805035ae9.nq.gz
    ├── 295588b0a8d3b2a9cf0960038fd29c96eff6cdc8.nq.gz
    ├── 296ab8347bf6e8498a678e64894514fce500a46b.nq.gz
    ├── 29cdc4d344be685c35bb09a57a01d40cdb8ce494.nq.gz
    ├── 29d0e4235b22ad19bbdf2b6a4094722d0545cf03.nq.gz
    ├── 29e230094f98da2825a06584694855e05b729923.nq.gz
    ├── 2abe24ad8bec296770232a7770d6b478bd095df0.nq.gz
    ├── 2aee0bcc3a89401f4a86a31c425eb984bf1c4b54.nq.gz
    ├── 2c4d607a1adfad6aaaf0144431486a652e5cfa51.nq.gz
    ├── 2c7a1a58ec4c8984f420a14c383548301d052958.nq.gz
    ├── 2ce0e74f7df46285d70fa71aa37fa725fc6748f2.nq.gz
    ├── 2cea38e389fa507468a32e18aefc80c6eb06c167.nq.gz
    ├── 2d2981976f1117bb0dd0c9f1c182d48f998746c2.nq.gz
    ├── 2d54c660dce872c8dff882150a3dcbe7a336031f.nq.gz
    ├── 2d8d72a1e8152cff657b0c1f8a090300f4e6f3ec.nq.gz
    ├── 2dff4708d4f7330e841251b873c53bfa02e0f459.nq.gz
    ├── 2e8fd74a579141432f7b5ba3a9cef9b40448a001.nq.gz
    ├── 2ecbd5767d022d22f5a1d2db36b8f7d4e32d5055.nq.gz
    ├── 2ef1d0dab8671407ea1933c07ae9a29863910380.nq.gz
    ├── 2f9e9250a9d81ac1b09e0b92c325c73d4a4e3a15.nq.gz
    ├── 2fc515e19ad5658d0e6c45aa50d471172313a3cc.nq.gz
    ├── 3019e012ab98ec46d6bb973df16a7c903bb494af.nq.gz
    ├── 305bd99230d0b1d22f6adf43286f548ab26ef2d5.nq.gz
    ├── 30c081138f4284ff1090ef409173481972aa6201.nq.gz
    ├── 32016e1c7dc19407b24f5e4e69da7bf66b0b13d6.nq.gz
    ├── 320e7188a0dd4a0f7fa784921630750253632af5.nq.gz
    ├── 3274bf86aba1c4d4e3b90606e3f349858629540c.nq.gz
    ├── 33375d3ad8ac4010364065b77bbd0d5f7a70afb0.nq.gz
    ├── 33b918d54bbfe59e821d91401f0b3fc9f35bb549.nq.gz
    ├── 341ec88e3d017c3ba6f53aa31c8bb9422baca43a.nq.gz
    ├── 3422f9f764f5497913d1e187cc53cf52746ed7d0.nq.gz
    ├── 342ea17111b2d5cc78a5d3533f19877236761040.nq.gz
    ├── 34cc2e725a2fbbd2b152424f82c2cf06c125703d.nq.gz
    ├── 3512d1a7748fd718c6d222239db7cc4b5c74a930.nq.gz
    ├── 353cf0f5cdf476110267c158f319ea8811ff65f4.nq.gz
    ├── 360988b6da7bc755bfe67cd894095765f3c15112.nq.gz
    ├── 361c1ae22b0de77d759180eb31694f8416cd72b4.nq.gz
    ├── 3633f813f82e3a38da158c194e7a4c15a05348ac.nq.gz
    ├── 36baf1f752d989a54bcc139cff69dd97ffe8a0dc.nq.gz
    ├── 372ba09cc4baf5381324f7c759a05f4ebf4718ae.nq.gz
    ├── 37845d3114991839517578d1654d311e7bc8015a.nq.gz
    ├── 379cc597aa2e6b0dc1642d8bc441604b0aa3fb99.nq.gz
    ├── 37ee5df1d0a6bee3119efba848ed31f962b046be.nq.gz
    ├── 38c838bf52da555384f9ffced912896707a64ea1.nq.gz
    ├── 38f6e785aca082ff6726752dbbf6fd67ab1c7273.nq.gz
    ├── 3a299ba3a6c8f9a134a09303c7dfbe3cd8ba204d.nq.gz
    ├── 3a39174a56d15be1f48827be4b4dffd63a51f49e.nq.gz
    ├── 3adb47074711595bc8ed886669d7d328302aa7eb.nq.gz
    ├── 3bbcaee165e1f0a9c0795a6a350ab2148500133d.nq.gz
    ├── 3c4edba0632e90ad6db1c95bd8a4f30f13a959d0.nq.gz
    ├── 3c56842730bb2dc470d71a193b586a874978eb4a.nq.gz
    ├── 3c7f4bdd9366de58c03fe541158568de3c9e64bd.nq.gz
    ├── 3d0ff86ebbe6ae8dbc36d63a878781a4f11785f3.nq.gz
    ├── 3d2a82db0f154ac1fe3fe9ed8a5feb3fd59f57e9.nq.gz
    ├── 3d366ad9647be84c8acf1d7cd9d35d5817a6bb5b.nq.gz
    ├── 3d636e5c7379e4d8d85a3521a4729c042fb92c26.nq.gz
    └── 3da5ee1a0835b37d8e2c60f9e365b96bdeed3f8a.nq.gz

32 directories, 200 files
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

[Python-Markdown/markdown](https://github.com/Python-Markdown/markdown)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
