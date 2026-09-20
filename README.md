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
│   │   ├── 06d0e70438881497402d4798fd6e64aa92d6b532
│   │   │   └── chunk-001.nq.gz
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0d81a0b5272421a8174ea834017b11078b16e5e3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 13c88972de9976137e9f523a80bfd71cdfb97224
│   │   │   └── chunk-001.nq.gz
│   │   ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d41f13c774696d651921601c827ed500e2aa285
│   │   │   └── chunk-001.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│   │   │   └── chunk-001.nq.gz
│   │   ├── 28a5920fbc1f6f91c8bb455e1c1946108e3a6dd0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 41dde4f4b3c6d2eba46ae0e3c6cd595dbdb61466
│   │   │   └── chunk-001.nq.gz
│   │   ├── 447da662b0c9548941a44a911e45c7cf6ad32861
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4e8cbad5ec60806393d0df05419aad33b67bbc73
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4ecbf34d7762d414bd6b027e37568693d05571fb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 54a00d12c03ab3c05ffb57f5797b96b31b6d894f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184
│   │   │   └── chunk-001.nq.gz
│   │   ├── 58b4d64db00ef50c090a9da4bc303c5e840c5c9f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 59bb9afb86d71b258e54c7099beb094f8523ddb7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5deee37e22192c8e6e0d55358eaa013494d20b2c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6323ba6c98cadc19c0a7eebe9b09279b738dc109
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6e15290aba4352451e432f2f1722a2ccb0088fee
│   │   │   └── chunk-001.nq.gz
│   │   ├── 77464c670005bf727e38e6114116ec0c5d58db92
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7df1ed30d98cdc1316ec8da150644d957f1c6303
│   │   │   └── chunk-001.nq.gz
│   │   ├── 829743a598f1cc226a95b77afe171090a3a3204b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9ce3138b7e9cf887c590c67331da4f8ba4b5b7a1
│   │   │   └── chunk-001.nq.gz
│   │   ├── a0b5aef8adb1af7bd2ee0ff033f0997d11ee138b
│   │   │   └── chunk-001.nq.gz
│   │   ├── a884a99173e44b76d28ffb34f27995aa70e5b938
│   │   │   └── chunk-001.nq.gz
│   │   ├── a9195fd2261d8a29762f7d8fc34b520c94fd09ec
│   │   │   └── chunk-001.nq.gz
│   │   ├── aab33ac8a27d1d768949db9c1734931e442e0157
│   │   │   └── chunk-001.nq.gz
│   │   ├── ad4fdeadcaa3f63b3709932015ec65a95e750306
│   │   │   └── chunk-001.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│   │   │   └── chunk-001.nq.gz
│   │   ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── b8c6a76a97c46ae8b7b64236acfa420d7ea03344
│   │   │   └── chunk-001.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d
│   │   │   └── chunk-001.nq.gz
│   │   ├── c282d46a65996f38cfc66f01c2cfced0cddd9e57
│   │   │   └── chunk-001.nq.gz
│   │   ├── d7fa7931bec55eec5498cd79882b770d1110b9b7
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13
│   │   │   └── chunk-001.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── db98a2632447387cd5c965b324904ee780809b81
│   │   │   └── chunk-001.nq.gz
│   │   ├── e4c13788f1c6f6f204ca7c471b25246f6c156832
│   │   │   └── chunk-001.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5ad235956c87f07b056af1ac7218fa980921144
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│   │   │   └── chunk-001.nq.gz
│   │   ├── f0c5b71acbc02af60a33d67c59558bb513b25e74
│   │   │   └── chunk-001.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│   │   │   └── chunk-001.nq.gz
│   │   ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869
│   │   │   └── chunk-001.nq.gz
│   │   ├── f99f176d248d0e472b0960d06a7aaf649bb1da25
│   │   │   └── chunk-001.nq.gz
│   │   ├── fac5b9531416890a0d1d951d18fd30333bb2f7c1
│   │   │   └── chunk-001.nq.gz
│   │   └── fc96b467832cfe4d7060017e439344b10c77a31b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 06d0e70438881497402d4798fd6e64aa92d6b532.nq.gz
│   │   ├── 08dacae618775831243f6bbab47d9be590d511f2.nq.gz
│   │   ├── 0d81a0b5272421a8174ea834017b11078b16e5e3.nq.gz
│   │   ├── 13c88972de9976137e9f523a80bfd71cdfb97224.nq.gz
│   │   ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9.nq.gz
│   │   ├── 1d41f13c774696d651921601c827ed500e2aa285.nq.gz
│   │   ├── 22e89c1fc346f72218a10e392a0c3b4731912522.nq.gz
│   │   ├── 28a5920fbc1f6f91c8bb455e1c1946108e3a6dd0.nq.gz
│   │   ├── 2932f183921943687ca3d72b3908a937bd495d24.nq.gz
│   │   ├── 3870f20ba1dd214609b380e921dffc5f115730f5.nq.gz
│   │   ├── 41dde4f4b3c6d2eba46ae0e3c6cd595dbdb61466.nq.gz
│   │   ├── 447da662b0c9548941a44a911e45c7cf6ad32861.nq.gz
│   │   ├── 4e8cbad5ec60806393d0df05419aad33b67bbc73.nq.gz
│   │   ├── 4ecbf34d7762d414bd6b027e37568693d05571fb.nq.gz
│   │   ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa.nq.gz
│   │   ├── 54a00d12c03ab3c05ffb57f5797b96b31b6d894f.nq.gz
│   │   ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184.nq.gz
│   │   ├── 58b4d64db00ef50c090a9da4bc303c5e840c5c9f.nq.gz
│   │   ├── 59bb9afb86d71b258e54c7099beb094f8523ddb7.nq.gz
│   │   ├── 5deee37e22192c8e6e0d55358eaa013494d20b2c.nq.gz
│   │   ├── 6323ba6c98cadc19c0a7eebe9b09279b738dc109.nq.gz
│   │   ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644.nq.gz
│   │   ├── 6e15290aba4352451e432f2f1722a2ccb0088fee.nq.gz
│   │   ├── 77464c670005bf727e38e6114116ec0c5d58db92.nq.gz
│   │   ├── 7df1ed30d98cdc1316ec8da150644d957f1c6303.nq.gz
│   │   ├── 829743a598f1cc226a95b77afe171090a3a3204b.nq.gz
│   │   ├── 9ce3138b7e9cf887c590c67331da4f8ba4b5b7a1.nq.gz
│   │   ├── a0b5aef8adb1af7bd2ee0ff033f0997d11ee138b.nq.gz
│   │   ├── a884a99173e44b76d28ffb34f27995aa70e5b938.nq.gz
│   │   ├── a9195fd2261d8a29762f7d8fc34b520c94fd09ec.nq.gz
│   │   ├── aab33ac8a27d1d768949db9c1734931e442e0157.nq.gz
│   │   ├── ad4fdeadcaa3f63b3709932015ec65a95e750306.nq.gz
│   │   ├── b34e1d03387be771aa626241fe56f8f0c34243f2.nq.gz
│   │   ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa.nq.gz
│   │   ├── b8c6a76a97c46ae8b7b64236acfa420d7ea03344.nq.gz
│   │   ├── be1c2839dd587a858f91c710e56667cba9f5329d.nq.gz
│   │   ├── c282d46a65996f38cfc66f01c2cfced0cddd9e57.nq.gz
│   │   ├── d7fa7931bec55eec5498cd79882b770d1110b9b7.nq.gz
│   │   ├── d9c8431e404d614812e39a11109afbe9981bba13.nq.gz
│   │   ├── da03cd646d00a77786ae1e0bc79b01a5539852bc.nq.gz
│   │   ├── db98a2632447387cd5c965b324904ee780809b81.nq.gz
│   │   ├── e4c13788f1c6f6f204ca7c471b25246f6c156832.nq.gz
│   │   ├── e524b8fe938738cb4492411a34cce89051cb9695.nq.gz
│   │   ├── e5ad235956c87f07b056af1ac7218fa980921144.nq.gz
│   │   ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601.nq.gz
│   │   ├── f0c5b71acbc02af60a33d67c59558bb513b25e74.nq.gz
│   │   ├── f39cf84a24124526c1a0efbe52219fa9950774f6.nq.gz
│   │   ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869.nq.gz
│   │   ├── f99f176d248d0e472b0960d06a7aaf649bb1da25.nq.gz
│   │   ├── fac5b9531416890a0d1d951d18fd30333bb2f7c1.nq.gz
│   │   └── fc96b467832cfe4d7060017e439344b10c77a31b.nq.gz
│   └── repolex
│       ├── 06d0e70438881497402d4798fd6e64aa92d6b532
│       │   └── chunk-001.nq.gz
│       ├── 08dacae618775831243f6bbab47d9be590d511f2
│       │   └── chunk-001.nq.gz
│       ├── 0d81a0b5272421a8174ea834017b11078b16e5e3
│       │   └── chunk-001.nq.gz
│       ├── 13c88972de9976137e9f523a80bfd71cdfb97224
│       │   └── chunk-001.nq.gz
│       ├── 14c2fa92302084e4850e5323ed56721e43fbbdb9
│       │   └── chunk-001.nq.gz
│       ├── 1d41f13c774696d651921601c827ed500e2aa285
│       │   └── chunk-001.nq.gz
│       ├── 22e89c1fc346f72218a10e392a0c3b4731912522
│       │   └── chunk-001.nq.gz
│       ├── 28a5920fbc1f6f91c8bb455e1c1946108e3a6dd0
│       │   └── chunk-001.nq.gz
│       ├── 2932f183921943687ca3d72b3908a937bd495d24
│       │   └── chunk-001.nq.gz
│       ├── 3870f20ba1dd214609b380e921dffc5f115730f5
│       │   └── chunk-001.nq.gz
│       ├── 41dde4f4b3c6d2eba46ae0e3c6cd595dbdb61466
│       │   └── chunk-001.nq.gz
│       ├── 447da662b0c9548941a44a911e45c7cf6ad32861
│       │   └── chunk-001.nq.gz
│       ├── 4e8cbad5ec60806393d0df05419aad33b67bbc73
│       │   └── chunk-001.nq.gz
│       ├── 4ecbf34d7762d414bd6b027e37568693d05571fb
│       │   └── chunk-001.nq.gz
│       ├── 4f0b91abe1a954a72ab3c99c3e2b880ab36631fa
│       │   └── chunk-001.nq.gz
│       ├── 54a00d12c03ab3c05ffb57f5797b96b31b6d894f
│       │   └── chunk-001.nq.gz
│       ├── 56b03b21f50d2b28b7ab87df7d8015e1f1b62184
│       │   └── chunk-001.nq.gz
│       ├── 58b4d64db00ef50c090a9da4bc303c5e840c5c9f
│       │   └── chunk-001.nq.gz
│       ├── 59bb9afb86d71b258e54c7099beb094f8523ddb7
│       │   └── chunk-001.nq.gz
│       ├── 5deee37e22192c8e6e0d55358eaa013494d20b2c
│       │   └── chunk-001.nq.gz
│       ├── 6323ba6c98cadc19c0a7eebe9b09279b738dc109
│       │   └── chunk-001.nq.gz
│       ├── 6a85e4d4e28e105d4e772a6c2ab8188ddeba1644
│       │   └── chunk-001.nq.gz
│       ├── 6e15290aba4352451e432f2f1722a2ccb0088fee
│       │   └── chunk-001.nq.gz
│       ├── 77464c670005bf727e38e6114116ec0c5d58db92
│       │   └── chunk-001.nq.gz
│       ├── 7df1ed30d98cdc1316ec8da150644d957f1c6303
│       │   └── chunk-001.nq.gz
│       ├── 829743a598f1cc226a95b77afe171090a3a3204b
│       │   └── chunk-001.nq.gz
│       ├── 9ce3138b7e9cf887c590c67331da4f8ba4b5b7a1
│       │   └── chunk-001.nq.gz
│       ├── a0b5aef8adb1af7bd2ee0ff033f0997d11ee138b
│       │   └── chunk-001.nq.gz
│       ├── a884a99173e44b76d28ffb34f27995aa70e5b938
│       │   └── chunk-001.nq.gz
│       ├── a9195fd2261d8a29762f7d8fc34b520c94fd09ec
│       │   └── chunk-001.nq.gz
│       ├── aab33ac8a27d1d768949db9c1734931e442e0157
│       │   └── chunk-001.nq.gz
│       ├── ad4fdeadcaa3f63b3709932015ec65a95e750306
│       │   └── chunk-001.nq.gz
│       ├── b34e1d03387be771aa626241fe56f8f0c34243f2
│       │   └── chunk-001.nq.gz
│       ├── b4a399ca1a39244a84a2dda0ee3fa2d8f17916fa
│       │   └── chunk-001.nq.gz
│       ├── b8c6a76a97c46ae8b7b64236acfa420d7ea03344
│       │   └── chunk-001.nq.gz
│       ├── be1c2839dd587a858f91c710e56667cba9f5329d
│       │   └── chunk-001.nq.gz
│       ├── c282d46a65996f38cfc66f01c2cfced0cddd9e57
│       │   └── chunk-001.nq.gz
│       ├── d7fa7931bec55eec5498cd79882b770d1110b9b7
│       │   └── chunk-001.nq.gz
│       ├── d9c8431e404d614812e39a11109afbe9981bba13
│       │   └── chunk-001.nq.gz
│       ├── da03cd646d00a77786ae1e0bc79b01a5539852bc
│       │   └── chunk-001.nq.gz
│       ├── db98a2632447387cd5c965b324904ee780809b81
│       │   └── chunk-001.nq.gz
│       ├── e4c13788f1c6f6f204ca7c471b25246f6c156832
│       │   └── chunk-001.nq.gz
│       ├── e524b8fe938738cb4492411a34cce89051cb9695
│       │   └── chunk-001.nq.gz
│       ├── e5ad235956c87f07b056af1ac7218fa980921144
│       │   └── chunk-001.nq.gz
│       ├── e5fa5b86e8ec380cbc520cfc637d72c779e5c601
│       │   └── chunk-001.nq.gz
│       ├── f0c5b71acbc02af60a33d67c59558bb513b25e74
│       │   └── chunk-001.nq.gz
│       ├── f39cf84a24124526c1a0efbe52219fa9950774f6
│       │   └── chunk-001.nq.gz
│       ├── f588d8b0f2877c6aa5ac352d27c6f37bdbd41869
│       │   └── chunk-001.nq.gz
│       ├── f99f176d248d0e472b0960d06a7aaf649bb1da25
│       │   └── chunk-001.nq.gz
│       ├── fac5b9531416890a0d1d951d18fd30333bb2f7c1
│       │   └── chunk-001.nq.gz
│       └── fc96b467832cfe4d7060017e439344b10c77a31b
│           └── chunk-001.nq.gz
└── blob
    ├── 0038bdced683d11787dbf6681310f0aca078f769.nq.gz
    ├── 00445ecad4bced3b453913aef08d54032be4d93b.nq.gz
    ├── 00668674ab4fee632b17b86347992c9378b330dc.nq.gz
    ├── 009a39d465030a1bf95b64047870a10e7754cfb5.nq.gz
    ├── 00c330f1f05f0a8cc155fb716d6ea59027820da3.nq.gz
    ├── 00c7b5e1b2bdcfd7c87b0f80df924728213e9a53.nq.gz
    ├── 010e310c3671b48aa8419e15386e02c3ad84508c.nq.gz
    ├── 01329c66cd89e0fbecc505e9eed05c391ab1a0ed.nq.gz
    ├── 0139bd7c8dae42ccfd934fc4bb4bade1ae0b9064.nq.gz
    ├── 016a734ace692fdba4ef729c61e5c34b8a0eec01.nq.gz
    ├── 018400824f07bacccd0f30cc0449920fb424bcdc.nq.gz
    ├── 01bdbd6824264a2a370e9f93b7e0db652ee94324.nq.gz
    ├── 01c118fa68b886bb4b699ae5fbb473f2a466c8a3.nq.gz
    ├── 01c2316d2ba6d0e2c0e3679a43794ccfc33bdc3a.nq.gz
    ├── 01f9940102ceffc34b983e323ff185d9251438a0.nq.gz
    ├── 01fcd4eb2cfdf6c52bfa6ea4c5036747102bebd7.nq.gz
    ├── 0212a4da3bf91f2c5f44a94c31388477ea054ecf.nq.gz
    ├── 0222c91351a29c89297ef95a61ca8841091a7fb4.nq.gz
    ├── 0228ddf020907a733e5f15c189474fdd2176b55b.nq.gz
    ├── 02321a660df1e110b37e6ab86a964aba8ca758ad.nq.gz
    ├── 02d86edd31a0f7dfca8870e70680666db7060645.nq.gz
    ├── 0358551706acb01da9a18c389bdd13c1ca01401c.nq.gz
    ├── 0388070ac5efb5a1a45baeac51406031884d1acc.nq.gz
    ├── 0397f9c2cfcd94f7590eda296ab09030df7ecef1.nq.gz
    ├── 03b2a4cf3247b6b064143be37034ed520f46fec2.nq.gz
    ├── 03ff4e9e213aa6dd68f222cde1415071479160d8.nq.gz
    ├── 0425971848ad602f0330e932fbc2219d66d11586.nq.gz
    ├── 04587560d9a76677ff8cf64a5b6e1112de1c08dc.nq.gz
    ├── 047996acf07ebff5685aa709f98c01b3e88fa0f3.nq.gz
    ├── 04893e3e4c1971ce308d17cead8503ceb3d24dc7.nq.gz
    ├── 0541e7b40917f9c95871c55b15b874b7ea7bbb54.nq.gz
    ├── 055d8ac346cc269b6fc658839ca6c5a3c70a5e7f.nq.gz
    ├── 05d808252f83a7242193f77bf3a3175b23984726.nq.gz
    ├── 05fde239e66dd89e89dac1efb40c7100a7a94888.nq.gz
    ├── 062a7e6e2ec7d152a3029f16074b4c5269609143.nq.gz
    ├── 0639d3d6df1c46a9aecef540cb43d0e4ab63a004.nq.gz
    ├── 0649870476a456bf13e254a6c2af6a4a2ad431a6.nq.gz
    ├── 0657c37681e08c5563b642a6f6bda5be253717e2.nq.gz
    ├── 06995127aea17b4210bed75183178e931e019baf.nq.gz
    ├── 06a01d763e0338b973411f7c84c19867ce0d8947.nq.gz
    ├── 06a51078256a4ab38d5c6bba38bb467a8a83ad59.nq.gz
    ├── 06b9c9aa8342c8179c3dba2bc62478daefa5b970.nq.gz
    ├── 0702f6b2ab51b47d15672fe37aaa45abd971b049.nq.gz
    ├── 070881731e5b86e19788c5af449c75c0665dd684.nq.gz
    ├── 070bb01a96c8e6b5d5e8049590f8bbd307f32996.nq.gz
    ├── 070c4cce0fdb0379360b9e337b618704c32db0e8.nq.gz
    └── 070fa27fc81b3105f029418ff20b6896c579b38a.nq.gz

108 directories, 200 files
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
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
