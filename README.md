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
│   │   ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d41f13c774696d651921601c827ed500e2aa285
│   │   │   └── chunk-001.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 447da662b0c9548941a44a911e45c7cf6ad32861
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644
│   │   │   └── chunk-001.nq.gz
│   │   ├── a884a99173e44b76d28ffb34f27995aa70e5b938
│   │   │   └── chunk-001.nq.gz
│   │   ├── aab33ac8a27d1d768949db9c1734931e442e0157
│   │   │   └── chunk-001.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13
│   │   │   └── chunk-001.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── db98a2632447387cd5c965b324904ee780809b81
│   │   │   └── chunk-001.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│   │   │   └── chunk-001.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│   │   │   └── chunk-001.nq.gz
│   │   ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869
│   │   │   └── chunk-001.nq.gz
│   │   └── f99f176d248d0e472b0960d06a7aaf649bb1da25
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2.nq.gz
│   │   ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9.nq.gz
│   │   ├── 1d41f13c774696d651921601c827ed500e2aa285.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5.nq.gz
│   │   ├── 447da662b0c9548941a44a911e45c7cf6ad32861.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa.nq.gz
│   │   ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184.nq.gz
│   │   ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644.nq.gz
│   │   ├── a884a99173e44b76d28ffb34f27995aa70e5b938.nq.gz
│   │   ├── aab33ac8a27d1d768949db9c1734931e442e0157.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2.nq.gz
│   │   ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc.nq.gz
│   │   ├── db98a2632447387cd5c965b324904ee780809b81.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6.nq.gz
│   │   ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869.nq.gz
│   │   └── f99f176d248d0e472b0960d06a7aaf649bb1da25.nq.gz
│   └── repolex
│       ├── 08dacae618775831243f6bbab47d9be590d511f2
│       │   └── chunk-001.nq.gz
│       ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9
│       │   └── chunk-001.nq.gz
│       ├── 1d41f13c774696d651921601c827ed500e2aa285
│       │   └── chunk-001.nq.gz
│       ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│       │   └── chunk-001.nq.gz
│       ├── 2932f183921943687ca3d72b3908a937bd495d24
│       │   └── chunk-001.nq.gz
│       ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│       │   └── chunk-001.nq.gz
│       ├── 447da662b0c9548941a44a911e45c7cf6ad32861
│       │   └── chunk-001.nq.gz
│       ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│       │   └── chunk-001.nq.gz
│       ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184
│       │   └── chunk-001.nq.gz
│       ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644
│       │   └── chunk-001.nq.gz
│       ├── a884a99173e44b76d28ffb34f27995aa70e5b938
│       │   └── chunk-001.nq.gz
│       ├── aab33ac8a27d1d768949db9c1734931e442e0157
│       │   └── chunk-001.nq.gz
│       ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│       │   └── chunk-001.nq.gz
│       ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa
│       │   └── chunk-001.nq.gz
│       ├── be1c2839dd587a858f91c710e56667cba9f5329d
│       │   └── chunk-001.nq.gz
│       ├── d9c8431e404d614812e39a11109afbe9981bba13
│       │   └── chunk-001.nq.gz
│       ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│       │   └── chunk-001.nq.gz
│       ├── db98a2632447387cd5c965b324904ee780809b81
│       │   └── chunk-001.nq.gz
│       ├── e524b8fe938738cb4492411a34cce89051cb9695
│       │   └── chunk-001.nq.gz
│       ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│       │   └── chunk-001.nq.gz
│       ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│       │   └── chunk-001.nq.gz
│       ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869
│       │   └── chunk-001.nq.gz
│       └── f99f176d248d0e472b0960d06a7aaf649bb1da25
│           └── chunk-001.nq.gz
└── blob
    ├── 00445ecad4bced3b453913aef08d54032be4d93b.nq.gz
    ├── 009a39d465030a1bf95b64047870a10e7754cfb5.nq.gz
    ├── 00c7b5e1b2bdcfd7c87b0f80df924728213e9a53.nq.gz
    ├── 018400824f07bacccd0f30cc0449920fb424bcdc.nq.gz
    ├── 01c118fa68b886bb4b699ae5fbb473f2a466c8a3.nq.gz
    ├── 01c2316d2ba6d0e2c0e3679a43794ccfc33bdc3a.nq.gz
    ├── 01f9940102ceffc34b983e323ff185d9251438a0.nq.gz
    ├── 01fcd4eb2cfdf6c52bfa6ea4c5036747102bebd7.nq.gz
    ├── 0228ddf020907a733e5f15c189474fdd2176b55b.nq.gz
    ├── 02d86edd31a0f7dfca8870e70680666db7060645.nq.gz
    ├── 0358551706acb01da9a18c389bdd13c1ca01401c.nq.gz
    ├── 0388070ac5efb5a1a45baeac51406031884d1acc.nq.gz
    ├── 03ff4e9e213aa6dd68f222cde1415071479160d8.nq.gz
    ├── 0425971848ad602f0330e932fbc2219d66d11586.nq.gz
    ├── 04587560d9a76677ff8cf64a5b6e1112de1c08dc.nq.gz
    ├── 047996acf07ebff5685aa709f98c01b3e88fa0f3.nq.gz
    ├── 04893e3e4c1971ce308d17cead8503ceb3d24dc7.nq.gz
    ├── 055d8ac346cc269b6fc658839ca6c5a3c70a5e7f.nq.gz
    ├── 05d808252f83a7242193f77bf3a3175b23984726.nq.gz
    ├── 05fde239e66dd89e89dac1efb40c7100a7a94888.nq.gz
    ├── 0649870476a456bf13e254a6c2af6a4a2ad431a6.nq.gz
    ├── 06a01d763e0338b973411f7c84c19867ce0d8947.nq.gz
    ├── 06a51078256a4ab38d5c6bba38bb467a8a83ad59.nq.gz
    ├── 070881731e5b86e19788c5af449c75c0665dd684.nq.gz
    ├── 070c4cce0fdb0379360b9e337b618704c32db0e8.nq.gz
    ├── 070fa27fc81b3105f029418ff20b6896c579b38a.nq.gz
    ├── 0756514d9d54242586dacc8fdf25595721c0fe71.nq.gz
    ├── 0794b7f9fc2c9578b573e2a6c9bdbdbab4785723.nq.gz
    ├── 0872aaaf5dfba614b12b9a95aa35c19bbb459e1a.nq.gz
    ├── 08cbb492e4c1f3fed5436d0d32149cc16b4bdb31.nq.gz
    ├── 08fb8ef848397987acbd41de305ed5eac09a65ac.nq.gz
    ├── 093abb01442dca16e88064ec88d5a7a149a340b7.nq.gz
    ├── 095f17d26630ec79406594c8f6650bf5314a9474.nq.gz
    ├── 09ace62be17bd97ccaf38806ba19761bb653bd28.nq.gz
    ├── 09b8cf619f6e16198baa1a51670f499415cf26af.nq.gz
    ├── 09ce6e7064579b921116100452ac4a0c80823882.nq.gz
    ├── 09dd523c1e9185035c5dfe0eda9e70657fee0d22.nq.gz
    ├── 0a41c4f7667b3d9eb42c3eb2ebd7120123a3a17c.nq.gz
    ├── 0a4e2f3d793cb1fca9a597bdd7aabf2ed426e3e1.nq.gz
    ├── 0a9d084713254595aa9f77df3396653489fa58fd.nq.gz
    ├── 0afb6a26dcf4846f79ee3ce3ba1e2fcc2c9b0bfa.nq.gz
    ├── 0b0af424587fc21738eb626bf434dfbc84698ca7.nq.gz
    ├── 0bd129cd1fd95752bce38931960ebf8a4ca22dc6.nq.gz
    ├── 0c317d1bb9076d655b2287d7760175f7fa72eab0.nq.gz
    ├── 0c76754f1acd0d103a65939e5aaa2fa50577941e.nq.gz
    ├── 0ce7772a73ac98772313fd2bd1b881f6d467ee95.nq.gz
    ├── 0e56161308f69fd7a3b3375ca4d0c1c51dd0a463.nq.gz
    ├── 0e626b977c19c9e78a31807b045c59e50c26abde.nq.gz
    ├── 0e89d406ffe2526544dccacd132fc4a2f7e7eaf2.nq.gz
    ├── 0e8e45285659781a5c66634877d7a69d426b26c2.nq.gz
    ├── 0e9527f9311d129ac9ae5bca7666f37c3dfcfb59.nq.gz
    ├── 0ee47b6d17f17b8965d511f7a665c2436668fe4a.nq.gz
    ├── 0f63cdd36ab2f06222a18380bfe7ab5e47c3bfcf.nq.gz
    ├── 0f897b2e37b59e9c402ef946427feb8bdb71a8d2.nq.gz
    ├── 10a2d3337402c67cc85d024dd496bcc98ffb8e35.nq.gz
    ├── 10dee11848e85a0b528f6b8b5ed30cf477bc89ea.nq.gz
    ├── 114227da5ca6f747bd65864292ee5a2d710b88f2.nq.gz
    ├── 11cb5adc90dca19a2f2640670278561ed76eae3a.nq.gz
    ├── 12273bc8884c2cf60a92fbe061813f9661a8e676.nq.gz
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
    ├── 161e886822522f1156bed461ae386c7387abc4fd.nq.gz
    ├── 16447a010b1601e51952da95d39da8f56ea37f4b.nq.gz
    ├── 165bbe346a3cf6dfa7525b0457d34930635ffe6f.nq.gz
    ├── 16f308887136265cfa4faaf03c1ec04b7174c08a.nq.gz
    ├── 16fe4027ca3e2727c6d652a41dc37ebf3aaedf72.nq.gz
    ├── 17549f031fd7fc27232d2660c7fdda41a7e849c3.nq.gz
    ├── 177df1ee416ccaa7779f5d969645c4337edc0034.nq.gz
    ├── 17b46889669372c43b2f34babdc904b1b079d3e9.nq.gz
    ├── 17b47517bbefe333fcd05f8295052a8dba6b6be1.nq.gz
    ├── 17e301b702f44d5367952f64e4d58a9deedcae07.nq.gz
    ├── 18306f78a537efe960673357434b230700d3dc34.nq.gz
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
    ├── 1a3a2b0bba9f130977723b63e47b742cd692be40.nq.gz
    ├── 1bdca393dc0e74dfd476004583ed9460a2026774.nq.gz
    ├── 1c6c4415501485bcc32bd5f9320f080140cbaeec.nq.gz
    ├── 1c7185b2db7a6b2addc76ae9b573959d6708e02a.nq.gz
    ├── 1cc7118916ff0fb81be5ca1b3cbfae163debde84.nq.gz
    ├── 1cf18bb4330846eba97ce76e340245fdde15a5bd.nq.gz
    ├── 1d0a7e1fa1076c1eae3764da7e5b26748bb95d0d.nq.gz
    ├── 1db47dc59060645b24a90c8463bee7ccf6062386.nq.gz
    ├── 1dbf404a04dcc1d9d53bdf3353c5623ab406ac81.nq.gz
    ├── 1ded18d6305dec16e09d860fac8a7a62967fd3e1.nq.gz
    ├── 1df68854157cb6b6f1de04614828a6a6902f87ab.nq.gz
    ├── 1e7fafa51c1aaf475013a4dfd8f2247c9c220a9b.nq.gz
    ├── 1eae842b8ba4a531e2815eda7d27263d199db92f.nq.gz
    ├── 1eb54502db5611c47a8b729444dc959430a9654b.nq.gz
    ├── 1ee6029737580073b7123c37ae1aa4683e0e7972.nq.gz
    ├── 1f4ab23901e34861977a8e617cdf618bd6c21295.nq.gz
    ├── 1f80c7ea6cda4317b579f74144436208afb299c6.nq.gz
    ├── 1fa82189979d8e18a1f2fe176b01a208f7d5a38f.nq.gz
    ├── 2094203aee6eb93d11d9f0029ac26c82b3b6d896.nq.gz
    ├── 20e9afa74cfbd546c6168b7d4b40dc4b42bde236.nq.gz
    ├── 20ee6d7c91f93024052ca17dea92f67607341126.nq.gz
    ├── 20f21c252d5c6f050b8a6a3b313ac7547b88c077.nq.gz
    ├── 210933ecee10f02d1457929c06e159e0b050e753.nq.gz
    ├── 21388762e7e213d05f12d0449228ff79fa9babe7.nq.gz
    ├── 21934a22d09338b3130dd0a3f60dda809c23dc9f.nq.gz
    ├── 21ae1a7de03c22cb0abc4aca1ca38133bdee596a.nq.gz
    ├── 21fceacecf984a27650c762e8e566be819c37b32.nq.gz
    ├── 22b949834b84ca83ba580a641cbd4a5c5859bf75.nq.gz
    ├── 230ba3435605ea5375ccc205254f8444c7df6c78.nq.gz
    ├── 23d56034a8a40d264109da4aa61059381a66e93d.nq.gz
    ├── 241bb6d40e06a46b6b055c5e90f535557ec192a8.nq.gz
    ├── 2424dbc842a2dd41531f575e7d6a832936b7fffe.nq.gz
    ├── 246b60d1cfd167562355bc5f51bff2d75384172a.nq.gz
    ├── 24b01f65e12f042d553c3356a1fc23c516364226.nq.gz
    ├── 24d8254a997bcfb7bd23064f7cd3f01f6d9bd955.nq.gz
    ├── 24de5d95895c2750c573954f5c5356339d669a64.nq.gz
    ├── 25530d60cba2546282f0c59505baea8c2a193d1b.nq.gz
    ├── 259c47f746972bc5f34fe8ea47825b6f1bca67d3.nq.gz
    ├── 259df6336f8829b27649a6f19058646d662a9213.nq.gz
    ├── 25abb16eda498751dce83173994da9546877acfc.nq.gz
    └── 26513242c0caecba0831c4d13e363ac1d97a5f98.nq.gz

52 directories, 200 files
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
