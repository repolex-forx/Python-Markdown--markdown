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
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13
│   │   │   └── chunk-001.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│   │   │   └── chunk-001.nq.gz
│   │   └── f39cf84a24124526c1a0efbe52219fa9950774f6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601.nq.gz
│   │   └── f39cf84a24124526c1a0efbe52219fa9950774f6.nq.gz
│   └── repolex
│       ├── 08dacae618775831243f6bbab47d9be590d511f2
│       │   └── chunk-001.nq.gz
│       ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│       │   └── chunk-001.nq.gz
│       ├── 2932f183921943687ca3d72b3908a937bd495d24
│       │   └── chunk-001.nq.gz
│       ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│       │   └── chunk-001.nq.gz
│       ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│       │   └── chunk-001.nq.gz
│       ├── d9c8431e404d614812e39a11109afbe9981bba13
│       │   └── chunk-001.nq.gz
│       ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│       │   └── chunk-001.nq.gz
│       ├── e524b8fe938738cb4492411a34cce89051cb9695
│       │   └── chunk-001.nq.gz
│       ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│       │   └── chunk-001.nq.gz
│       └── f39cf84a24124526c1a0efbe52219fa9950774f6
│           └── chunk-001.nq.gz
└── blob
    ├── 00c7b5e1b2bdcfd7c87b0f80df924728213e9a53.nq.gz
    ├── 01c118fa68b886bb4b699ae5fbb473f2a466c8a3.nq.gz
    ├── 01c2316d2ba6d0e2c0e3679a43794ccfc33bdc3a.nq.gz
    ├── 01fcd4eb2cfdf6c52bfa6ea4c5036747102bebd7.nq.gz
    ├── 0228ddf020907a733e5f15c189474fdd2176b55b.nq.gz
    ├── 02d86edd31a0f7dfca8870e70680666db7060645.nq.gz
    ├── 0358551706acb01da9a18c389bdd13c1ca01401c.nq.gz
    ├── 03ff4e9e213aa6dd68f222cde1415071479160d8.nq.gz
    ├── 0425971848ad602f0330e932fbc2219d66d11586.nq.gz
    ├── 047996acf07ebff5685aa709f98c01b3e88fa0f3.nq.gz
    ├── 05d808252f83a7242193f77bf3a3175b23984726.nq.gz
    ├── 05fde239e66dd89e89dac1efb40c7100a7a94888.nq.gz
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
    ├── 0a41c4f7667b3d9eb42c3eb2ebd7120123a3a17c.nq.gz
    ├── 0b0af424587fc21738eb626bf434dfbc84698ca7.nq.gz
    ├── 0c317d1bb9076d655b2287d7760175f7fa72eab0.nq.gz
    ├── 0ce7772a73ac98772313fd2bd1b881f6d467ee95.nq.gz
    ├── 0e626b977c19c9e78a31807b045c59e50c26abde.nq.gz
    ├── 0e9527f9311d129ac9ae5bca7666f37c3dfcfb59.nq.gz
    ├── 0f63cdd36ab2f06222a18380bfe7ab5e47c3bfcf.nq.gz
    ├── 0f897b2e37b59e9c402ef946427feb8bdb71a8d2.nq.gz
    ├── 11cb5adc90dca19a2f2640670278561ed76eae3a.nq.gz
    ├── 12856652773c6a08727e5221c7cab3dae818b72d.nq.gz
    ├── 1305c54766ccd84eb4beb39b4a4e5abd51f9ca5e.nq.gz
    ├── 13b3c35f8dd5a6e24ce89174c9a1e395e92b1017.nq.gz
    ├── 13cdea5b1e0794b1bbf9b405cb4457d8b78f5bcd.nq.gz
    ├── 13ecf7c2287842532b662dbf5540caa15f8ec725.nq.gz
    ├── 14aa2dc272d0a056c71049fb4ff80d54d36f9adb.nq.gz
    ├── 14ec034aac7e8419a72210ddaa4c3fb9a24f6d81.nq.gz
    ├── 1594bda27b4130726fd43d0aa1f3ede6487d1905.nq.gz
    ├── 16447a010b1601e51952da95d39da8f56ea37f4b.nq.gz
    ├── 165bbe346a3cf6dfa7525b0457d34930635ffe6f.nq.gz
    ├── 16fe4027ca3e2727c6d652a41dc37ebf3aaedf72.nq.gz
    ├── 177df1ee416ccaa7779f5d969645c4337edc0034.nq.gz
    ├── 18dc114582307427c4ed972a473f2cda7747f681.nq.gz
    ├── 19028bb3e731ec3197e02b633154344c7a971f56.nq.gz
    ├── 19aa92b8718f05cdb98f425b7859765cf338aecc.nq.gz
    ├── 19b9d526d148220666ee79c832e8ad29132ec1f6.nq.gz
    ├── 19f4cf1128a167a8607a3fd669004178223308f1.nq.gz
    ├── 1a0ae12c2ad23ff0cb5052fe95e6d7540618dab9.nq.gz
    ├── 1a1de345e0a03fd4ceff91becd6e464a38dff575.nq.gz
    ├── 1a3544fb35694383b5d03ad1b412dad9b6b3d2e3.nq.gz
    ├── 1bdca393dc0e74dfd476004583ed9460a2026774.nq.gz
    ├── 1c7185b2db7a6b2addc76ae9b573959d6708e02a.nq.gz
    ├── 1cf18bb4330846eba97ce76e340245fdde15a5bd.nq.gz
    ├── 1dbf404a04dcc1d9d53bdf3353c5623ab406ac81.nq.gz
    ├── 1eae842b8ba4a531e2815eda7d27263d199db92f.nq.gz
    ├── 1eb54502db5611c47a8b729444dc959430a9654b.nq.gz
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
    ├── 29107c775ad03f6a4d8934392c0edc5a1ce70a34.nq.gz
    ├── 296ab8347bf6e8498a678e64894514fce500a46b.nq.gz
    ├── 29d0e4235b22ad19bbdf2b6a4094722d0545cf03.nq.gz
    ├── 29e230094f98da2825a06584694855e05b729923.nq.gz
    ├── 2abe24ad8bec296770232a7770d6b478bd095df0.nq.gz
    ├── 2aee0bcc3a89401f4a86a31c425eb984bf1c4b54.nq.gz
    ├── 2c7a1a58ec4c8984f420a14c383548301d052958.nq.gz
    ├── 2cea38e389fa507468a32e18aefc80c6eb06c167.nq.gz
    ├── 2d2981976f1117bb0dd0c9f1c182d48f998746c2.nq.gz
    ├── 2d54c660dce872c8dff882150a3dcbe7a336031f.nq.gz
    ├── 2dff4708d4f7330e841251b873c53bfa02e0f459.nq.gz
    ├── 2e8fd74a579141432f7b5ba3a9cef9b40448a001.nq.gz
    ├── 2ef1d0dab8671407ea1933c07ae9a29863910380.nq.gz
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
    ├── 342ea17111b2d5cc78a5d3533f19877236761040.nq.gz
    ├── 353cf0f5cdf476110267c158f319ea8811ff65f4.nq.gz
    ├── 361c1ae22b0de77d759180eb31694f8416cd72b4.nq.gz
    ├── 3633f813f82e3a38da158c194e7a4c15a05348ac.nq.gz
    ├── 372ba09cc4baf5381324f7c759a05f4ebf4718ae.nq.gz
    ├── 37845d3114991839517578d1654d311e7bc8015a.nq.gz
    ├── 379cc597aa2e6b0dc1642d8bc441604b0aa3fb99.nq.gz
    ├── 37ee5df1d0a6bee3119efba848ed31f962b046be.nq.gz
    ├── 38c838bf52da555384f9ffced912896707a64ea1.nq.gz
    ├── 38f6e785aca082ff6726752dbbf6fd67ab1c7273.nq.gz
    ├── 3a39174a56d15be1f48827be4b4dffd63a51f49e.nq.gz
    ├── 3adb47074711595bc8ed886669d7d328302aa7eb.nq.gz
    ├── 3bbcaee165e1f0a9c0795a6a350ab2148500133d.nq.gz
    ├── 3c4edba0632e90ad6db1c95bd8a4f30f13a959d0.nq.gz
    ├── 3c56842730bb2dc470d71a193b586a874978eb4a.nq.gz
    ├── 3c7f4bdd9366de58c03fe541158568de3c9e64bd.nq.gz
    ├── 3d2a82db0f154ac1fe3fe9ed8a5feb3fd59f57e9.nq.gz
    ├── 3d366ad9647be84c8acf1d7cd9d35d5817a6bb5b.nq.gz
    ├── 3d636e5c7379e4d8d85a3521a4729c042fb92c26.nq.gz
    ├── 3da5ee1a0835b37d8e2c60f9e365b96bdeed3f8a.nq.gz
    ├── 3ed4cf07fcf63852556939382e36bc2210e55e0d.nq.gz
    ├── 3f3cbe2ddda6154ff484ed37d4a007207f9a8059.nq.gz
    ├── 40192e961441f400d1c19c48fcf21a289e16fb95.nq.gz
    ├── 406de9975268e67b5ab4de347231b125ab09e593.nq.gz
    ├── 4076aa909d7044fe6af650b572e2a47cf0bf5fe2.nq.gz
    ├── 41d830d0385feec59a07b3476dedd68ef52749c6.nq.gz
    ├── 4262bce1b6f5019b0a01c50320f4020e621ea33a.nq.gz
    ├── 43f2bcfd56a4acbfaa97874dae2eabd7be696189.nq.gz
    ├── 44bc6568f3c90d1f89a01ee9f82b7920965326bf.nq.gz
    ├── 44dc11d4fd5201e7a5186a6c88d18c382203f075.nq.gz
    ├── 44e8a61596d5fc0d349c7e276c28fdff53b9d275.nq.gz
    ├── 456d05c3cd6531f070761875c6e0e226bc6f7ba5.nq.gz
    ├── 464149ff565eaca4de8293d46a70047b29089a72.nq.gz
    ├── 465ce4f523062bd21bb78c6991fb50ba54b2e258.nq.gz
    ├── 465ef1d9f52ed88acfb49e61e6537f1ce5348522.nq.gz
    ├── 4751f7867c60436887b6ee01a6018f9044b59ad2.nq.gz
    ├── 476a190448c5d362ba462042b77605191c7d3efe.nq.gz
    ├── 478e70216c8aa673552e9e9072ba8a671f7773d7.nq.gz
    ├── 4879070f7fd48a625e76ee9ec3829074d5358f47.nq.gz
    ├── 48ecd6084052b1c4a468d6bca760a58fd6530955.nq.gz
    ├── 4a24440000288b87c6f3ef24bdb57e94600b219d.nq.gz
    ├── 4b10d325aceccb0b8510a3a71e201a554b9e0ecf.nq.gz
    ├── 4b520b57c796cf878055a354c9257009d2537387.nq.gz
    ├── 4cf19ec8dc6421e3a6e1c92b53fa2b636a283626.nq.gz
    ├── 4d0c1c2621047ffd674fcb9b879a8653fc813662.nq.gz
    ├── 4d18affe9f8a71001391d8a1106d93279193d06e.nq.gz
    ├── 4e33d1aa3fe5d19039d1bb109dc75f4389ddbfa0.nq.gz
    ├── 4f068bf96379e1b138013519cfadc91f1a3ed491.nq.gz
    ├── 4f362b78c99ef67e127b7e2268c12a0b0077a6d1.nq.gz
    ├── 4f79d488effd0a5d4f25269283983760619256eb.nq.gz
    ├── 4f7ba750626c26538385b0b85b0332a8def87a22.nq.gz
    ├── 5093348f3424aaeef92e19a5a5375540b2f5261e.nq.gz
    ├── 50e9ec2d1fbed0e5692d66fcd5dc0f719d431835.nq.gz
    ├── 518908c18f00796ad87f2641ab04fee70d64e673.nq.gz
    ├── 519f013b1789937d474b713e0fd4f46b318c7984.nq.gz
    ├── 51a6a32701c2ff799b36403da8875f60de6b7a5e.nq.gz
    ├── 51fbdd67ca9a13967fdd9811e213bee43122b808.nq.gz
    ├── 5256e9046f46f8b055d911f8ff7c8714a7aba48c.nq.gz
    ├── 529e5a968901284a828fc56f4de0ae8569ebd840.nq.gz
    ├── 52ac38a6bc2cf1869ce5a13e730056f144b12e7b.nq.gz
    ├── 5324bf193ac049b802af3f814817473c7a07104e.nq.gz
    ├── 54273b6026e765a596724bdc40337559a0884080.nq.gz
    ├── 545e0610ca4745bde6324057e4678ccc3767fa65.nq.gz
    ├── 5462a906cc51b72a56c7a37aa78cf7cc2607ec86.nq.gz
    ├── 549c9ecd5a2ff01f84c2eccb53d537e18502a8fe.nq.gz
    ├── 551687fdefe8ba71e50c6b5892ac360928446916.nq.gz
    ├── 55e2cdb663bb282a1ee4c6a7db225e02692c219f.nq.gz
    ├── 566e0f174a1ade5deec97c3364072e328c68b861.nq.gz
    └── 56ad2e89a86669d581ba216d504f38f7324e7837.nq.gz

26 directories, 200 files
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
