# Repolex Knowledge Graph of python-restx/flask-restx

RDF knowledge graph data for [python-restx/flask-restx](https://github.com/python-restx/flask-restx), parsed by [repolex](https://repolex.ai).

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
rlex download python-restx/flask-restx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 30abd919e7c6bb2533eef57ec9c2339d7de69b39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 30abd919e7c6bb2533eef57ec9c2339d7de69b39
│           └── chunk-001.nq.gz
├── blob
│   ├── 0075e737d4abf28c320916a0a180fa1808831dc7.nq.gz
│   ├── 062e428ed1efb2725150d8e29d2605250d67aee9.nq.gz
│   ├── 07e673e99f8543006c4e8fd0aa309a734c3a051c.nq.gz
│   ├── 09fac15644492ab7647052862289b02080b4e78b.nq.gz
│   ├── 0a68b497bbb2a403be99b2d60d7eb6716bb3d602.nq.gz
│   ├── 0e340c5488d733d00075fe1e10975ecb5e6b5852.nq.gz
│   ├── 1078c983de910dbec63095bd81e706f4c09f2ea8.nq.gz
│   ├── 11fc491ef1dae316f2b06bbb40eaba9c757fdfd1.nq.gz
│   ├── 123b7864449d0aea99ca851a20049720e39d2185.nq.gz
│   ├── 16a194fd10b57a18c40c71ee3779234224d6c243.nq.gz
│   ├── 1893dc9ba08138e25dfe336df2458e9666047b57.nq.gz
│   ├── 1a5ae366e1a6a239c6c04b7e13c32ce29ff35848.nq.gz
│   ├── 1f4783eb68f192ce6e1e310cb1f4187774ba1988.nq.gz
│   ├── 21ed5ea6244937b357580d9bbe4be14a3fc7c2e4.nq.gz
│   ├── 2209710582257754ac3a07b51a1a7e34eab5e3b0.nq.gz
│   ├── 22e0996aea416507746b02f5cc8e94ab3e21670b.nq.gz
│   ├── 252177b534770d601b489d4e6ce02edb8dbc9c59.nq.gz
│   ├── 28fe5110e1595b135600cbca4d16e0192b6e2c95.nq.gz
│   ├── 2b319ed91499dfadbd509de2fc6375ea34611fc8.nq.gz
│   ├── 2b40b2353e4f9ae125349e3c70d2adeb80e10d4f.nq.gz
│   ├── 2c5e981469c3893b63332303be1fd33ba84a86a2.nq.gz
│   ├── 30219dd282f8d5ca61dae95a5ac8e267c91f3e53.nq.gz
│   ├── 32fdb70d89f3f43eaf7756c87d5af1c92f03f50b.nq.gz
│   ├── 335c55f7b67bb554df3db7ca8f1258010923d007.nq.gz
│   ├── 33e1c6985f75ef0fc2d73f984acf969b392884a0.nq.gz
│   ├── 34e357d54612d5f6abae9f9d0c95b97dc0e39918.nq.gz
│   ├── 36d15a99890966fd4525060afdbb0633581b7ced.nq.gz
│   ├── 3b025ee4268d4f28c003d2b27aef17dc5ec860b4.nq.gz
│   ├── 3bcb660177cc1d9fdfdddcfa6bfc3b4814c9b475.nq.gz
│   ├── 3ee8a3a26179a47a568d3d31457ccc15898a373a.nq.gz
│   ├── 41db63ba53cb370f7d30b80a6fcb04a3ce13350d.nq.gz
│   ├── 4666cbf7dac54e572751bb516af3259c916a54c3.nq.gz
│   ├── 47110997531f91355c1a9d5b357c8917e1d40420.nq.gz
│   ├── 4b7b8c0f17f22772b98cd91397a51372d8f817f6.nq.gz
│   ├── 4f758714e2a97d58f1ae29a1a88d7c660e8d1c6b.nq.gz
│   ├── 50d5c0aebb1334add0af7605e4243c11c4558990.nq.gz
│   ├── 535e5dcadc3510fe8c4cf2978431e560fb582603.nq.gz
│   ├── 553de42ec8706ea42abe8b9dfbd51ffb82c9d925.nq.gz
│   ├── 5727d4b653b05cc515c4eda3be511c71a6638ae2.nq.gz
│   ├── 61df37ea6b07424ee66861549277994639a01ded.nq.gz
│   ├── 62a3854c24e3483b7b6a9b6b6969f095c9fd9316.nq.gz
│   ├── 649aadc95d1840c2c9d3fe718a15f388f0eb1e83.nq.gz
│   ├── 64f45e2e064b7ad501885063de512655316e4edd.nq.gz
│   ├── 6785913fb228257368555fcb9004a55db217b706.nq.gz
│   ├── 69a65657f44959f0950f94954b3129dd02b7b88a.nq.gz
│   ├── 6d55fabeff2f34d6c23a6ebb3ac4e990009bceca.nq.gz
│   ├── 733f7d1d830b845f5ca815819d3ddaa178fe6545.nq.gz
│   ├── 73ae6425c9c76c39a60cf77a4a3bddff4d249b95.nq.gz
│   ├── 756726eb200e1d6a8fd7b11b0539f14a793188b5.nq.gz
│   ├── 77834eb2d352e2f41a05a27db22058ac2e76e33c.nq.gz
│   ├── 79669aae45a6e2cb282d98ce3f0da65942852a75.nq.gz
│   ├── 7d0a38f5f97a767711e5bdec13b982daba2c254f.nq.gz
│   ├── 800b7660954a613ac0d8474faa8b57626c7a7520.nq.gz
│   ├── 82356eaa043935568581f2f61dc2483b2a3be155.nq.gz
│   ├── 836a4e1ddffddb08408c03f8b45d8a61ca2545a2.nq.gz
│   ├── 8461f0ecc7995d1be202168257e8726bb56a46e7.nq.gz
│   ├── 84e4db17ee150ab3d5e651ef3f70b73bd044020d.nq.gz
│   ├── 85c91628cf7abfaf09142f1f6e4ec1a5f7d653f0.nq.gz
│   ├── 868262231c45f32f642d319ae8e0a39866778ab4.nq.gz
│   ├── 88e1677f7566557164dab832c3aa307ba824bc16.nq.gz
│   ├── 8abaadd6504602856f7ce4155fc882da8c1a91d4.nq.gz
│   ├── 8e0f6750398e62178f182c73e1c578eb5afd7525.nq.gz
│   ├── 8e7cc7eb9d7ce6ea4502a3e25f10bb7458d22bcc.nq.gz
│   ├── 9065b5e02d75843f768a368da0c8d3411901de58.nq.gz
│   ├── 941199a66fccb5b56a6b452b3eda2b5b6c8c5a25.nq.gz
│   ├── 97d0e866249066ecd39030dd40ed19776cf0976f.nq.gz
│   ├── 9934494d715e4d7e29f33d8ab97e6b9ffdc40c5c.nq.gz
│   ├── 995d606a7b9d69219e8deb1e21a0305af8077df4.nq.gz
│   ├── 9bbb9c79bea3308202b85810adf4ba0629c5f896.nq.gz
│   ├── 9cf979b137a535ea6815251d3c86e496d5df6b95.nq.gz
│   ├── 9d709f714993c1f2281ca6d9728d88cdf3a9723a.nq.gz
│   ├── 9fc96981a16eeb7ef7dfdf27cac77bb228b7c3f4.nq.gz
│   ├── a0a5c3b5d6105a44f870693f40c1319251532df0.nq.gz
│   ├── a3aa2854df4127538966785ef8bb1ca180608675.nq.gz
│   ├── a92e18f2a5aa611d09eda83ce9f19987ebb58d52.nq.gz
│   ├── aaa34e91f2b5728f39cd4fe3c22e3eefed81b5a9.nq.gz
│   ├── ac50a34664742e19372570aeed1d4e4cba7fe7f2.nq.gz
│   ├── afb4c703bf5b1b1f1d979c1847e5ea818da589c8.nq.gz
│   ├── b15a60273e2d6f1531caa3e5ae38dc5e527935d1.nq.gz
│   ├── b163a8699fd45db0c4e087832483c77f953d8a4a.nq.gz
│   ├── b24a610fa263942c89fa0cfa1c56afa8719178eb.nq.gz
│   ├── b56782fc41b98b2274932a5cb4d438b5e34cbde8.nq.gz
│   ├── b57f83c62fe58dc244100d4c654e4e9c6d4dcff6.nq.gz
│   ├── b8522e3b71a2b0a9c6ba0112ccdd4118a7448700.nq.gz
│   ├── b89a9512f31bcfc5c28ad4374b81aca6352c4bb1.nq.gz
│   ├── b8f00fed26c0a9d6a25830c51f0f6095574b1a74.nq.gz
│   ├── baa308fcbae5f71ebeac08e8b26c328ebe2ea561.nq.gz
│   ├── be1fc624e56cf380a2268772a9c65de64977895c.nq.gz
│   ├── c4a5ca7b9c95902547d076b673da3be0c2fca7d8.nq.gz
│   ├── c6741da9fd8bfb07a62bbd0d6f4573bc53deb9b2.nq.gz
│   ├── c6f994e0842bf9710439450c1ef3febd33bc4a48.nq.gz
│   ├── c7dc5eaf506f037c3b38e313c8ec5b50a513528a.nq.gz
│   ├── ce84dcae29dcdcc43eac615df44da877cf8d6cd0.nq.gz
│   ├── cf5ad2ea5f4e3bd821f33329617cc1c375dad0ca.nq.gz
│   ├── d1ed93366171228d6cbc77fa2568225be6afbcef.nq.gz
│   ├── d3018ce0ca7275446035b729b57444b85fb44810.nq.gz
│   ├── d6846ea9cd73a974569f796d9a9cae3df95a00d0.nq.gz
│   ├── d89b7e89acfc29899d81b2d787bd07a7857176ca.nq.gz
│   ├── d8fcc30d9123648f6a58a6296e28c8e2dee2505e.nq.gz
│   ├── da2c2b507f6f449cefd1e0bcde42f0fca4620447.nq.gz
│   ├── da52b04c6b819916625faf70606451c5045d37c0.nq.gz
│   ├── dca305098909a4222cf6554f134f5e5d8760c3fe.nq.gz
│   ├── df4bbecfc33dc5153414375594db53f3ce95db9c.nq.gz
│   ├── dfc5106743815849634d80bd053907e70be5d02f.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e800a74979cbbe7bf5c4b37e18c24143b2ede872.nq.gz
│   ├── ea0152dac07fc75fb40c9c14dc8f500c72cbe8b4.nq.gz
│   ├── ec0a197549363acb698851340aa5843e5c6c592b.nq.gz
│   ├── f22044594f3cfcc1a90ecdcb100e5836d9f1ed33.nq.gz
│   ├── f24652badcd7be1275ea17ce82c2645759695ee9.nq.gz
│   ├── f28dd77928bbc84707a4010355da26c103995d21.nq.gz
│   ├── f8bcd87ed3f0119191023b667f08c53ae5305cb9.nq.gz
│   └── faf1e19cd21425bf14bb45fcc48511c7c2cbbefe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 30abd919e7c6bb2533eef57ec9c2339d7de69b39.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[python-restx/flask-restx](https://github.com/python-restx/flask-restx)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
