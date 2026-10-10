# Repolex Knowledge Graph of BerriAI/litellm-bench

RDF knowledge graph data for [BerriAI/litellm-bench](https://github.com/BerriAI/litellm-bench), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download BerriAI/litellm-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 642704a95555bc0fc25dd73017584345c8eedb3b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 642704a95555bc0fc25dd73017584345c8eedb3b
│           └── chunk-001.nq.gz
└── blob
    ├── 01c20712460f4c446c3bd67743c217362b1788eb.nq.gz
    ├── 01c65fba22f4648d3824fb82687b76102c814827.nq.gz
    ├── 03f26a74030c2bd90acaf0ac89f153504477ae65.nq.gz
    ├── 04b2c1f51f564edc04488ed0c5c6fae002acee33.nq.gz
    ├── 04f327a6618786cf2c644896e9e03208854bd0aa.nq.gz
    ├── 051521bf35a2542f796d372898f9ca26c37319ce.nq.gz
    ├── 05e0667b2076114312f3d89a38a5a3f2b9be565a.nq.gz
    ├── 075a12e4b4c75f9364bf3960aa4ee79d68e03128.nq.gz
    ├── 0868498947a367e2358dc33b261025cc647833fa.nq.gz
    ├── 08cf899d8e8c404b5b4248d0e64e21afec6e9653.nq.gz
    ├── 0b3bf39f2388911539f4966ad8616a2e76956216.nq.gz
    ├── 0b4118103d7c209f0f33752f7958c7ad58938947.nq.gz
    ├── 0b9a0704aac33402f909cbe70a8dc626056af1f6.nq.gz
    ├── 0c9eb871ab8ea6b8573174ddb91c0e611d37528b.nq.gz
    ├── 0d5a9ffb0100c0bff97b238a577ef14b947f549a.nq.gz
    ├── 0d96e6f1d3f44ae066ac20d61fc0870ecc730549.nq.gz
    ├── 0dc752c4e99a1ce6291991f45ea58aaa86fa139d.nq.gz
    ├── 0ee628b8dba50e853ed4afc21bce2c1cb73f8c8f.nq.gz
    ├── 0f08ddf8524e1ae59ff3dbd8a22226e42214bd4b.nq.gz
    ├── 1044c0cf3c242705bbf8eecb6c6a1bec1f094e27.nq.gz
    ├── 10763fc6abaf4964e1a866b20c54f89a2d0c589b.nq.gz
    ├── 1458134f4c4882b1417ff1b7e959df5817869f66.nq.gz
    ├── 160a1ad0793c958852ac727816adf9d3453be03e.nq.gz
    ├── 165bd86af0efa0ce14ea069d55d3b69e5dab3376.nq.gz
    ├── 1816cc59e21439a92839df0df2cbae0979448dd6.nq.gz
    ├── 1835dda41d58b5094a46a83dbb080b9d8954547a.nq.gz
    ├── 19258248abee01089566f42e9001823cc29bc04c.nq.gz
    ├── 1a1443e227ad1ddd6a0734d8b6d170dbfa8f174a.nq.gz
    ├── 1a87b796aef788d4cf90f5157dbb0f295c0ed9f7.nq.gz
    ├── 1b541c3b72d05b98a53dc62aced9bb42ff6588e4.nq.gz
    ├── 1bd30ad47adb7e14522eaab2649994e106e2d780.nq.gz
    ├── 1bd9c744fbfa84373c423690ddb08cc543ef11b7.nq.gz
    ├── 1d7b9418a35a70f898811a7dd41bf0276d32de3b.nq.gz
    ├── 1d9a391e8b853edac1e5825c99b35c90660f5430.nq.gz
    ├── 1dda2ec0a07eafcf19c9bdcd1fdd25439513e5b4.nq.gz
    ├── 1e7a60329ff7c1586b296f3b2ccc188497955abe.nq.gz
    ├── 20d830e854ac74e0334e41aa10bf8edd0b190a4d.nq.gz
    ├── 21379a17e97edbc53b474bb8587ce6cc6a0b6ec6.nq.gz
    ├── 21672e672c3024710c4aeb02ae786a367c391813.nq.gz
    ├── 21722d552f98dde0541756dc361b17ffe189bb83.nq.gz
    ├── 23329b07a8260d9f699761a3c93e7e4ebb37397b.nq.gz
    ├── 23eb4cddfb590f13414683314f2757da25b9aa14.nq.gz
    ├── 244db8d99be4b27eb4c8e4d74473be737c785195.nq.gz
    ├── 24d052395f5a9bcd2c55efb7392521940a95c7ad.nq.gz
    ├── 24da22499bf559acc6a85b3bacd617b27d52a7d9.nq.gz
    ├── 2669454399649acb2aa5721c0946b9cef58c96ad.nq.gz
    ├── 2910347a168b91e6d1277e073e8e88b5cb6bb521.nq.gz
    ├── 29bcfc1cd94364660653c92ce5c42450014deabe.nq.gz
    ├── 2bd0d46ab172dad1c72ca57f6e4277ef5fa0eb90.nq.gz
    ├── 2c286b2b40f9f10e5ba48bcbcd605c6129d91d1e.nq.gz
    ├── 2d23d672e86aa752ee53ea72fe7445d435bb9fb0.nq.gz
    ├── 2d43bfb01dedb74a4cb3485ba595b891a9616bfb.nq.gz
    ├── 2dc6a9ddd1fa7072b3f5ea6306b7309e7bcd3671.nq.gz
    ├── 2e0fa54831547cfee3d2416b6a84cb56dc857416.nq.gz
    ├── 2e3fa5c584d735b133910cb5481c4d133042e604.nq.gz
    ├── 2f1c210246ba069df7632b5653a963d437134980.nq.gz
    ├── 32a7e6d8b55911155100a1271e3c089c3d234fff.nq.gz
    ├── 32ed1d1c6fc8a84a2996f180390349266c1f4406.nq.gz
    ├── 332eaf6c850be19dd9cc09b66672c8c5f773a5ee.nq.gz
    ├── 34aee2975cdde743085c74d5df83d2aa4af7d2bf.nq.gz
    ├── 350d2a64279d4d3e624d525b28614698c8b4e78d.nq.gz
    ├── 359ffe983ae0b834e5629f8271467ae79f53a787.nq.gz
    ├── 35c9a2506e9b48cee5a348ec3388eddeff8dbf75.nq.gz
    ├── 3615dce1d264c81f8f3e9ab027d18f4dd7906f83.nq.gz
    ├── 36d4d66813bea2100739cf2e4081f8d1fc767b2d.nq.gz
    ├── 36d81fad9ec5469de8ed69dd2b1a34dea4d19119.nq.gz
    ├── 372c6f9f6e67efd1e97f45d43d364935bc5b3170.nq.gz
    ├── 37cb601ec5b54efe5104aab4272c41f211a47332.nq.gz
    ├── 37f29f35ced5421927482ac3fca0eb709d8cc8bc.nq.gz
    ├── 387a24253ad48422bfc8930db8f3a94b68443b53.nq.gz
    ├── 38ca0b13bcdd8cd722662a199ee22bea18bf30c0.nq.gz
    ├── 3a24c58781409f9d42764415c23fea0f057585f5.nq.gz
    ├── 3b42136d49486cc8eb946e02e7c85fd69cebbdd2.nq.gz
    ├── 3c2a4e77a110a3e285065389ca39521edfd5a10e.nq.gz
    ├── 3d9c4d4a902b231eaa927312b30ab30f9bbde629.nq.gz
    ├── 3df3ef1ea4aa3da96b783c2742dd3e9bc37b03a8.nq.gz
    ├── 3f024a393ce55f0d17f1974cae7b067309fb9ec8.nq.gz
    ├── 3f715b33fafd206d74673ed1e046037a18f2bac3.nq.gz
    ├── 3fa2b4e8baecd303370ad919ff40311cec96b14b.nq.gz
    ├── 407a8fa70b3a333f73195ffbf09921f33e51abba.nq.gz
    ├── 4124e9450005d8d5e61fcf38f47457655f0ec1cf.nq.gz
    ├── 42903a52df1cac9cc3465a6246dafd2ef43c3820.nq.gz
    ├── 435c42d363799abe5ca00143a50f048ee18790b4.nq.gz
    ├── 44836bb52cdb48265ca95b60ef25318e9da2eb56.nq.gz
    ├── 44dad2862ffe6696a6e6103f1944fa445350ba21.nq.gz
    ├── 44f16bfc6b5e5c181523e90a5a14cfa1fcbc3f7e.nq.gz
    ├── 453e14b68afd9d52dbb2cc80971bf3898a07e972.nq.gz
    ├── 4611b22488a9b0b52b12c38c23a396d4877c58ef.nq.gz
    ├── 46d908790b579682f16e8f34f84604fcd8c26b69.nq.gz
    ├── 4714893798c38255a8e27badeac2f10b27be1458.nq.gz
    ├── 48bacf20ae0027c801cfe19e0403681072082aef.nq.gz
    ├── 49d51b1f4178f462007bf43e5172e375859cdca5.nq.gz
    ├── 4a7a4726fb6335b2abbfc3ee683cfeba43535e48.nq.gz
    ├── 4b9d868dde56a9e9786f8b7c2d5e223ae882d56e.nq.gz
    ├── 4c5d8f6ff5c309eea6ae4644cd67671081822b1e.nq.gz
    ├── 4d5789f79655bfe5f428216783a19a03e1f1afab.nq.gz
    ├── 4e7a52d0fc4c84ba603025406601850c7761d252.nq.gz
    ├── 4f314c83f3ec3baf646b0f2db498d824d7713a7a.nq.gz
    ├── 50ab34bf7c831c114d272d49b6be87665dcb697f.nq.gz
    ├── 515f7b41646c6817e512729e41e67c1aab4a495d.nq.gz
    ├── 526b50bb29778d9d6a0a793014231a863c5b65d5.nq.gz
    ├── 531ac81d57f64c7f8c2646918033950d36f480eb.nq.gz
    ├── 53934b6714ccbd9d5a3cc23831e58e6d89a90cc0.nq.gz
    ├── 54b16b9bddea40c64ff15fac90c73ae5a68f0e0a.nq.gz
    ├── 561dc1ad35bc8ff5ab25699524992131f6f9e537.nq.gz
    ├── 56c0a8275eb8a842b030559d8417653619be3f2b.nq.gz
    ├── 5722502f8f382e8bf0615670c0f1e7cf3aedfac3.nq.gz
    ├── 5861c00c7be87e14aedd68527185dddbed1dc97e.nq.gz
    ├── 591fdbcbd1318ee014dfc891aa44445a0b0d7e47.nq.gz
    ├── 5bbe5e518297908fff465072024e583df588bfad.nq.gz
    ├── 5c70076d066b63174db9677131247ff838749400.nq.gz
    ├── 5ccf0cb443557570a094e9e4ce6121589b4965e0.nq.gz
    ├── 5cf9297f1c1525f26759ddf9a29a57e8546a11ca.nq.gz
    ├── 5d18aa8e957d5179e9e7c993e3f4d95b173298aa.nq.gz
    ├── 5d88b4673793e8307ec5c0be08f112a5b5a00387.nq.gz
    ├── 5db847a006b772e26f0a26839f2ca2da9e730cf0.nq.gz
    ├── 60361715a671f6988c126d544cb7e47c971a6ebb.nq.gz
    ├── 60854bf83d4642dff2ba6ee67d99c7fdde69d706.nq.gz
    ├── 615484ef534133d5936303f84cf2609dc6184e27.nq.gz
    ├── 63cfc24182e48f97928259ec6758c5c0b80ccd5f.nq.gz
    ├── 6416b59b9a02c874bcc57c46c2146de5645ae6b5.nq.gz
    ├── 642f4f7d3c2b8c6906020945773e150c1ffba906.nq.gz
    ├── 65f54b1d30dbba6a02deee3cdd15503600ef3a3b.nq.gz
    ├── 661b7889991c27772910bdba34aa0c0b2fc4af46.nq.gz
    ├── 6716bba396a805dd234bf27479d9da9882e77583.nq.gz
    ├── 671f2da62a9f3c4fcb6da2fe8311c0131bb04801.nq.gz
    ├── 6739fd947da06ab674e237c1c9ea59b05c8b11ed.nq.gz
    ├── 673e73fcf3a9353a39151072bc7336efcffc29c8.nq.gz
    ├── 67b816b5496e03363c61e06a8ae280c4925c5e77.nq.gz
    ├── 69abc9748f767b954cd035816c4ad40be8d1f1b5.nq.gz
    ├── 6a5986fe4bc6c3c1e5e1f829307b83b3d0510d77.nq.gz
    ├── 6a85b2d291630787274037e8e83f1ea5239f2ee7.nq.gz
    ├── 6ad0f2e6d8347d98316313035126731cc07b8e01.nq.gz
    ├── 6c2ef25ade185f835d5f1b989f25feb686b25cbf.nq.gz
    ├── 6d1e61dbc29951eabb0ba9e429a88345023578ff.nq.gz
    ├── 6f06b789eaaf53ab328fedbbf030dc36ff82ef13.nq.gz
    ├── 6f8bf0b58acc58ff5fff03350bfb28eb16e3a1ac.nq.gz
    ├── 6fac858843325a5c1a58d4e856d86a1448d953e6.nq.gz
    ├── 6fe011e7d1f35cfcf868edfedacfb3e3347769bb.nq.gz
    ├── 700bcbb9afc1afb86cc37581ab8a3abe724ddc1a.nq.gz
    ├── 7189996952b20e8bfbfb6f936bd564eb2e8bebef.nq.gz
    ├── 7210b00c3679cfcb58c5c248f8b47d9fc9a6cbe4.nq.gz
    ├── 738479921178ec0ee3f7c0169444ae26459c94da.nq.gz
    ├── 739925f71ee2af123ce3c4ece06940c71888347d.nq.gz
    ├── 73b9d9de5ae738f8f93eb180b376c8abbf60eab4.nq.gz
    ├── 73e9541c38f9c050c983ae30037139ca8bd9c1c7.nq.gz
    ├── 75cdec5dd2855fb9b9a189ae0b108f230bfbd2ab.nq.gz
    ├── 7959233d2e7a210cc64d217ef20092b301a8a76f.nq.gz
    ├── 7b25938c4afb034c22f1f15063211c9a1c28d227.nq.gz
    ├── 7b9fa59f45e94ee30e7ec1b5134de801f274ee33.nq.gz
    ├── 7bb827801707c9f07f9566ca4fb318affb31f0e1.nq.gz
    ├── 7d3b643bc91429ccde93c96e77fc78c0a88d9a5a.nq.gz
    ├── 7ec7052e672513ade8a01c669a224d943c90d684.nq.gz
    ├── 7f8b49cf58c29fbe5b0ff1c6676387ec5e032090.nq.gz
    ├── 7fb37819a08168a026827c0e8fcdd36cf56d7adf.nq.gz
    ├── 800f0ed406b7afc0269597552b20797f27c0ca36.nq.gz
    ├── 804e629089f2f2596e50ea4cb85f70b449716d4f.nq.gz
    ├── 8066c7c7df9984faeab7b4d1b9154876fabe9c16.nq.gz
    ├── 81236704cd016915dad36fa6bfdee7af15ca955b.nq.gz
    ├── 81243b23d08e1612bd2f5fe156f83bf2994dca28.nq.gz
    ├── 83a8acd014deebf48f965357d5c837164e3f4152.nq.gz
    ├── 83c12d080c8e132a4bdaf03a50db019acc8b2428.nq.gz
    ├── 841f824e8ba5a9cab864e693ee2f6eb933116d2f.nq.gz
    ├── 84467192707cea3d223e1ef0b6108a03024f4510.nq.gz
    ├── 84a0226fc394ada594c03574892779748401ea3a.nq.gz
    ├── 84f3c122b80860d783597b2cfb1a7ce1eba77c93.nq.gz
    ├── 859cc8febb88f666396d766546d74476e0190873.nq.gz
    ├── 8609bd1081f4bd96d94ac375e0ed8599587ef44a.nq.gz
    ├── 86e03cb16c90ece40dff9ceddb9e36b8c166d73d.nq.gz
    ├── 872ce315d9802920bf5006d2dce778a6e0a4a95e.nq.gz
    ├── 87657cb9c147d45a0cd32ac1d30c0324e264efe1.nq.gz
    ├── 87f475ba909e23958a986e418345edbb05d0513a.nq.gz
    ├── 88db450a54b9b4429662bc023ed2d86e72a9870b.nq.gz
    ├── 89ed38b0b76b6d661e591101a8efe392a0305447.nq.gz
    ├── 8a4071ba1c2f2f0c573d51a28a46c7c085e10c53.nq.gz
    ├── 8c98aebb3f91fdcdc3a3727138b7a520bed402fc.nq.gz
    ├── 8cc480636bc476f209a3b2d1dd598d2751eb725c.nq.gz
    ├── 8e019bf20edeef478f36f3c8484ac6453777851f.nq.gz
    ├── 8f0bed6d6e4c69c4046adc9a6ffb030fbdc40df0.nq.gz
    ├── 8f64674ebfee297a8f70a816d49c5700bb0b7d58.nq.gz
    ├── 91f96c0fbde8395a33af0762c1fea133edbdab14.nq.gz
    ├── 932996cbcbd22065c43c9df44eb6cabe14060102.nq.gz
    ├── 938fa081e5c6724f9369e7fbd16981b923672f8e.nq.gz
    ├── 9482d2de5731391fb334835985ead059af585d79.nq.gz
    ├── 94e1c6fff3746339cdddf04f91f1446bd3241f02.nq.gz
    ├── 9527674fa72f66944c07fe04950edd2d5389f729.nq.gz
    ├── 96490590136dd5701d08811320872988bdc5f9df.nq.gz
    ├── 96ed81f57b00efe69be760a201f788b377da8623.nq.gz
    ├── 9723b257661dd2f6a5318a48a0bd81f1dbc06f7a.nq.gz
    ├── 97d28789cbc7b7a5fa7f360db0a5b5dea635221c.nq.gz
    ├── 98088eceb3c41faf33002630b36529df9b4fdfa7.nq.gz
    ├── 9832ace2a25a74d25d1ac241ddf9d8b4d81b44e6.nq.gz
    ├── 99bdce34de634303d4bf85b7190c14d7761e133b.nq.gz
    ├── 99eb0ef42f55f925ea022df4a4693aa4bc619c01.nq.gz
    ├── 9aa4b28975bffcc851dc8f7e45d6a4fc6c18e0ac.nq.gz
    ├── 9acba46993083410cbf6011163528f80963194a9.nq.gz
    ├── 9acbd0f4153db03b3ea00825e960c81909ee6745.nq.gz
    └── 9d1fabb984f516ced037f791d53845b5b1f6b36a.nq.gz

7 directories, 200 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[BerriAI/litellm-bench](https://github.com/BerriAI/litellm-bench)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
