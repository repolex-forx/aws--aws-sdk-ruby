# Repolex Knowledge Graph of aws/aws-sdk-ruby

RDF knowledge graph data for [aws/aws-sdk-ruby](https://github.com/aws/aws-sdk-ruby), parsed by [repolex](https://repolex.ai).

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
lexq download aws/aws-sdk-ruby
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3665106e009d2e46b022b00997c939b1c28fb022
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3665106e009d2e46b022b00997c939b1c28fb022.nq.gz
│   └── repolex
│       └── 3665106e009d2e46b022b00997c939b1c28fb022
│           └── chunk-001.nq.gz
└── blob
    ├── 000e53d13ea77705e782c8b88e673ac905a0617e.nq.gz
    ├── 000eb57d5e808ed1fbba0acc6b6a19b766c31af7.nq.gz
    ├── 0014a26627b184b30eb1945776e535e862c24f14.nq.gz
    ├── 00c06275baa72a9f5e0e3a35104dc48f1a43f099.nq.gz
    ├── 00ff98edbc2ad97bb6c774a2a16e3c66d8688280.nq.gz
    ├── 012933781f40fde15f31ce140b0be969bdb998f3.nq.gz
    ├── 01729da0e733fdee1df30d259969f8cf53c2aa5d.nq.gz
    ├── 01d845b9306ff8bea4a516e43b532a3dc03138e7.nq.gz
    ├── 02556b61e4e72e8d031e2697948fb1b4e2b61bc6.nq.gz
    ├── 02bc90671620a60591f9b3928837e332f68fe82e.nq.gz
    ├── 02e8922906243ea7d110a140fedc1e14e7b61610.nq.gz
    ├── 030badf143775d0d40e6450f2fcb2933287ea813.nq.gz
    ├── 031169bf92004e73ed9dfd9fa2fe907d0650c443.nq.gz
    ├── 0329f539bc78c7bbdf0a00cd5c0ff7890901564d.nq.gz
    ├── 0342e379fe91d21ae593b3012e969ee196140003.nq.gz
    ├── 034b85a3dd7e3c74d9c95b260f51cdd33fd1706a.nq.gz
    ├── 034d95a4841241652f9cd9b8bdf7ef84199c8e9c.nq.gz
    ├── 036163bb475a243da26a42f1171c8225a52cde6a.nq.gz
    ├── 039e04d60f3452d93a6ecffdb12bbca24802517c.nq.gz
    ├── 03c31dd7818248c1629a56c9d6d70886aadde0c3.nq.gz
    ├── 03deec4c0e973164ca635863340ea8695baafdd0.nq.gz
    ├── 03f248425e21ae05bb0c43720821b3482537e5de.nq.gz
    ├── 041fdc9317e2ddb982b9dfa41f1da9258360e780.nq.gz
    ├── 042c4bd81ebf8f96f280584b0e5537b0cec6ccd7.nq.gz
    ├── 0435b13bc0a5a92de8d543877ce27e09a8636ba6.nq.gz
    ├── 04457b247af046763869dba443356451d1ee507e.nq.gz
    ├── 04552996032029ab1e61c0d155b0646050dbe9ad.nq.gz
    ├── 0457f108fb8b4f81379cc060dee07cf81e6f77e0.nq.gz
    ├── 048a6bb6c0586d945b93b566921fb0a57582661e.nq.gz
    ├── 0497df084841b9838dc1230ecb0650de643d770b.nq.gz
    ├── 04b8669445daff91fe822c96d897fcdacd41e0c2.nq.gz
    ├── 04c2ed2586a55b6e7954afedd3d12832e3692e39.nq.gz
    ├── 050ca3b0898ea8e4e19320c2f21ce68165a88ac9.nq.gz
    ├── 05135fe2e2b5cf4ba0ec73a6e1e547697dedfff8.nq.gz
    ├── 05234e24c6e639f402b30efdc300fadafcbd6fe0.nq.gz
    ├── 053fd1ea2401ed469c311f646ac20c1f6f630e9a.nq.gz
    ├── 056aaac5f22f30b857b2bd2621d2cd50f3509256.nq.gz
    ├── 057baeb0eeefee3538668872db4780163872ef5d.nq.gz
    ├── 05917d111f977cecd8a43d3c37b384f29f6f53a9.nq.gz
    ├── 05a3e48e87b1cb1ea444347dbc03867f2d899e0d.nq.gz
    ├── 05ac22f5a5eeb261681e3e42679b3d25f58c409c.nq.gz
    ├── 05ac652a5934778f11ceeed1754c18e031b3592e.nq.gz
    ├── 05b541f045665d048b8aa34aad7ade34638e07d4.nq.gz
    ├── 05ba94ea4ef036ed7d76b2d019c4d47e939a7e2f.nq.gz
    ├── 05ea54a70519d0ef7ca03378ff2b5fe13b5c0077.nq.gz
    ├── 05f3f259a031f195f2dfb54cb888da90ce491eaa.nq.gz
    ├── 0603ccc3da0ae389f2a33b48a41dcbf7ad003bc9.nq.gz
    ├── 06267cf446a3e9768031c9d2cd71977767524d0e.nq.gz
    ├── 063fd9c08a32d2d29427375af7fc08adbd8d1f78.nq.gz
    ├── 064c2e74e94bb259f2f020275e98a60a6a310634.nq.gz
    ├── 064c4053df9f6e3e3279be1430efb5b6583be149.nq.gz
    ├── 0665148e34036a6a5236199cdee4081853982fc7.nq.gz
    ├── 067170af54d66a31c234b0c76242fc0a0130a25a.nq.gz
    ├── 06824a26b3e2049d9e3c682a31243ec12a9faa8b.nq.gz
    ├── 068b23492c36e186032ba7ce436b48a364d98e08.nq.gz
    ├── 06b8076d721d64e6236c1b250c49568d698d536a.nq.gz
    ├── 06d385b7095c4ea33d0b8ea0ae1fee78b281f39a.nq.gz
    ├── 06fb959003bcdf247855f6568f50382109c603ee.nq.gz
    ├── 073b14d30e5929f098dee0e5ac555e5b42d27d4d.nq.gz
    ├── 076b65a2ca57f67a38c75589ac98ead6d50e427f.nq.gz
    ├── 077fbb63c6c59ce3555b5d61b1761a639faf7467.nq.gz
    ├── 07a64a056d43ded02a83c93f10934a1dbd1dcb2a.nq.gz
    ├── 07d605b1d2c2b5a6342c5468a1f27998e58028ea.nq.gz
    ├── 07f17ba73b27c301638e13fa9810d2eff1844744.nq.gz
    ├── 07f3cda7cc58a08728a618275423858432583783.nq.gz
    ├── 0847bc32024fa4564422bade0ed3834a07894896.nq.gz
    ├── 084f09d8dd15a6f1db2bcccbbac45ab64c8734c1.nq.gz
    ├── 08694bc3f53ece7e9a064c99eaadcd342bf08b89.nq.gz
    ├── 087dce8b3f035f525f006e2eac3a00aa9ada73a7.nq.gz
    ├── 09114adc011ce5daddc32ec53c3e581ea7ddb55c.nq.gz
    ├── 093d64995b1089b482b066c3049759f53e4705d5.nq.gz
    ├── 0943f1d56ac81985dba9dac49f881200705d8746.nq.gz
    ├── 09512abbc5fccae69e3a659cf2c2d4ab37172d9b.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 0982d973b5e4651682f1f1adc7246082376d0c57.nq.gz
    ├── 09f987dbfe46743972be8577e0fc2db9d0650f51.nq.gz
    ├── 09fecfab1f2c84c8b4da25a02ca42fed7e3aa861.nq.gz
    ├── 0a311f5f2fd72fc0f55db46254af796c96c0ba07.nq.gz
    ├── 0a801760554c8b9d59ac884cbe53b2102ea1194c.nq.gz
    ├── 0a98c5b4e9fd57584a9bf882fac549a0603a857e.nq.gz
    ├── 0a9eaf71de40a3bf490d2e1462eef25608499127.nq.gz
    ├── 0ab359873da1b152b09161b44c49217d43993667.nq.gz
    ├── 0aeeeb8d3ca1b1e58053a481f0f6763776364415.nq.gz
    ├── 0b2f39404153f060eaf0b8923df03ce4f1c39ebf.nq.gz
    ├── 0b48da94fe5e99ddfcc7d2c37dfc60c9f713043b.nq.gz
    ├── 0b5717370854e79929eab4ceb9a737866ca5d070.nq.gz
    ├── 0b6a1ed3317e2411930776cdbe024ac5304d10f3.nq.gz
    ├── 0be480deacfbce6ff0b53c52fbfc2168cedaa955.nq.gz
    ├── 0c2a8ddf4cb0e3cfde5dad52f7df7a5f83fa31aa.nq.gz
    ├── 0c521c96ab8833534079ae1bc5d421daa3702085.nq.gz
    ├── 0c8e447c46e24c1d6c961771358c339e54fe9b89.nq.gz
    ├── 0cce3b4a3cc8919925a18f4c6117cddf979ae700.nq.gz
    ├── 0ce33d1e5ca3e933c61a0bab6c6f85105272b074.nq.gz
    ├── 0d1b38715575ccd20ecb4a77600668b666fad8ed.nq.gz
    ├── 0d30588a5d9ef6b1ed088077658b0ef77b9c3e45.nq.gz
    ├── 0d4f101c7a37a4c875e6999bee1a287fdb733380.nq.gz
    ├── 0d51ee57e96f9804b142f5dff39e5914fac88640.nq.gz
    ├── 0d55dc8072223ba9a683c034bb4bf293e54240c4.nq.gz
    ├── 0dabb32f7c4131e0116a3955473ec15fd294f1c4.nq.gz
    ├── 0dcf07ba91f057470f0a0443284020e0a92ead47.nq.gz
    ├── 0dd8cb1941624c7707575a28d6f225594930063b.nq.gz
    ├── 0df2e5b4848015dd91b91b63cd0f69c8df22c74e.nq.gz
    ├── 0e02fc699b9163702a6a46080ee0f1567feefc25.nq.gz
    ├── 0e462efca243e1d7e1b1b7d93416a9535a4ce48c.nq.gz
    ├── 0e847452936c44046d07dde119866281677bb028.nq.gz
    ├── 0e937993faf3ee2982bef03bf928d0d21f63cc44.nq.gz
    ├── 0ea7e3b0bbe917eb027880396ac01509becd1fa0.nq.gz
    ├── 0eb39e6f7f3af93f7210f01f84e1c97922124c9f.nq.gz
    ├── 0f39aad9dbce01545b9aa50b8c89fb40c6002216.nq.gz
    ├── 0fbf7b36a754b3d9fbc77dd8a22f4ffaa7225118.nq.gz
    ├── 0fd4f4adc5b8b469e2fd5058748d095a12b3c435.nq.gz
    ├── 0fded62815628f6b0586acfda2445a5a5774f7ee.nq.gz
    ├── 0fe08a68af2a2eca84151007f436cdbc7c67d699.nq.gz
    ├── 0fea4facde2fd2fc3ad7a0683376623be515d0f8.nq.gz
    ├── 1052182aafe6c77b2c16177e538a899f69cc4a83.nq.gz
    ├── 109bb1ba047c271cb0c776a4493fad463ed59764.nq.gz
    ├── 10a0f08122bb15225b99cad64589b7e6685d64b8.nq.gz
    ├── 10aed2825a296012538a62d728815e78d87b53db.nq.gz
    ├── 10d638978aceaafef5199706d2b36b548f98770c.nq.gz
    ├── 10e27ea0937877bcb2e9115f96036c87bee3d2ea.nq.gz
    ├── 115eff20492b8bc23bb3b8e29152e2ffed273706.nq.gz
    ├── 1176e68f0afc82c1807044aa60b48441c0027f1c.nq.gz
    ├── 120440d57a716da3ec2427ae107825099476dd00.nq.gz
    ├── 1222a2891bc0cf57da70ca26c864669eb3e1b174.nq.gz
    ├── 124e17e638dd90b7f69dbd4da158ce47598dac70.nq.gz
    ├── 12525be1945df35ce0ecc0a93afd9fb8d3603d62.nq.gz
    ├── 12915162c92c32991b34b7858ff9ab0dfc7a982c.nq.gz
    ├── 12a87a454620b3a15a816caa4e5d0ada1473427d.nq.gz
    ├── 12b4e2c6c9a6757f4bc8b0ed9ef6373f20193cd7.nq.gz
    ├── 12ba13162ccbf83d606d5a50486e91890f17a240.nq.gz
    ├── 12bef398edfffa00644e57d9746249ed61f8277f.nq.gz
    ├── 12c425a62a16593e1d0bb6e1db91a9c0cc74b12c.nq.gz
    ├── 130b33d92c351ee66cfb9fad7fa5cfd3383b12f4.nq.gz
    ├── 132728d55265636c064039f598c98bfd413294e2.nq.gz
    ├── 1350b148aab76a937edcc0521e27b22c75d7b231.nq.gz
    ├── 1363c94a7da7b02c89293028577fb783d6f4cad3.nq.gz
    ├── 1369114221b14a47a60f7e8f548f15b605270b5c.nq.gz
    ├── 139c05ae8a4c8ad6a51eb531b07e0dd79a87114b.nq.gz
    ├── 13bd72715d36f965087aab16e59f36c6157973a4.nq.gz
    ├── 13fbb1a0e390f09c34f4e6dd151079ce1bf1770f.nq.gz
    ├── 147b3e594ae83da748dd103a1782acf8f84944ea.nq.gz
    ├── 1493f27abe43b2cd7d41d9eb075f3e744e244855.nq.gz
    ├── 14c4c9738b003d6a88dac1248e7c16ede4422d27.nq.gz
    ├── 14fbf4b701929f9ec600331c020a4bdb882964ee.nq.gz
    ├── 15104b28a71220b1586da32bf9f63b01fc49d176.nq.gz
    ├── 1510d1fc8a470720972af43abbad15ddc4c29b64.nq.gz
    ├── 155d03bb161795f31f2192b8bb998f11be804ab7.nq.gz
    ├── 155d2abb263907b6177e84c0a9dbe03e5f93945a.nq.gz
    ├── 15f739527f4794b905ef5d8c863cb52b78e075fc.nq.gz
    ├── 16179e444bb37e8f584ad74d2704dd6875a4c87b.nq.gz
    ├── 161bcdf3b7ea2463dbe78e8798cef7262e556a00.nq.gz
    ├── 1632727d02bb1b9716c1e7951f36a584a0b06703.nq.gz
    ├── 164773a8b15adca307af147d25218cc2ee295744.nq.gz
    ├── 164e9b0df2c8c7ba549743ad22034eb9f005a502.nq.gz
    ├── 1660e51daf2eafe50ada57e4c4130edffbceabee.nq.gz
    ├── 169a15eebbd352b60e015dfc69607208191585e3.nq.gz
    ├── 16eb0ee47e4ca4fca59f6bfd71774b09479d9f0b.nq.gz
    ├── 16fa7ccaba45bf3a79623a27ce34a8ce6dce9345.nq.gz
    ├── 1722f14c6823a197e31d0f010087522de6b94a89.nq.gz
    ├── 173eb1dbbd98327fa846d1c446fc680da4bfeef5.nq.gz
    ├── 17481193ef1bf7db7dfb53e5a4d9208c5b018506.nq.gz
    ├── 17adbf0f4d3584cd07792a5013a9ac1315779719.nq.gz
    ├── 17bc12c50f5d063febb576940d7d30ccba76bff1.nq.gz
    ├── 17d34a4c78b3f2ccde0140fd09ea76b46be81ea1.nq.gz
    ├── 17e94f3510c7436b5285639bf05d519d748aa109.nq.gz
    ├── 18085ceadc2d7301164d40af1759b666e848257a.nq.gz
    ├── 180d1300f43db8c7084b3615539ffaa34be5ffff.nq.gz
    ├── 182e070b8418a3deec5c045c417b343a7c4d2feb.nq.gz
    ├── 184927f93540172d036d4078efacba542210fbf1.nq.gz
    ├── 1851bbf12c931803dea21e5bc58301f114704cd8.nq.gz
    ├── 187b2cc8239e695b7fb37f37ec6bdd03e3abdd9c.nq.gz
    ├── 18a33607e8c7a4d24f4641eb57eeaca3deacc44f.nq.gz
    ├── 18cb1453a7683255ded2ac1aab1f7aaf642f705e.nq.gz
    ├── 18e104df789aac12fc2d482c85a8d2f4a13b60d0.nq.gz
    ├── 18ea31884ed8e06fc30f494ba5abfc3b79919374.nq.gz
    ├── 1919182e0b0dd0853a8fbe43fad0f058ba984cab.nq.gz
    ├── 1967f76e32c6c56712593c2a2f5956d6a72813d1.nq.gz
    ├── 19996259ec3fa38e72bf7c36f985af90901b541a.nq.gz
    ├── 19cd96a651c30704e704951bd3a6c2f70eb7fd0b.nq.gz
    ├── 1a281f25c08616b2543519887ab3e4c6335f30dd.nq.gz
    ├── 1a56ee490b0753712e5e0efa84972286f35bb42a.nq.gz
    ├── 1aa53431a16f391d7f6fe8b9cd888e4907d2dfac.nq.gz
    ├── 1aaf28c32ef19c7ca3630b76f0da28b9bfda747d.nq.gz
    ├── 1abc09db2e0421a001f18e06053c10c6d2bba401.nq.gz
    ├── 1ac3dc91e71a7212ac4f958f3ff2ec7bfe411f5f.nq.gz
    ├── 1aec2cf98125a24b30ffc322b2e43444c1df0cc2.nq.gz
    ├── 1b3698862cabc73c4b8f257b7358a36f4eaad9a7.nq.gz
    ├── 1b4e6ab7e03ca1c7ff0589ac56d8a30ce8644047.nq.gz
    ├── 1b83859752d8fcdb830817d5d6f4af335018edb1.nq.gz
    ├── 1b9dfaad9d515800ad847e6c02f7fbffc4d651a5.nq.gz
    ├── 1be3a53daa0576eb3836b99154f961fc6b1ec2d2.nq.gz
    ├── 1cd57271f0b9703e0741eff58d812ef7761459f9.nq.gz
    ├── 1cd6e20e8b09f784ffa074555cfadcd6958d6d7b.nq.gz
    ├── 1ce142e02350c23d2fe81e06dfa41ec975dd2014.nq.gz
    ├── 1cfd869cbdb1f1ae82715ce4c9ed240851142a89.nq.gz
    ├── 1de25c814ad5c4286612975f481b54f40e11c44d.nq.gz
    └── 1e0359463464a0859695144a6ab6819e083765c5.nq.gz

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

[aws/aws-sdk-ruby](https://github.com/aws/aws-sdk-ruby)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
