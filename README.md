# Repolex Knowledge Graph of aio-libs/aiokafka

RDF knowledge graph data for [aio-libs/aiokafka](https://github.com/aio-libs/aiokafka), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiokafka
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13a6400024621371254f32e17bd489313dbcc63f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 13a6400024621371254f32e17bd489313dbcc63f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0119f3182959b7af894eae60208f233793ef36de.nq.gz
│   ├── 02140d60b2347e712fd6d9ab3226da487f3384d8.nq.gz
│   ├── 0241f64dc69b76c9a9ab0f313d424480a8d8d644.nq.gz
│   ├── 036790bea73eb15762d90bed163e0890a49ebba6.nq.gz
│   ├── 03d104a59b187b53b6eed6cb87d321d3a2b1ccb7.nq.gz
│   ├── 03e609c28790930da7b99888d74acee63f14bb21.nq.gz
│   ├── 07ff1d377378fa6859b111b9dd9ba781a6f9ee54.nq.gz
│   ├── 08dbcdc69e81d2ed94c0a76c267860a3c5be5012.nq.gz
│   ├── 0980a1dba4a4a475bb1fac52959a6458b462767e.nq.gz
│   ├── 0b2aaccf4da4cbadf75502d7d8a306b7fc2b6d5e.nq.gz
│   ├── 0c6905fbcc92d073c093811699aa18871936083f.nq.gz
│   ├── 0cbaf31137a37163249bd90a69a96111f1aeeb36.nq.gz
│   ├── 0fd9368a6d91250aa0e16c5692d4837f6fab91cb.nq.gz
│   ├── 1016bf54e2bab482667715536c1fff1a3281b4c3.nq.gz
│   ├── 1029f2e7b0b05313f3eb34b147df22a1763293ca.nq.gz
│   ├── 109dbf9802d94fd2083295ad00b706ac7a05b2f8.nq.gz
│   ├── 11a98063c02746d4c6870b81d6d10a8b677d3170.nq.gz
│   ├── 15d99e1c55a471274cef8df53417ff6e444da8b1.nq.gz
│   ├── 18cddc8455ee3a158c38db1737f7ec5792c6ae75.nq.gz
│   ├── 1c61c672cc375a5c1f37db57f77cddc3912e8c87.nq.gz
│   ├── 1e9f90e78bf28ef3d7451b958b050b5145df9388.nq.gz
│   ├── 1ed687beebbefe1f12ef7b6da81eecbeb7969bf8.nq.gz
│   ├── 1f46e76e84dcfc02ee9746222032223ce9533f86.nq.gz
│   ├── 20d054bdc3758e16568f85a9da822f78f55af7ed.nq.gz
│   ├── 23b1dd23e85de26732e496f8f186278619496a4c.nq.gz
│   ├── 24350890b14040f7fe151a46b0c1eabaaeeb16fe.nq.gz
│   ├── 25ee26b3d45912350e0bd90927eca5f22c9f219c.nq.gz
│   ├── 25f97a25f43652c7636a7249d18abcbcb58cd39c.nq.gz
│   ├── 26c864de3d336a704905c1db73c95826ba59ba6e.nq.gz
│   ├── 28c73322610b83a866b472a343ced52b8818ace5.nq.gz
│   ├── 2986821f675766d8688d714c5cfa8f0ad113dcc7.nq.gz
│   ├── 2edba90d6a28940ec2b88c12a705d6b652b074b7.nq.gz
│   ├── 2f63ca35db222e0094cd040a39ada607453586de.nq.gz
│   ├── 3032fedeb903829498eb5c58d9e3a0103853005a.nq.gz
│   ├── 308307e183416a6eaf7c64950d24f84cda1782a2.nq.gz
│   ├── 32543b4e92aa9abb6f1374c23e4bcb280fdbedf4.nq.gz
│   ├── 330703e9cb07e01e7ad12bf32f92d28f0f6ee611.nq.gz
│   ├── 33198be9bdc90c68ef5f088ab879d04e3e76184d.nq.gz
│   ├── 33af4e755df0be9f538dd36df0f9e3bbdcad21a2.nq.gz
│   ├── 35180f7de33ca78b435fd0dcfda0d45fa2a6f155.nq.gz
│   ├── 35c7a2c5d22feb282facf4180353c92c0f019281.nq.gz
│   ├── 3822067b8fd6f79edc8a5b120c974fab18e7b762.nq.gz
│   ├── 393cbead74d84e259f9a0a4e7824942653281c63.nq.gz
│   ├── 3ba19d5bf81d694a74aac394fea50e68b4bd8996.nq.gz
│   ├── 3c46c2299fe8f33d359c725f964ba857168a5c8a.nq.gz
│   ├── 3e2701869040f79a74c61dc32143c405ce55a96c.nq.gz
│   ├── 3f51a2e2eb66c8c5a40741cbc0153f8082159653.nq.gz
│   ├── 40a945e2a7e4c4e9f55cf9f45ae019bef5f43f55.nq.gz
│   ├── 420eb93bc49ca0873ae969c33450b53ab937158c.nq.gz
│   ├── 431544508695f0943bd502e93038e474a505a748.nq.gz
│   ├── 43c35a474096d1e816f9e3b4190ce9f31e1c3ea5.nq.gz
│   ├── 493e67f67fd7ad8614f2cff5d413c8509a24587c.nq.gz
│   ├── 4c75acb1341913be8b010d944befddfe7bc7a36b.nq.gz
│   ├── 4d1538c374b3bb19fdf49706d09ea6fbd97af2c3.nq.gz
│   ├── 4d60508885fbb639dc7d4f37881d0e47fada273c.nq.gz
│   ├── 50387dcc111668ff41b52e0ae36b6c8be933bd50.nq.gz
│   ├── 510480ea990f88862abd980affcc282caa629617.nq.gz
│   ├── 5113ef389aa3ae433c983ef275de6562cda5d78a.nq.gz
│   ├── 51e04e7f0757d0b6d221bd0bf4cb5310f8c72a65.nq.gz
│   ├── 53d1a3ce796a8ae805b4c57cc3332c1d1ad476af.nq.gz
│   ├── 5435ffe96408f95f6459d9be25fd3ac72adccc5c.nq.gz
│   ├── 54546268141303657daf294acbc610cb3369b9ff.nq.gz
│   ├── 55d5a48d52ebdc4deaa8d640971610cf17442a2c.nq.gz
│   ├── 560ebacae6ce7be060fd1dad093aa37644b6df03.nq.gz
│   ├── 5650d95b17fe79b149477355543510709aceee0c.nq.gz
│   ├── 5abd950821c5624721de0ad3d61bf644b05dd772.nq.gz
│   ├── 5cd9fdde00a1444fdd0a8f475663c7f951bac419.nq.gz
│   ├── 5d37496c62d373cfeea749c61dcf2806cdcf6c26.nq.gz
│   ├── 656c70311422bd4da7b34bc64b8dc5406df6e681.nq.gz
│   ├── 66114710b192c3a942434d8a800c64b4f50fbc7f.nq.gz
│   ├── 66f0b3b5a70c3c031cdd458e9e24ca948f1e8bea.nq.gz
│   ├── 69ae269fbe802a3ba15e446598f23d648f5b898e.nq.gz
│   ├── 6b2e325cd2cc9a21c0994de4999a880ca5f11c33.nq.gz
│   ├── 6b3381356fa92b991180a68a4e6ae1d3eff0c0fe.nq.gz
│   ├── 6b415dc1238c6bcf6c0e333c795691f8adb29a32.nq.gz
│   ├── 6f5cea74349c6a9bdd7cb8e503871d87f3671bb4.nq.gz
│   ├── 70ea32b46df6f4d3b046febf272a572be0f6f12d.nq.gz
│   ├── 7136e0abca1493fc0dc99051d8c043b646823b48.nq.gz
│   ├── 7139529ace8bf5fbd1a3c58cafdfc7880fbc7a2c.nq.gz
│   ├── 738f870129953fb90dd6eca2d3796ca05138ddf3.nq.gz
│   ├── 73b6e9b975799c5cd4de96d0516ee284255dcd10.nq.gz
│   ├── 75d807b8bc5f3c97d04a4672c8cb03cdd584a27b.nq.gz
│   ├── 75f97b45e42195398c198bc66960620372d604ce.nq.gz
│   ├── 76edc146836628a107db741940a453df58060c15.nq.gz
│   ├── 772de8abb921b342e1dbce93e1332127df82c252.nq.gz
│   ├── 77d13ce7eb60ac9a76677e64f40f7a043bd8c692.nq.gz
│   ├── 7ae80a4f8bd1c8beaaa1eb8b206dd74534a035b1.nq.gz
│   ├── 7bb3d44c674b3873deb30c845006756d0d1f5abf.nq.gz
│   ├── 7ce32106f8a4c19787f91fcc08d0969d31778a65.nq.gz
│   ├── 7f0b8fb7c07ffe7aa31629e3316cf4bcbb8debf2.nq.gz
│   ├── 7f1044131bbc48aa7bc671ff5fc4f732fa3f5219.nq.gz
│   ├── 889160fdf9378e37f14fbdad774f4bbd553593aa.nq.gz
│   ├── 893fb4c1093985241775c78e4ebfcc0f17cbe1eb.nq.gz
│   ├── 8b2d5d034f30494d16cff5e20ddc6a37c27c766a.nq.gz
│   ├── 8c37c369b79b83e7825405a25dd8d9b924327928.nq.gz
│   ├── 915a47f7c2ae457e5c705c61ec5ce1ab4a323104.nq.gz
│   ├── 922a88bbbcdd49d2f6b0434329ad268555b09745.nq.gz
│   ├── 9268e2975d38246c6ec05bf2c887c1dbf2c17970.nq.gz
│   ├── 9303c1ae6b213d401f69171a2e4814d22ac9612b.nq.gz
│   ├── 932dbd750ae6bbe500c5870d09f3148a03ce201d.nq.gz
│   ├── 99792ed899083388d1ddd08b7458c819cef27cb9.nq.gz
│   ├── 997e31e5e916dc89ce3696ed14197ea5758b5a4b.nq.gz
│   ├── 9b323c857915e44cb06ba3714c1c8fdd5ff667c0.nq.gz
│   ├── 9f56f98b40fe8a3695035d0838703649cae593f0.nq.gz
│   ├── a1632e45b8f16917c6cd387f2820d252e9613570.nq.gz
│   ├── a51429d8c7a89257f7e5c9d4e9edd36e3a322d71.nq.gz
│   ├── a515ddb272756bb0ab7f800ea5625b054909df0c.nq.gz
│   ├── a65295943c9125d2931b7422072d29d3e62dd5d3.nq.gz
│   ├── a90f383020a559e7caf53904934352bd3b6637d7.nq.gz
│   ├── aafd01a9502fa8adb4e4b58a0bec5bd10723e03d.nq.gz
│   ├── ac7712fb8d58cc8f89844dbe1b5365f45fcdb15a.nq.gz
│   ├── ac914a71be4b91c07ebec7537fd8a5e5a3053efa.nq.gz
│   ├── ae3215c6dffcef6f702bfdebd0a02583adcbb011.nq.gz
│   ├── af0a7cb29c5ae19e6cbf17448e821dcd092f969e.nq.gz
│   ├── af253f4da283e477963259d6da3642d8f9cf31cd.nq.gz
│   ├── afd89b51ca43203a86df928e71b840ff76095c39.nq.gz
│   ├── b1934feb6e650eddc51c99c54c5a2e31d46a15eb.nq.gz
│   ├── b1a6cfc3ce0e08821f6785d95496ca836c0a66eb.nq.gz
│   ├── b1a81eadf9fa8131f44ea2e71e22af0fc0fd3a11.nq.gz
│   ├── b53cce4cb9773b73e65691a5c4c7ddb0b4ae0890.nq.gz
│   ├── b75547a759f7a01d23ca7d33392bad77deb474da.nq.gz
│   ├── b99d5e51892061908a0c3f4e7a236b9ddcdb64fc.nq.gz
│   ├── bac1b9c8c59a7be567894653c82036a96ed4aeb7.nq.gz
│   ├── bcbaa3484092c516fc042a512e1fa034acda322f.nq.gz
│   ├── bde25e2fdf99fdbdd37d2bca602655bd4496ccd7.nq.gz
│   ├── be376bf3925bcd3a123f1d2d1c386e6813a35e24.nq.gz
│   ├── bf39958b2187d4cd350a384e6239b54eeaae2cbe.nq.gz
│   ├── c0099c8db31d3e2ad77bbc3f87150ccab11ee055.nq.gz
│   ├── c30c64c068898e960b620a0c616e4c7957cf0a17.nq.gz
│   ├── c466357e0a6ef8ae79d8927ce1f0f24ba03c91f7.nq.gz
│   ├── c6144841dd0264847ec531225251467613c695bc.nq.gz
│   ├── c6b7cd39f7270c5ccddc53a5a1a955972765f416.nq.gz
│   ├── cabb486d9ea0671a1f08559fffe50780e739cffd.nq.gz
│   ├── cdfb9705c2bf607818d5b26491e3d4355cec93af.nq.gz
│   ├── ce324a868b5abf658e1c74e9680739a672e80799.nq.gz
│   ├── d16007ab0536b4396914d73ab2376b32e7bcac34.nq.gz
│   ├── d5fce397865cf7d74eac8020fba5e4a9209ca3dc.nq.gz
│   ├── d6b77a9fe2f4944ebd1791d02127d9f50238690d.nq.gz
│   ├── d754356e39a218751dc6c9b032447c6bb6480c2c.nq.gz
│   ├── d8dfa40923ab54798275934650d310e6de9e4aac.nq.gz
│   ├── d92aaddf574b34ab1663237c9273d4adba10b026.nq.gz
│   ├── d941e135d10d699181a0d6b382e5a01e4022e996.nq.gz
│   ├── da2bc4527816332325da4112099111437efecece.nq.gz
│   ├── dc5cbdc3b5da9f0ce000ee6fbd9e68498fcd0b4f.nq.gz
│   ├── ddb86889bd52745ec39ed768030617082d260905.nq.gz
│   ├── de058323bf497b3022626c58271321f504736058.nq.gz
│   ├── e001b5713eafc71455f00f9c849ee0759241f91a.nq.gz
│   ├── e0bf826e03e2293317891b56a630e4e760562960.nq.gz
│   ├── e19250652be1df1e6b122ef25bc1c8900e0bf00c.nq.gz
│   ├── e34365d2be379f4468875525448beee722ff241b.nq.gz
│   ├── e3f5c5484e1c4cea0e7aa667d26ceb9455570f37.nq.gz
│   ├── e517df14299dfc1614519898193866d1fd9b935a.nq.gz
│   ├── e5c2963f215462de83a26822b5aa1d994f6dc368.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75c92fb1e894a4a151f92cf533cc2878b8a4f1a.nq.gz
│   ├── e9175ad3e49f2d35c0710245a14b0a3ed580987c.nq.gz
│   ├── e9d0e673f3ee0c99a2fab968e74c963b066fab70.nq.gz
│   ├── eae23b475011796ca8ab839af49f6723ecd07839.nq.gz
│   ├── eb161e2dd6fa5bba5d43feb529cbaab27c5b688f.nq.gz
│   ├── edf392e6ccca65b5111aa4cdef9facba79250be5.nq.gz
│   ├── efc6720529f8c71ac43c174fa9ef6d9b0d0bf02f.nq.gz
│   ├── f0c47ac7a98fd30e939c5792d1249b844cb97fc2.nq.gz
│   ├── f116c41cf127f05b2a711e6ab48be53137830f19.nq.gz
│   ├── f1d6b3688e75415367970298e3712270d844efac.nq.gz
│   ├── f2ca2acb5f1d04da5ca62515bc1a66a29fddf0cb.nq.gz
│   ├── f2f6a5f2bac880d42f502337d8ae3ccf1fcfc76c.nq.gz
│   ├── f456e59d7e46a630b4ad49fda0fc564f8f2b2280.nq.gz
│   ├── f57e1d51bdcec8232aed55b13fa52a327ca4172c.nq.gz
│   ├── f5f8841670dd743328f16378ad6575cf4121fe81.nq.gz
│   ├── f6254090f4cb6f1b781d0ca51a6ddea7f8c4adb3.nq.gz
│   ├── f7d99612c9c9c098ecbb2d74cd3945dd9faaa99d.nq.gz
│   ├── fa68f1583e16432f796a2629b414f17a50d9a974.nq.gz
│   ├── fb750083a32d8fa0cb016d479950cc5f88e3a41f.nq.gz
│   ├── fbf3ce733eb847da48005371e500fcbe68f71593.nq.gz
│   ├── fd3c27d70d0df30556dc817f9ca1e493fcbe7123.nq.gz
│   └── fece6c97f55611cc3042b91f76c8cc967bdb7c0b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 13a6400024621371254f32e17bd489313dbcc63f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 184 files
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

[aio-libs/aiokafka](https://github.com/aio-libs/aiokafka)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
