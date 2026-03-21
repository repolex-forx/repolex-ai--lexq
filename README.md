# Repolex Knowledge Graph of repolex-ai/lexq

RDF knowledge graph data for [repolex-ai/lexq](https://github.com/repolex-ai/lexq), parsed by [repolex](https://repolex.ai).

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
lexq download repolex-ai/lexq
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd88d3d5ac5ff31c90c918b3de888f01a3216913.nq.gz
│   ├── lsp
│   │   └── dd88d3d5ac5ff31c90c918b3de888f01a3216913.nq.gz
│   └── repolex
│       └── dd88d3d5ac5ff31c90c918b3de888f01a3216913.nq.gz
└── blob
    ├── 02dba9d84a525343e572c712eebe815e69ece9b1.nq.gz
    ├── 03d1322204f9b219002d7f57f5f6c7e8180fa1c7.nq.gz
    ├── 051c3771ab33aa3b90538ccf58f2570351d5cb22.nq.gz
    ├── 05444286b59e1beacaa41bd4a8ad17715f5756b3.nq.gz
    ├── 057409a952467736d53a4c21e151b4d36b0f8afd.nq.gz
    ├── 057e832cbd5b418146964b58d1bbf03cc39f4b08.nq.gz
    ├── 06479c19cc9b765f0be350ae4136ae5e61ac3758.nq.gz
    ├── 06a13aad5bfe2aae80593905c0016767bef6d8bd.nq.gz
    ├── 06c8c37b02c63881302e1101017163ca8fe46657.nq.gz
    ├── 0785144c33eb7634c4339d7a93d4723afb6a02dd.nq.gz
    ├── 07bab52028d37d2293792b53bcf313278fb9ce6b.nq.gz
    ├── 0800edf91b126d7eca28ac14cb442282f2e8f7c8.nq.gz
    ├── 08e1b59d45a252a09a776dc08ba42f0adfe05f2a.nq.gz
    ├── 08fba43ed334599910a398cbf5f07cb5efcd39ae.nq.gz
    ├── 0a09235a83b80a0611a1a68bb9d4725e7c17f362.nq.gz
    ├── 0a095c9c7ad27781d00017cbeccc7b93e43634cc.nq.gz
    ├── 0b6c5cc813783ac2adc021238e7556730c2490ba.nq.gz
    ├── 0c386d556c47775d13ed0f56c3821b11cd40a130.nq.gz
    ├── 0d14d1e136a63be1110445093c8ca6ee689eaad0.nq.gz
    ├── 0dd0c98f01a4bd9382806678c1e19382dd50da25.nq.gz
    ├── 0e6f860c1e7026a1a1ce549ec0e7fa42fa7f3b00.nq.gz
    ├── 104d83f57cc8f8107598ebf6afd5eed3c1942ad9.nq.gz
    ├── 10918b5002222b2736d32d0601ac5b304b073947.nq.gz
    ├── 11ccb9edda4ade9fd31b56fc369f775dd49dec1c.nq.gz
    ├── 12af374df50fa114de831a2e2dc65eca81d1c109.nq.gz
    ├── 143f85714a07e054c980e532c025010dee81543c.nq.gz
    ├── 147114e862bb0cd27eaa0c19188c65c7fe7d79f3.nq.gz
    ├── 17d532a202beee6cf617ce56ae27f7a0e042f979.nq.gz
    ├── 18dff1e439c648b8e0d1fff6676b1c71310db3be.nq.gz
    ├── 1bdfcd2122e141a469f2d3ade9f813a9806c6382.nq.gz
    ├── 1dcd48af053100a29b95ae1abe97f5fadb735833.nq.gz
    ├── 1e5c0c05929eae7eb94476187d47a83abf14bef5.nq.gz
    ├── 1ea62d97596ab3b7f9c2d68f4fa2f19ca1c081be.nq.gz
    ├── 1f3c34dd273985ae05e3d9ab91c7ac6195ed7a42.nq.gz
    ├── 200c187617c3bdd4d670dc351c1d365d8554a4a5.nq.gz
    ├── 2023412e93727cc8a68775ac51b30150dc2a0cc0.nq.gz
    ├── 21a4ef09ac8b1acea2c636e1a67da5ae96e4da3b.nq.gz
    ├── 21fc9392e619918f2932f8a6f99f7f984bc66238.nq.gz
    ├── 23329cf5390b44cb7b7c85f511fa1bc7be358fea.nq.gz
    ├── 24651a8d77a50eb8f2ea36fdb24e9536f43a1ca9.nq.gz
    ├── 24ab0a4fa80f8894b40d296923800b6f042880c5.nq.gz
    ├── 24f66d7b08e29139fa877f97e5602991caa2c0a9.nq.gz
    ├── 24fe8da5c49e25239b460fdda27ab16f30de9908.nq.gz
    ├── 25ebaa545170bc866423d55ccfd3915d459a465c.nq.gz
    ├── 2884c3d35f0be673e1168bb7017976ddefb03b9c.nq.gz
    ├── 2a38ca572483be47e57be0cb7280e2c705554f44.nq.gz
    ├── 2c25463867439c85874d7ced5ea32f2f5c32390a.nq.gz
    ├── 2c431167456dda731f182cd5fa1b32e9b5f5773f.nq.gz
    ├── 2ce029a06b1290e7e2777f1097c2d1037586a71c.nq.gz
    ├── 2e757d76895b3ecc37d47952c2e804d9c19c3d8c.nq.gz
    ├── 2fabb0a4986f33648dd93eea2f30c39686fe908c.nq.gz
    ├── 303a39a08458fa34f765efefab6b454b35ec5d9a.nq.gz
    ├── 304bf97264789b1dfd2fee653d7b61856ac530e8.nq.gz
    ├── 323a22a8caefeaf8b9abbd9a36ee655281446796.nq.gz
    ├── 3292ee9256df0a31cb2ae299b0f8d8c70a7096e2.nq.gz
    ├── 32dece5dd238f8019d62ace209eff994b8bccc65.nq.gz
    ├── 34abc2deddb1ba1c18c69f50810abab675b133d9.nq.gz
    ├── 3514a34c1811d2a011369f517f3ae99086a8a21e.nq.gz
    ├── 393a362461fd582cbfb7738fef8826bd752b3368.nq.gz
    ├── 39d57d575b32a195c2cdbea9d4435b57039f66ae.nq.gz
    ├── 3ba952dfc4769e3fa4e6e3b6eea7f4d6f56c2bda.nq.gz
    ├── 3bfb5b6021cf9921994da23ead21ab87e3e4ce49.nq.gz
    ├── 3c1a80289d261d1cca70ecdce555cef4b006ce19.nq.gz
    ├── 3c2582c4dc250de71633fa137a2fc0e152c72f42.nq.gz
    ├── 3ed49b7e491ec325dbe76c7744e63e6dc7ca300b.nq.gz
    ├── 3f4e04f4366c9f4809143696865e094beb72bf0b.nq.gz
    ├── 3f632079f4653c00a032e2d9c79ed8388e97bb98.nq.gz
    ├── 3f8c24dc422fc9003624d55a4ca57c3ee626c29c.nq.gz
    ├── 403d3010803c6b65f04bfa0e4b891e69d1c05fb8.nq.gz
    ├── 444ab46730658ac62b4501c0f923fe2718a4d54e.nq.gz
    ├── 446552118b29c48992f9c977724da4b755d5c6a0.nq.gz
    ├── 44a704c2db691f91ccd75e9fed8be3999f08d96e.nq.gz
    ├── 4842484aca790077e46fd9cc4ec6bc2d83d3f0a3.nq.gz
    ├── 48b39e8f338b44740061693a439c2312e30080e4.nq.gz
    ├── 4a88cd533225be8c31050679acea83ea55c04755.nq.gz
    ├── 4ae42777436cc055c7841d8e8b61f60cbd1ff2c8.nq.gz
    ├── 4b1190cffa0ed414aa224c995335f3df9e2d1029.nq.gz
    ├── 4b51751ef10aa73dfd5ce0ba25ed31a97fb5a015.nq.gz
    ├── 4be9cce6ca4621a2781384f9aa1da99b3087d4b8.nq.gz
    ├── 4d3208fdc44105a1ab5ad12ea8c7af634a89a16b.nq.gz
    ├── 4d717bc314150a99b1b016761b14a79b7cb6edaa.nq.gz
    ├── 4da031d163f1faf81f12185949bdc8768337b884.nq.gz
    ├── 4ddaf021ee90a4d012255bd39868657684c7d629.nq.gz
    ├── 4f219147c2ee4c5f0c7da865fb99ee4b4b06f271.nq.gz
    ├── 507699f557057d2b55dc9aabe1c058050cd73ef3.nq.gz
    ├── 539fc03b2866dd778e12fb91c9ffc21116bb5d24.nq.gz
    ├── 53ffc3abc45d0b67fd5ce6c228393b4411e08af9.nq.gz
    ├── 54bbd04e18df44572600ab11b087655aeb1d63d3.nq.gz
    ├── 559ed6dbe63d9d59c42bb0af38e504bbc923c999.nq.gz
    ├── 55ec1befbde6d83962633ff60ce0782ff6421f41.nq.gz
    ├── 560b295071946bd1649734fca596524bce76f136.nq.gz
    ├── 5a18bb68360e333c0658ea6ff1f4555b9916d04b.nq.gz
    ├── 5a39afd44ce7760992826148ad33e7d6228fd30e.nq.gz
    ├── 5bf65ef267da8e1ede36dbf7c0ac7655bc27ab76.nq.gz
    ├── 5c73b2ecd9e4f3df93fb5e1a7f86c42b912c4365.nq.gz
    ├── 6013952518f40842924b6b06116247754286b522.nq.gz
    ├── 6321ece43df3ab3eb85999ccafceaf8bb0067e6f.nq.gz
    ├── 64083cc38a1eb5c5d22fffd944634962312cd493.nq.gz
    ├── 641602f447652a728dae454190640260e43a0b5b.nq.gz
    ├── 6447d144a07bdff365963a1f4a1fdea91dd406b2.nq.gz
    ├── 67fcfc85c06f7abb727fd66c94abc52366fa7e5e.nq.gz
    ├── 69cbafa1c8961ee6e78ebfcf1414d648d285dbc3.nq.gz
    ├── 6a1d1ec7b60883ceebba898d41d28a7a4a2065c6.nq.gz
    ├── 6ba712908c2139039b33ce6796552d55e566a15b.nq.gz
    ├── 6cce59b5e88fb6613101a302cd362a11277e5ccd.nq.gz
    ├── 6d0b0b6c22d984843caeddc99e0cc47210f2640d.nq.gz
    ├── 6f3996f03508e26b26ac83bc3f3dd0e9b9bf3174.nq.gz
    ├── 70eb50960828db9a920af1e6bbd0299ccf9f9d33.nq.gz
    ├── 70ecbf0dbcee4011b1ce7549f218723c74afe412.nq.gz
    ├── 71087cbcd1f11cc96bfa59baf240ed5182545b4c.nq.gz
    ├── 7163ecc76ae077ec2bb5ec47fe69a7147c4a5ef9.nq.gz
    ├── 748c0abfba39003767924a49085e4b9e4e6a2a03.nq.gz
    ├── 74fad61da1721018e8c2c4ebb116cdff965c319a.nq.gz
    ├── 7699100f515d85f2e2405946199ac2c88864a5f2.nq.gz
    ├── 76b3404d7f634490a561d155dde986c4a21b92f0.nq.gz
    ├── 78971cda4da90cd15f50566d0ed563fd1d577ab2.nq.gz
    ├── 791cba63c005d59a1560e220596faf331e145fdc.nq.gz
    ├── 79c59b90653fbcc49d884bb7ffad44f731b8be44.nq.gz
    ├── 79e90d59a4d61d850b08783c14d1e23d253dea7c.nq.gz
    ├── 7c04bb528a3c4494f9820a57000b33162470fbd7.nq.gz
    ├── 7d35c9c4376286334946a8778b1ed2b005272240.nq.gz
    ├── 7da8e82d9cea24ca6536ddeb6d776b0ab36348d5.nq.gz
    ├── 7dcd7cd91983a90db921b95c461e2b94fc6f3d47.nq.gz
    ├── 805fdaedff6b93eb7661ff15a08407e3c9186acd.nq.gz
    ├── 8291f1547d040f29d8c88824aae444ccb6c391b8.nq.gz
    ├── 83b0f168a514523e9482bbb9b061d417adfe8791.nq.gz
    ├── 83df7d61d5b5b5e6c6318562aba7e5716dd94155.nq.gz
    ├── 858ad26710a184043f648a7ee6bb20c4175001b4.nq.gz
    ├── 8723642f64adf068c1f3dd2d93736b17a48b7464.nq.gz
    ├── 873110831f49d8c58f12acbe5324975dccdd6e80.nq.gz
    ├── 89d7a3b67e39ea0f54d9f4c6a47ef5249bd866b1.nq.gz
    ├── 89fcdb4f81ddd3f07aac2da1793d5ddb6f06452b.nq.gz
    ├── 8a39a48e4ce426f98a4b80f8b51b2d8f486b2cdf.nq.gz
    ├── 8a781a7727e8f6d86ae45c8b54d5dbc7e14f5cf7.nq.gz
    ├── 8b13b4ce845c78647d12b39b83202ce8e367c789.nq.gz
    ├── 8b1d7fa80b33626f38daee2bdd91a7b26642693c.nq.gz
    ├── 8b826973e339417fcc6ca6aadbe1c6d518282ffc.nq.gz
    ├── 8cf9b686ecd6a53dd9b9577ccb91cd4a952c8186.nq.gz
    ├── 8dc7d89c57e1e7c45bf12bd5df2623ece29f22c4.nq.gz
    ├── 904d69c48569c21d3ef6f756130e67eeea902d15.nq.gz
    ├── 91090dbfaffd4f426a1e57ab0f4b5364e36d5778.nq.gz
    ├── 9210b8e9fdba109eaaef7eee8ca0dab2968a3240.nq.gz
    ├── 92cc632c9241e6b5f08e86307b1f5dd5683740d6.nq.gz
    ├── 940ad91d30f0f7ede9378868eb1f397486b034b3.nq.gz
    ├── 97203560ecd03d0e773106c0e7da0f523f753473.nq.gz
    ├── 984bbe3fc451039991a070ff9b676e07e622309f.nq.gz
    ├── 9a682fc9b2ea3964678bd9f487385c7a56ccee0d.nq.gz
    ├── 9ac5ff946a4184445f51fc4359f94fb780c65a64.nq.gz
    ├── 9b804cfcf0913eb306c4d92eafdbd23baa07f684.nq.gz
    ├── 9d7059cd117c79d9a90b2bce6aca8a2bb61c2f8a.nq.gz
    ├── a31931314395cced673451f0091f8b81d32ed64f.nq.gz
    ├── a3ac87ad9b2c6cf5c0a1250174e074f7b42d560a.nq.gz
    ├── a3ad57a49527fd2ffc7eaa4005d0719f4c4e8407.nq.gz
    ├── a50b0f6f4d72981e52d0d21b792d9b74d0f28b83.nq.gz
    ├── a56fb60176582492ee5695658d6363c4a82cff49.nq.gz
    ├── a5b2d23980aa46de319b4260df3fa45dfecaf8fb.nq.gz
    ├── a64b6bd7f87c4ef3e8e99159a00ee71aa99cb7f6.nq.gz
    ├── a6d8e2c482fb44a7ec40f344ed9cfb40ce921fb2.nq.gz
    ├── a726a6c47d26523b3520505aedd428a089ad58fe.nq.gz
    ├── a7d589534b84df6b477c15c5fca49bd829cb93d5.nq.gz
    ├── a8f39173c9327843c472e7a5014d42a67979a283.nq.gz
    ├── aa8f5bc90f524ae807e54d811ca2e5382a95270f.nq.gz
    ├── ac1222987b571f9cdb16b139d47d6166af32c13e.nq.gz
    ├── ac97569688ac95fec7dd6e32a786f3cabb374cba.nq.gz
    ├── ad16db65768c80f776b5ae21e28cb47c893d2333.nq.gz
    ├── af83fd6d241a05ee23c7cbbb26f9985734723930.nq.gz
    ├── afe1a7744c7c4c28309d7f408c031c73ac662d99.nq.gz
    ├── b0b37673b58329f77ca38bccdc486c2a17899834.nq.gz
    ├── b1a4b45302742b37c61e72a6be40adc56828f442.nq.gz
    ├── b39432ad71c9ad96c692a4bf0ea2da56099b4aee.nq.gz
    ├── b5af18e929cd08a829b48928cf95e22786b78b13.nq.gz
    ├── b5f05a894866437d805e3a13eb058c341ca72c2b.nq.gz
    ├── b601745f6abd32b9e01d5f029f3902e51c192907.nq.gz
    ├── b68c06880dd92804440afea66731cfe34be187a5.nq.gz
    ├── b6b21e0e26b6fafe16b7d116ed3bc66d90c378be.nq.gz
    ├── b75e1b162a4c49d2be57a621bdd8fead466ce749.nq.gz
    ├── b7bb98f75cbdf0491c8d861d98f0f646d7cdf85b.nq.gz
    ├── b7f80e5c696bda523cbc8ad7d3871a5e836cb730.nq.gz
    ├── b9b7b44b0eede17f7432e2cfc033dea819b4d3dd.nq.gz
    ├── b9ddab739afbafb895a973e39d5a58d69f76f292.nq.gz
    ├── bb98b00eff2e7df0adbfa25953475b59334bc9c2.nq.gz
    ├── bc455cd173c5aa65993da11671084439a709b62a.nq.gz
    ├── bd6a7700c0518b3a3406d4b7fa0608040dde213e.nq.gz
    ├── bf61237663f32ade2d4950e1fcd502dd9cd16af7.nq.gz
    ├── c0790d3495c636fb6553802b2ab3bba9cbb1b736.nq.gz
    ├── c14c8cebc7bb62dc3e5760c1e3f3eb361db42a4e.nq.gz
    ├── c207c0c24a986d89a8fc399db7e8c4df00a9d8ff.nq.gz
    ├── c2479ffe00fc24735164297ce5a91e92671f7657.nq.gz
    ├── c281f830152795a9cc1751fdec07c0f92ec70285.nq.gz
    ├── c3e6c36a84cf7cb5d4ef86f44eaf745759d82998.nq.gz
    ├── c47a3bb40e6e73e6ec9251606d06a832d9725906.nq.gz
    ├── c73afa94cc827bd1719a5620d7af4c1e8219a90f.nq.gz
    ├── c753676308f79f7ec2cc6303a32f96f0adb7c5bd.nq.gz
    ├── c7c08dee48dd6e98782693d9e721610c307f4377.nq.gz
    ├── c7f8cf2cee794f55bf60ce858f3014ec6f513b1b.nq.gz
    ├── c937f7be891fd6425f9544e47b76b71e022be26d.nq.gz
    └── ca7054f70d67f323c4109ae3fb59121614e6e020.nq.gz

6 directories, 200 files
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

[repolex-ai/lexq](https://github.com/repolex-ai/lexq)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
