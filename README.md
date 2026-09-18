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
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│   │   │   └── chunk-001.nq.gz
│   │   └── f39cf84a24124526c1a0efbe52219fa9950774f6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601.nq.gz
│   │   └── f39cf84a24124526c1a0efbe52219fa9950774f6.nq.gz
│   └── repolex
│       ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│       │   └── chunk-001.nq.gz
│       ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│       │   └── chunk-001.nq.gz
│       ├── d9c8431e404d614812e39a11109afbe9981bba13
│       │   └── chunk-001.nq.gz
│       ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│       │   └── chunk-001.nq.gz
│       └── f39cf84a24124526c1a0efbe52219fa9950774f6
│           └── chunk-001.nq.gz
└── blob
    ├── 00c7b5e1b2bdcfd7c87b0f80df924728213e9a53.nq.gz
    ├── 01c118fa68b886bb4b699ae5fbb473f2a466c8a3.nq.gz
    ├── 01fcd4eb2cfdf6c52bfa6ea4c5036747102bebd7.nq.gz
    ├── 0358551706acb01da9a18c389bdd13c1ca01401c.nq.gz
    ├── 03ff4e9e213aa6dd68f222cde1415071479160d8.nq.gz
    ├── 0425971848ad602f0330e932fbc2219d66d11586.nq.gz
    ├── 047996acf07ebff5685aa709f98c01b3e88fa0f3.nq.gz
    ├── 05d808252f83a7242193f77bf3a3175b23984726.nq.gz
    ├── 05fde239e66dd89e89dac1efb40c7100a7a94888.nq.gz
    ├── 06a01d763e0338b973411f7c84c19867ce0d8947.nq.gz
    ├── 070881731e5b86e19788c5af449c75c0665dd684.nq.gz
    ├── 070fa27fc81b3105f029418ff20b6896c579b38a.nq.gz
    ├── 0756514d9d54242586dacc8fdf25595721c0fe71.nq.gz
    ├── 093abb01442dca16e88064ec88d5a7a149a340b7.nq.gz
    ├── 095f17d26630ec79406594c8f6650bf5314a9474.nq.gz
    ├── 0b0af424587fc21738eb626bf434dfbc84698ca7.nq.gz
    ├── 0e626b977c19c9e78a31807b045c59e50c26abde.nq.gz
    ├── 0e9527f9311d129ac9ae5bca7666f37c3dfcfb59.nq.gz
    ├── 0f63cdd36ab2f06222a18380bfe7ab5e47c3bfcf.nq.gz
    ├── 0f897b2e37b59e9c402ef946427feb8bdb71a8d2.nq.gz
    ├── 11cb5adc90dca19a2f2640670278561ed76eae3a.nq.gz
    ├── 12856652773c6a08727e5221c7cab3dae818b72d.nq.gz
    ├── 13b3c35f8dd5a6e24ce89174c9a1e395e92b1017.nq.gz
    ├── 13ecf7c2287842532b662dbf5540caa15f8ec725.nq.gz
    ├── 14aa2dc272d0a056c71049fb4ff80d54d36f9adb.nq.gz
    ├── 14ec034aac7e8419a72210ddaa4c3fb9a24f6d81.nq.gz
    ├── 1594bda27b4130726fd43d0aa1f3ede6487d1905.nq.gz
    ├── 16447a010b1601e51952da95d39da8f56ea37f4b.nq.gz
    ├── 165bbe346a3cf6dfa7525b0457d34930635ffe6f.nq.gz
    ├── 16fe4027ca3e2727c6d652a41dc37ebf3aaedf72.nq.gz
    ├── 18dc114582307427c4ed972a473f2cda7747f681.nq.gz
    ├── 19aa92b8718f05cdb98f425b7859765cf338aecc.nq.gz
    ├── 19b9d526d148220666ee79c832e8ad29132ec1f6.nq.gz
    ├── 19f4cf1128a167a8607a3fd669004178223308f1.nq.gz
    ├── 1a0ae12c2ad23ff0cb5052fe95e6d7540618dab9.nq.gz
    ├── 1a1de345e0a03fd4ceff91becd6e464a38dff575.nq.gz
    ├── 1a3544fb35694383b5d03ad1b412dad9b6b3d2e3.nq.gz
    ├── 1cf18bb4330846eba97ce76e340245fdde15a5bd.nq.gz
    ├── 1dbf404a04dcc1d9d53bdf3353c5623ab406ac81.nq.gz
    ├── 1eae842b8ba4a531e2815eda7d27263d199db92f.nq.gz
    ├── 2094203aee6eb93d11d9f0029ac26c82b3b6d896.nq.gz
    ├── 20e9afa74cfbd546c6168b7d4b40dc4b42bde236.nq.gz
    ├── 20ee6d7c91f93024052ca17dea92f67607341126.nq.gz
    ├── 210933ecee10f02d1457929c06e159e0b050e753.nq.gz
    ├── 21388762e7e213d05f12d0449228ff79fa9babe7.nq.gz
    ├── 24de5d95895c2750c573954f5c5356339d669a64.nq.gz
    ├── 25530d60cba2546282f0c59505baea8c2a193d1b.nq.gz
    ├── 259df6336f8829b27649a6f19058646d662a9213.nq.gz
    ├── 26513242c0caecba0831c4d13e363ac1d97a5f98.nq.gz
    ├── 268633ddfa8e9cc1c78f92de38ef9a1455c77f71.nq.gz
    ├── 29d0e4235b22ad19bbdf2b6a4094722d0545cf03.nq.gz
    ├── 2abe24ad8bec296770232a7770d6b478bd095df0.nq.gz
    ├── 2aee0bcc3a89401f4a86a31c425eb984bf1c4b54.nq.gz
    ├── 2c7a1a58ec4c8984f420a14c383548301d052958.nq.gz
    ├── 2cea38e389fa507468a32e18aefc80c6eb06c167.nq.gz
    ├── 2d2981976f1117bb0dd0c9f1c182d48f998746c2.nq.gz
    ├── 2e8fd74a579141432f7b5ba3a9cef9b40448a001.nq.gz
    ├── 2ef1d0dab8671407ea1933c07ae9a29863910380.nq.gz
    ├── 3019e012ab98ec46d6bb973df16a7c903bb494af.nq.gz
    ├── 30c081138f4284ff1090ef409173481972aa6201.nq.gz
    ├── 32016e1c7dc19407b24f5e4e69da7bf66b0b13d6.nq.gz
    ├── 320e7188a0dd4a0f7fa784921630750253632af5.nq.gz
    ├── 341ec88e3d017c3ba6f53aa31c8bb9422baca43a.nq.gz
    ├── 3633f813f82e3a38da158c194e7a4c15a05348ac.nq.gz
    ├── 372ba09cc4baf5381324f7c759a05f4ebf4718ae.nq.gz
    ├── 379cc597aa2e6b0dc1642d8bc441604b0aa3fb99.nq.gz
    ├── 38c838bf52da555384f9ffced912896707a64ea1.nq.gz
    ├── 38f6e785aca082ff6726752dbbf6fd67ab1c7273.nq.gz
    ├── 3bbcaee165e1f0a9c0795a6a350ab2148500133d.nq.gz
    ├── 3c56842730bb2dc470d71a193b586a874978eb4a.nq.gz
    ├── 3c7f4bdd9366de58c03fe541158568de3c9e64bd.nq.gz
    ├── 3d2a82db0f154ac1fe3fe9ed8a5feb3fd59f57e9.nq.gz
    ├── 3d636e5c7379e4d8d85a3521a4729c042fb92c26.nq.gz
    ├── 3ed4cf07fcf63852556939382e36bc2210e55e0d.nq.gz
    ├── 3f3cbe2ddda6154ff484ed37d4a007207f9a8059.nq.gz
    ├── 406de9975268e67b5ab4de347231b125ab09e593.nq.gz
    ├── 4076aa909d7044fe6af650b572e2a47cf0bf5fe2.nq.gz
    ├── 41d830d0385feec59a07b3476dedd68ef52749c6.nq.gz
    ├── 4262bce1b6f5019b0a01c50320f4020e621ea33a.nq.gz
    ├── 44bc6568f3c90d1f89a01ee9f82b7920965326bf.nq.gz
    ├── 44dc11d4fd5201e7a5186a6c88d18c382203f075.nq.gz
    ├── 44e8a61596d5fc0d349c7e276c28fdff53b9d275.nq.gz
    ├── 456d05c3cd6531f070761875c6e0e226bc6f7ba5.nq.gz
    ├── 464149ff565eaca4de8293d46a70047b29089a72.nq.gz
    ├── 465ce4f523062bd21bb78c6991fb50ba54b2e258.nq.gz
    ├── 465ef1d9f52ed88acfb49e61e6537f1ce5348522.nq.gz
    ├── 476a190448c5d362ba462042b77605191c7d3efe.nq.gz
    ├── 478e70216c8aa673552e9e9072ba8a671f7773d7.nq.gz
    ├── 48ecd6084052b1c4a468d6bca760a58fd6530955.nq.gz
    ├── 4a24440000288b87c6f3ef24bdb57e94600b219d.nq.gz
    ├── 4b520b57c796cf878055a354c9257009d2537387.nq.gz
    ├── 4cf19ec8dc6421e3a6e1c92b53fa2b636a283626.nq.gz
    ├── 4d0c1c2621047ffd674fcb9b879a8653fc813662.nq.gz
    ├── 4e33d1aa3fe5d19039d1bb109dc75f4389ddbfa0.nq.gz
    ├── 4f068bf96379e1b138013519cfadc91f1a3ed491.nq.gz
    ├── 4f362b78c99ef67e127b7e2268c12a0b0077a6d1.nq.gz
    ├── 4f79d488effd0a5d4f25269283983760619256eb.nq.gz
    ├── 4f7ba750626c26538385b0b85b0332a8def87a22.nq.gz
    ├── 50e9ec2d1fbed0e5692d66fcd5dc0f719d431835.nq.gz
    ├── 51a6a32701c2ff799b36403da8875f60de6b7a5e.nq.gz
    ├── 5256e9046f46f8b055d911f8ff7c8714a7aba48c.nq.gz
    ├── 529e5a968901284a828fc56f4de0ae8569ebd840.nq.gz
    ├── 52ac38a6bc2cf1869ce5a13e730056f144b12e7b.nq.gz
    ├── 5324bf193ac049b802af3f814817473c7a07104e.nq.gz
    ├── 545e0610ca4745bde6324057e4678ccc3767fa65.nq.gz
    ├── 549c9ecd5a2ff01f84c2eccb53d537e18502a8fe.nq.gz
    ├── 55e2cdb663bb282a1ee4c6a7db225e02692c219f.nq.gz
    ├── 566e0f174a1ade5deec97c3364072e328c68b861.nq.gz
    ├── 5707590915a9e0945d0d504c2e752b1fc52fc4bb.nq.gz
    ├── 573b2648349de11618af078d2f6c4207200a0732.nq.gz
    ├── 57d725e7ed84edcd9ea49be5a31d3f133cae8baa.nq.gz
    ├── 589d1136e19c0b56dcb6731e8a6c53ae0cedc9a3.nq.gz
    ├── 5b014cb33d16c4ef2727eaf4e60256cc735e345f.nq.gz
    ├── 5c229c7ad31b03fd6af3b39d6fd585719473bb5d.nq.gz
    ├── 5e05459fbafe97da9164aca627bb4052a9147d54.nq.gz
    ├── 5e1ae18d80056b19c1c377d3b1135cad9f91711d.nq.gz
    ├── 5f18b8da214b794a88b9c4303974af06acd0678c.nq.gz
    ├── 601d01e730da40752bd190043855b4da70cdfe05.nq.gz
    ├── 61c19f733c4282bbc8890cc3cfec6c76d287158d.nq.gz
    ├── 621db5815fb12d7f25a71317d1cc14c675f1ea83.nq.gz
    ├── 622838333b22d041fe600cdd12ae4eace2c8a96d.nq.gz
    ├── 6249d60ce6f8a9a2a48a0314150cf0997a4a9962.nq.gz
    ├── 625d2ae18cdaa9472ed99a208f1d709cb430cf77.nq.gz
    ├── 62ad0266b15bc7fd8551b3d6b40be1f45a27523c.nq.gz
    ├── 62bcf9b520c322f80e19c90e1cb02ef6021d214f.nq.gz
    ├── 634758d5c9128faf96618625a9d31e160a4e6f96.nq.gz
    ├── 63e5df31be886f9a4be4f729f81fe99eeff57074.nq.gz
    ├── 6481caa1362af1aa7b2cf9e72771bf4d394cc09a.nq.gz
    ├── 658cd37e01d77a90355b7447695bf19f2079dab3.nq.gz
    ├── 6641e6ea69e1bb2b3616e46dae9992093329c23d.nq.gz
    ├── 678048e61b13af29df398d48a283d21089d79a2d.nq.gz
    ├── 67c6cd0068415ee5d6759b7b85f337bb9b8bc09f.nq.gz
    ├── 69823ae7469d64ece247b75a7864c8d2a8419f86.nq.gz
    ├── 6b45bd4903be49f3d44580aef58d532eb77b5c56.nq.gz
    ├── 6c62e6acc3cb63c396892a8bd57c8b6e988650db.nq.gz
    ├── 6c7a21be9b3a979ac7595452c0330c4d5dfcb294.nq.gz
    ├── 6d739e6d192ebec4a5c7e98db4a49471192b7c14.nq.gz
    ├── 6db0dc38e3ccd45e4639fc93bb4af278cf3e1837.nq.gz
    ├── 6db62226f3c09c6365dec58b9871a87275840c15.nq.gz
    ├── 6e96ea32c3f4744b920591d455ef3e7f7baac72c.nq.gz
    ├── 6f504e39c412ab853e8d11d38b62e25655a0c97a.nq.gz
    ├── 709e9238cb1da866eaf728a5f461783f749f7d36.nq.gz
    ├── 74465f1cb5b13f7506bea3de7b63fcc9e142da07.nq.gz
    ├── 74dbe25a8823c84ee78bf31d39338f5d0f2efaf9.nq.gz
    ├── 74ebc192ca80da9813bf8bf040008c707a343766.nq.gz
    ├── 75bfc74af1b313bfef802648573df4e39bca72a5.nq.gz
    ├── 75f47fa47effc12055128270b29215b3628d83b7.nq.gz
    ├── 77181c873275676370553a60688d66f028f7164d.nq.gz
    ├── 77f5de0868089c33d6e90c0eaa45ee57c9e148d1.nq.gz
    ├── 7927847f001582cb88bc6f6413f096d55a1ad12f.nq.gz
    ├── 79d49a5078295db375171394d386f3b512fcc5d0.nq.gz
    ├── 7a292abfa1985d2ade4ce9f79b4e88ef88a44ad2.nq.gz
    ├── 7b79973eee1f1193dbd0ede676845953eba2625e.nq.gz
    ├── 7bc4f8db499213e433631bf5ac9e8b5d36ec9e49.nq.gz
    ├── 7d033478f995fa41b69700989301e28b9f7b8e7e.nq.gz
    ├── 7d5e324e9698fbeef14a1056c0454a84399820a7.nq.gz
    ├── 7d5faa68bb937959a7629c1b445ee502d390ba42.nq.gz
    ├── 7e6dbeacd37189c74475b5132b03d22bedf7bf3b.nq.gz
    ├── 7eada6ffccb8cc79f5d1f296353f6cef3eacdd72.nq.gz
    ├── 7f3b49777f29e8181b2233357db3f5289b671597.nq.gz
    ├── 814e1bed7f8639428e2df072383c09a9e1acca56.nq.gz
    ├── 82734107ae68d7fb63f5cca64627fc024b5f86cd.nq.gz
    ├── 83630999e48dc2afa52603bd0e3a87fb6239df41.nq.gz
    ├── 83e33c7c9269820dd90260f069ed7b31a7e2e9c0.nq.gz
    ├── 8787e4dc4883c9d6f17a42050ee2f4b488ff7bea.nq.gz
    ├── 87d4e3bcc3e63ca8eced20f142f7f8be88324de4.nq.gz
    ├── 895e44ec5290435791faf3fcf72741cfb21e440e.nq.gz
    ├── 896e1fcdf05c041cd8f9a51123dc0d92849c5b2b.nq.gz
    ├── 8ab6767c0d43d380bd1f32584fe1462dcd6187c9.nq.gz
    ├── 8affc9800659e75b9fa8a109acb0648e4ccce949.nq.gz
    ├── 8b331dcb36e0b9650a5ae7fb1d2c06857dfb0125.nq.gz
    ├── 8bbca47d8baba796814c70738fafbf47d8ce4d0a.nq.gz
    ├── 8c44c98feed2c78169b9a915a0d17c3ccd2b115c.nq.gz
    ├── 8e6911bb49a896a23c18486d61a7b3fa228f0eef.nq.gz
    ├── 8ee512d934f50f7231ed23772fef7c82f5be6b8a.nq.gz
    ├── 8f67b242d1a6f9a3ab4648c0ac6294d870dc6573.nq.gz
    ├── 8f9c77974af7d00ff5f25cf7fd198c23cec07281.nq.gz
    ├── 901060ebfe79ce4dc7edbfb86ce579e56a6ce629.nq.gz
    ├── 9032cf13191e9e9420dfee0a2a62fd333028b185.nq.gz
    ├── 903766fcac3f8c035aff30927ee1267754384cb2.nq.gz
    ├── 909d12bee8c0728f77fc1450105a9dbf287c02c6.nq.gz
    ├── 92e7d8f2be476cee64ea109eb9e19d3d74cde5a7.nq.gz
    ├── 92f6ccc80c3338f0f63b3777b5f04a10ff0104d8.nq.gz
    ├── 93b586977f141bbe2254b6c7e6273222113c9f3d.nq.gz
    └── 93e4a02c3d321c545898a2ebb8873c26dd8a9e5b.nq.gz

16 directories, 200 files
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
*Parsed on 2026-09-18 by [repolex](https://repolex.ai)*
