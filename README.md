# Repolex Knowledge Graph of sphinx-doc/sphinx

RDF knowledge graph data for [sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx), parsed by [repolex](https://repolex.ai).

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
lexq download sphinx-doc/sphinx
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc7c6f435ad37bb12264f8118c8461b230e6830c
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── cc7c6f435ad37bb12264f8118c8461b230e6830c.nq.gz
│   └── repolex
│       └── cc7c6f435ad37bb12264f8118c8461b230e6830c
│           └── chunk-001.nq.gz
└── blob
    ├── 0027d87f223df11089f1813709aa874613af0723.nq.gz
    ├── 002b3d1f37df4525c01f4a87ecd7880fb20e82a6.nq.gz
    ├── 003c832b028e8918b1816ee35ad79a62db2c19fc.nq.gz
    ├── 004b301461eaf3fce2aa32fcacab0184f394c9e6.nq.gz
    ├── 0052a4740bb9a7707ceb0769bdfd6ff87a3bebc0.nq.gz
    ├── 00730c0a51818becf6d5853f68eadb78d9e24505.nq.gz
    ├── 007a8668575b0b5b5ee8e3893da4e36107edd48d.nq.gz
    ├── 00b736f86006490cec8d5fa48899853fceb1d46d.nq.gz
    ├── 00e5ae59d2c6a17c91a5c6f7009ab7aac76c8fb0.nq.gz
    ├── 01049098d18c9f8b3f903324cdaf22ca7a145b7b.nq.gz
    ├── 012d5d57246f9295d73e09041dfa3a147b3268d6.nq.gz
    ├── 012d9ee7372bb0e72a9514c3ad861ad03fb97d56.nq.gz
    ├── 0146c5d0f39469545856b0b9f10486e4ef2a894e.nq.gz
    ├── 015420d0149c846288202603bc288898f278db9b.nq.gz
    ├── 019cfd2fa1606e1237f56e3dab54921221df8b10.nq.gz
    ├── 01c7e0ba126300d7fe0cfe1d4c9a9bdb101ba45e.nq.gz
    ├── 0237f5abb59e38376a818b45f218f5a3db7b315b.nq.gz
    ├── 02969b63e3132bf6c70db8d6d012e3d41d791185.nq.gz
    ├── 02bc6edd055d693b2c1d0f477129c36f7720e807.nq.gz
    ├── 02cf4d14f539904f229ddcb80752a3b15c85834d.nq.gz
    ├── 0322e5d644e49d872c0b30146309087bc4b52516.nq.gz
    ├── 0341802e5111ad58a05ef6e93e59bfa6e5d3d1a6.nq.gz
    ├── 03445653a069e568327d66629cc59449e13ffdc4.nq.gz
    ├── 03493dda4ff1731e4e044d92526130f9f66238a6.nq.gz
    ├── 03574468baf619f5950681ce930a42baf8f95a8e.nq.gz
    ├── 039fada89774bd3b8a56e4404cc258c0e1b11d5e.nq.gz
    ├── 03d5e00750c814b447baf75e61b7d2240ae83325.nq.gz
    ├── 03def4715984e0fb62e7b870fcf1b7bdaf4db4f5.nq.gz
    ├── 04324a6bdfb2bf820c0cf8d1fc85ae3598061da8.nq.gz
    ├── 04505d1faf1da31b7eb0200b4221527818c2174b.nq.gz
    ├── 0461ea3ad28ef6ad456044f1b2112fa62d64d6a5.nq.gz
    ├── 04831b72dcc45f02df3d4040be5be8e82041e092.nq.gz
    ├── 048808a988eb0311594748c5eef40f6581928c71.nq.gz
    ├── 0494305dd3daa7d9acc2d7b6411db8882a04b16e.nq.gz
    ├── 04a40e21cff4b95f7195a0c47197e905903b5808.nq.gz
    ├── 050e8a09605b09387a99f77bf681999a60412341.nq.gz
    ├── 05183af129861e7a415099b5e3198f529c37da0a.nq.gz
    ├── 052d31ee2d1763a018b9a92a063ea4eebbce9cf2.nq.gz
    ├── 056760ee8aa51c108ce204a42929f9fa06f8bd22.nq.gz
    ├── 05740880ff90ff5d01e2d3515a9cd4dd1ee9eea2.nq.gz
    ├── 05e481b1c0c2ac1b3c3fa1d7d55c292ae4c80d06.nq.gz
    ├── 062c92e966c828b6db22bd0ef306c821b8e2e8ac.nq.gz
    ├── 06ad1692fb11c47c27ca78df0e335d182c508035.nq.gz
    ├── 06bae4b8861f969fe6da46c924e6f445b3318376.nq.gz
    ├── 06d905ceaebbb13051edff8acb699038a00df7d8.nq.gz
    ├── 06fa94cb2c5246d03be74c01a01fffc7721b5c5a.nq.gz
    ├── 0705631f1875dc557e5a5e235ff4fb38ba37ccb2.nq.gz
    ├── 071bf182b55c1ab006d253bc40e46bd71797ccbc.nq.gz
    ├── 0729385a79a465209bd8d4a6d11bc08e45048033.nq.gz
    ├── 0737dae32b75e5541c9a88880637285bde13cf26.nq.gz
    ├── 07421eb6c2dd8ec0bbcc349c1d8c31bd94de9a73.nq.gz
    ├── 0769bcc04524d8209566fc85c17493ae640d1467.nq.gz
    ├── 07a0166d012cd59d47cef0efd451dc4425b7391a.nq.gz
    ├── 07ad00875a4a0e13cdb3c67e74ee5863fe16cbd3.nq.gz
    ├── 07b38c471ba939c3298f207927af2ed6782acc6b.nq.gz
    ├── 07dd0a0a3b9b87600cfbd84c5dcd3809d923902e.nq.gz
    ├── 07fd78516f60e28ab734e01d09c52bfb5c82aae7.nq.gz
    ├── 082f3382cc2b84c28190afdeeec8aadaf1f34c40.nq.gz
    ├── 08416d671dde7278ee36779dff81a5ea057c3d73.nq.gz
    ├── 08770105543e0f8eb8aa8445d65925aa50669632.nq.gz
    ├── 08773c0b65894380845cd5efd3838599c6b9a190.nq.gz
    ├── 08b11db4f6334675ce6540163ecd078ed9cdba77.nq.gz
    ├── 08bd0f093db279ad79139c2b127f57a9111739fa.nq.gz
    ├── 08d5ccebd78f1c04e9cf7ad2182e0116e356c942.nq.gz
    ├── 08e0abdd61b93c548188596e21fc4dacac6fde94.nq.gz
    ├── 08e5287c9515365ef391694151703f681337ff3f.nq.gz
    ├── 08ee85d672f240735754050852ac41e05defeeef.nq.gz
    ├── 0946fbe98452a490e9b73291dfe363d1790c1fea.nq.gz
    ├── 0972d5e00475b9100221988a5932934623a26a1a.nq.gz
    ├── 097d79edadeb199965fe8ea3ecb8800eae9a90e4.nq.gz
    ├── 09a4f6e58dc4ec84f40ab1a4dba490049c328671.nq.gz
    ├── 09d1239cfd074aff881c3f09102965923ed4873d.nq.gz
    ├── 09ebc75bfbe9e69de2d57367b45e8df51130c91d.nq.gz
    ├── 09ee67efc54cd6234749a33debbd7b099cadd8a8.nq.gz
    ├── 0a103cd3ee3b5230a901ddfca3a35b48fe2c44be.nq.gz
    ├── 0a7d9f382f65f8c834b4a3ea24c73c5cdd78ea47.nq.gz
    ├── 0a8167fcc6a21e89648ae15a7546905f26bba35d.nq.gz
    ├── 0a8829e378cbedc8231cb49f531aebc818990644.nq.gz
    ├── 0a9310a5ed22a1a5fea93d01caef430f2c718cd2.nq.gz
    ├── 0ac2621eb22cc28f0a841c09e99e66d427b6a2be.nq.gz
    ├── 0adcf74df903ace27aeeaf0ed59ce5bc0d701db7.nq.gz
    ├── 0b5445461f37d7d59d38991bade028acaf71e5e4.nq.gz
    ├── 0b651d483779370fcfb40e67148fbf0a97276172.nq.gz
    ├── 0b74be0ba9e5eeba57d2f0c08985470eb699d9cc.nq.gz
    ├── 0b8d83a8f5adcaec1a4f006b11db6245ddb1ba42.nq.gz
    ├── 0b97a60fc0ae366619c86e9e8fcc9ee895f48b10.nq.gz
    ├── 0c319123c30ae4d51332002ab5b0668f358933ae.nq.gz
    ├── 0c5c920332a3784c71232acfd889fbf6426f977b.nq.gz
    ├── 0c6bdbefbcd8927d5f8028efc2ddd372b2a329a9.nq.gz
    ├── 0c9d57b2c3359649f00a0b6ce6856a08cf08da37.nq.gz
    ├── 0ccdc106c443af06cd5aa5ecf35f19a14067d907.nq.gz
    ├── 0d2c29d13fb981971d41d08a534b47b6043091cb.nq.gz
    ├── 0da8306bcfb57f38c9ab1320838f71ea98047405.nq.gz
    ├── 0db7cf03596b6e34ad90797cc04df50eeeba9f19.nq.gz
    ├── 0dda7cf32df9a7612a58df15ac9370581505c5c6.nq.gz
    ├── 0ddd906051c8404bf9f5d555bb45be974ba7d80c.nq.gz
    ├── 0ddfc74646716f43c80d39bb86631e4b3dfbc589.nq.gz
    ├── 0de1e7e84c03e45649ff64c291c047eb75adc424.nq.gz
    ├── 0e0c487d9f3f9f08032ad611f7a9db52537daffd.nq.gz
    ├── 0e3da9103d0d1b29f3c44766979b651951862d0a.nq.gz
    ├── 0e4794058f84081a4cb12538188d5c6a467586b9.nq.gz
    ├── 0e7b065549496dc0901d03a98ff91fc7bef2b266.nq.gz
    ├── 0e7ebb6a7b00d9e82a094ff89d5266f28b4e7b73.nq.gz
    ├── 0e9d22ca9d6bfdc3cc0f6967c0ad2b296de1b714.nq.gz
    ├── 0ea7ca3666e7890911bc208114ba3fa2a116092f.nq.gz
    ├── 0edd34a0e3914a5f2edec38afd945a7a88cf4744.nq.gz
    ├── 0f26b2ae00a8a4a15ca5af07edc7ecc94350dca8.nq.gz
    ├── 0f7d6f32e758072d2cdc993910cb2eb207bbaa51.nq.gz
    ├── 0f82e661be42ed2b530ff75b18e18a75de738099.nq.gz
    ├── 0fbd08e1a2d41932bc9006f7ff17ddd68e759923.nq.gz
    ├── 0fe83e0ff34ca08631c7d94e5625492a554369e8.nq.gz
    ├── 1069b4cb4c30daabcfdf3d29cd36a06b6e50c801.nq.gz
    ├── 106a16cea4b6fab2746a6c9aa3225f1487a17260.nq.gz
    ├── 10793aaf5e20a4f9729c2c17026531dec4101e53.nq.gz
    ├── 1081dc1439fb984dfa7ef627afe3c7dc476fdbce.nq.gz
    ├── 10d15210d8fcd2055f4aa3f0a73dab9ee617f409.nq.gz
    ├── 10d885a0800e0a05ca886ba9795ef3fdc6005164.nq.gz
    ├── 11023d2f62e2db6381c666d019e839fa7530148a.nq.gz
    ├── 116644007793afc2e8b13f5e54f03bdc1c6c4438.nq.gz
    ├── 11714a36dd9b023d770624a60a933db434fd8edb.nq.gz
    ├── 1195b0442ddab1471626a35b207acce2a98040e7.nq.gz
    ├── 11a395ed6c49c109760ee7112850dfc66e648add.nq.gz
    ├── 11e3d6a7341e9ea66215db252cf496b0383d91b0.nq.gz
    ├── 11f13fb83c41753f60407ba37eccec003292c0f1.nq.gz
    ├── 11f287a18aaf99b4a1c6bd5ceb8b6088a33fb8a7.nq.gz
    ├── 11f749dc24d9d2c4109714e4b0ff7cf75336eb44.nq.gz
    ├── 120066b5f35eefbe817baddba30231880e23f208.nq.gz
    ├── 1203d5dc5ccb999172c546924baa240c31b930fd.nq.gz
    ├── 1220192528922142deaefb66798827a00fb4359b.nq.gz
    ├── 122fd8b7b474fe070a54c8d0da60f73bedf8e746.nq.gz
    ├── 12c10622d86b05da2fdc769c18bca48d87047951.nq.gz
    ├── 131cadb4f41be92df8347728de76286440c1ad26.nq.gz
    ├── 133206ed650e8362aed93eaef9b56aa4cf370bcd.nq.gz
    ├── 139be3a05349355080e64677c69801b3f4caa424.nq.gz
    ├── 13d626301a9b483234159b4144aeae2e4d526a85.nq.gz
    ├── 13e88cea007d91a5423bfa3486ded7c6885f88c1.nq.gz
    ├── 140dee7ea99e56c08192cc37b154845b4c8d526a.nq.gz
    ├── 144d9958d0dca097b29c680e9368b169f7700cbf.nq.gz
    ├── 149a85edd679038d9f5f7d2ff38c96f16f1e7c68.nq.gz
    ├── 149b89d46b414e99a0fecd21e5aab1874ae4fda8.nq.gz
    ├── 149e63c1a321dde2a5bc742deadb40453a38e7a5.nq.gz
    ├── 14beabd289bb3a02b98669fb146177512c07c9d7.nq.gz
    ├── 14c34d0b705dbb06c086ccdeac1e6d36351f79d3.nq.gz
    ├── 14e7266d38a85a73e9dd9ad4a471aefae32f9623.nq.gz
    ├── 153cfa141ce6c91ba81e6fd0152a443273dc05cd.nq.gz
    ├── 1566aecba241006dbc71be74a798ebda110fba8d.nq.gz
    ├── 160fb267a05899eaa5546eaa8821f8445df035c4.nq.gz
    ├── 16170d4cf5ed8b6371a6bf2b86b75cc1eb591eed.nq.gz
    ├── 161b285a290b01abf8ec12b2683fd9bdfe5c95d2.nq.gz
    ├── 162b3611aa4ebe4d3ef58f2fe4b016f93a187f9b.nq.gz
    ├── 163a470b818bdddffcef297616ca52430fc5dd86.nq.gz
    ├── 165960f7e9db17528f7710d4bd0caf4c6397f8b6.nq.gz
    ├── 167c7aab668aedfc7b0f263628e8c1b78ab95ef7.nq.gz
    ├── 168d3c1efe03eee030e092c609435237cb797b74.nq.gz
    ├── 16c49b01daa227ba072747bd48fffaaeab8100da.nq.gz
    ├── 16cccce3ce06b56e71a84ae2d4ae92aa80bf18c5.nq.gz
    ├── 16dc7ed1e71c5ca404ae758e96d7639c808ec29a.nq.gz
    ├── 16f3a8849cc47977a4660814fe5e287e2b484046.nq.gz
    ├── 1711a889cef91810ddb36f7214621f9676246b09.nq.gz
    ├── 171b0792bbeb448e8c5739be094a4681bcd96bff.nq.gz
    ├── 173be97eb63e0b50a9d0427c7bb2ac570b6048cf.nq.gz
    ├── 17445b1963591a3395a8b5a3c2549136ee268877.nq.gz
    ├── 1747d27ebcd0eab66044d8a101a2b8450404742e.nq.gz
    ├── 175e3ff07d99b236fbb1a9dff0d5bf164f11c4f8.nq.gz
    ├── 17617ab5929e5b62f9f9feace217f24947fadc07.nq.gz
    ├── 17958dd31b67acedb4fbe87b464693995512229d.nq.gz
    ├── 1799612bfdd6e4a08d16bde39191e02e8810b5ff.nq.gz
    ├── 17aa7bdc45337b72cc1b19815dad6f2e84ed9df1.nq.gz
    ├── 17cdbc057e157a76ff4d08f2559d8fe061e16df7.nq.gz
    ├── 17e3d7d0e494a4d8ce49cf25c2913de48af48c80.nq.gz
    ├── 17edc1f3dcb745c82119fe319533cc6ec85794dd.nq.gz
    ├── 1825941779cdee28c3c7795fe6ca2ea7c45af202.nq.gz
    ├── 182b9d5edfb4d950aa3f8429938584df319a3713.nq.gz
    ├── 1834b3ac65021e2ce3f28f7210312fd017ce5a73.nq.gz
    ├── 184bd2bd8e4aad77b7b9957b383d9226c8349449.nq.gz
    ├── 186e71e79da6243a00e3671641417d792e58eaef.nq.gz
    ├── 187082ec98c3d0f5800451e2fc50496c4ab2e54f.nq.gz
    ├── 1888f6679d13d841feccc46bc9a81d5b2a69122f.nq.gz
    ├── 1892f94d6e4965b8b93b551d23de9e1b70c61c4a.nq.gz
    ├── 18f494fe10977558e32a6fe23d0c861ca64e7a60.nq.gz
    ├── 18f97f4a0fdeafd131e4028e446a0c5a7e4922f7.nq.gz
    ├── 1918ce732e245c1e99a3fc14db702ff7473f43a8.nq.gz
    ├── 191d0f5982afab56c220d92c4f234d6020bb08fe.nq.gz
    ├── 194916122cd3bb43c917305af760e37b7082fe15.nq.gz
    ├── 196307ae6c81c0c511af5acaa9db67b367705d0c.nq.gz
    ├── 1965c75f4cf64ab57bb0ca9917432fe3ea4e9aa6.nq.gz
    ├── 19b98ae12c2e2f88c89b9dc0a6f4bfd6f5c2305e.nq.gz
    ├── 19d4fcb5feae8922fd6eba2620eaae620f318901.nq.gz
    ├── 19e92eca7a61a23ab1e88d352adab37b63903bca.nq.gz
    ├── 1a117379ffca18946141e92c216651be019d72de.nq.gz
    ├── 1a12f2c2b54b37366dfa3f9f0fddd0cdbce4fd71.nq.gz
    ├── 1a1edc46916b7d01f9b601c6731d511c61c9bf07.nq.gz
    ├── 1a33f3970b4ac66b294580a069f7c1aec0f0b7e7.nq.gz
    ├── 1a36bb736d45149cbff3ed7bff5815909984b714.nq.gz
    ├── 1a527578bef26123ab0192791bd3cb217b72d484.nq.gz
    └── 1aa370cce8def83e69913488df12d262b946531c.nq.gz

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

[sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
