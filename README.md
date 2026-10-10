# Repolex Knowledge Graph of mkdocstrings/pytkdocs

RDF knowledge graph data for [mkdocstrings/pytkdocs](https://github.com/mkdocstrings/pytkdocs), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/pytkdocs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96560effaa047da3ff1b7d35c40b4dd4f924040f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96560effaa047da3ff1b7d35c40b4dd4f924040f
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0518ec1cb7daf0767a95491cb22fef97340afe3a.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0d6c192c3c1d38eca84f344c5f3bb918fc2ff8ea.nq.gz
│   ├── 0f3fcc5c304e3a9e1ba842e95f296d57433fa713.nq.gz
│   ├── 10bb546c171c803bc7647ae92734f7a0431988c4.nq.gz
│   ├── 14e1753758018cc82b2cc9ebc9e681d703817058.nq.gz
│   ├── 17ebf722ac7ba2568279698d214b47b9a61b81e7.nq.gz
│   ├── 1a5a2cbb34ec852595e92be93e0e55a96d725d58.nq.gz
│   ├── 1b284782d7eed471a4652cc4de9e150b7bda8ed1.nq.gz
│   ├── 1cc9a24e8457a81e926b97eea24b749c79a06cc0.nq.gz
│   ├── 1fc9c8d46e2436575668f1d63762a0c8c00dee6f.nq.gz
│   ├── 200f36ced2a3bd6ae01526ec6ceb534d6c631498.nq.gz
│   ├── 211d32a1af75f76da6291d3afd6474508d388d21.nq.gz
│   ├── 21f9c7187b2feae3270aa1d752ff97037329b7e6.nq.gz
│   ├── 22b119abe81db6595a91cf83960a31401f7fa646.nq.gz
│   ├── 244a41148c6957140fb4a003385c4c2375cfe8ea.nq.gz
│   ├── 285fe64ca01e4e9aa8058d8959a9089ceae0c8fb.nq.gz
│   ├── 2aed08279df26f129dc8dbda9abf91e2a684d0cd.nq.gz
│   ├── 2b3f395d8d123c141b4a213192dc5094ede7e26a.nq.gz
│   ├── 2b5e9a9670e540ced95055328096c85dbd262fed.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2d4e894a6bb4a5ebcd6c90c530f59cd51ebbae1b.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2e72dff168e7218c4e6f528c8ce039e6376944e0.nq.gz
│   ├── 2ec8e60452f5db67147ef0ec3c361d6d38054c06.nq.gz
│   ├── 3097a322b6d2a74212e6d65f0b5328dcdb25f142.nq.gz
│   ├── 37395f23d2372f77f6e83c6d5ce615ebc598ed47.nq.gz
│   ├── 39b02cdcbb1bf8290060e20ffddfefd3dfedec6e.nq.gz
│   ├── 3b42aecf0f89a4a19ce2f1fbdbd377e3f30baec8.nq.gz
│   ├── 3be27baffe914b56d125df306141a4e5a2a5f904.nq.gz
│   ├── 3d8190a3991876c2670497515f9f495147a92a53.nq.gz
│   ├── 4099b9f835de5776d0fe9dc75f66e03e56336395.nq.gz
│   ├── 437543da6f76efe3cb03a46b139fbd11a92a2ef2.nq.gz
│   ├── 48118abcbcc7fce87e9606f5fc5fc57d03f455eb.nq.gz
│   ├── 48dbc12e2b07b9ce70d17c757609bc932b1e3208.nq.gz
│   ├── 4b8c7d6bae31b9eec50f08df638d86373a1d9c40.nq.gz
│   ├── 4d2be9274f40cf5428dff78da1531be1cba5e3f0.nq.gz
│   ├── 4deecb2f6cadc06733957aee6b15a9c84aef13f2.nq.gz
│   ├── 51924e607d3eb2c5bbc85d3687e04fab78522185.nq.gz
│   ├── 521c95da18175ce6931f1e375863bff9a9535cd1.nq.gz
│   ├── 57114e0c7b547d7ebdabf71e013528d0204c635f.nq.gz
│   ├── 5794527f8e1e47c4d692a862cbe752f60c7b9571.nq.gz
│   ├── 5a7fb4c2a9378c84d3c47cd047413bab2fbcc827.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 5bf254d83c414528b7bf47ac36e361ffdb897051.nq.gz
│   ├── 5e143e577f0f23157ceb342dbfa319733308db75.nq.gz
│   ├── 5e88121db210bbe6201d261763520d111d4d1437.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 61def2a72ec06ae5a59fca28cdad1803e81ea2af.nq.gz
│   ├── 61dfebefd24a6c101e380f129468831c2537e8c2.nq.gz
│   ├── 644d417fcc76c1fa63cafb360decb77929f6584b.nq.gz
│   ├── 65b65cc2b4f8a036956e8ec65118990ab602986a.nq.gz
│   ├── 66c0553f10dfc8af80d844aa5b3b122da6b48d1c.nq.gz
│   ├── 6734e5b67d20e24015ee7223eef2936459297f68.nq.gz
│   ├── 6920261164e462cce1abb0ca21b1566225e89a87.nq.gz
│   ├── 6b0421b0517cce490fd5ad1d33f8517d8acd415c.nq.gz
│   ├── 6df9a40c5124e1f311efa80d40c07cadabc5aa04.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 7772c2d7022d70dd9b5abab24d36870560b25d16.nq.gz
│   ├── 7f4cb961e31376d33b909b1227f9d0ef34f16eb6.nq.gz
│   ├── 7f6aa5383d7073239676cf491adaac3119cdfe76.nq.gz
│   ├── 7faefffe584014412ac5cd5a4d29a96283387bfa.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8405477c6b47d7420bc0d31cde35cb9650364210.nq.gz
│   ├── 86767454775579440a38eaa757cae2cee8c44529.nq.gz
│   ├── 88c735759ca4ca82a77cfdfd56dc9bda6ea1c793.nq.gz
│   ├── 8a9361d37d0ad34440b4cd39f3bd101a0e585417.nq.gz
│   ├── 8b5912fd8b8e7e4ad21a9ba057b4c67d578cfb4a.nq.gz
│   ├── 9186e17d721f22907c49e3e025bd8e9e721d0bfa.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 949856d16241ae3b861c594cf8924ba565a7a55b.nq.gz
│   ├── 9e8c14a6c3e9e12c8debe37a9de178d0ffe9e39d.nq.gz
│   ├── 9e8f7b97a4d395ed37f96c6effe1fc59f0f88188.nq.gz
│   ├── 9fea047296efe8c8a689ef511f72cd8ad77743b9.nq.gz
│   ├── a58c006aa6160195dbe0771b9131aa7dab6f4b9b.nq.gz
│   ├── a97c9970064d61db9b4986e2fd1b8e765b670f92.nq.gz
│   ├── b447dc488d256d38fc177c467199ccab47421914.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── bbb7c61a33f214849e3bbf838e8fd821a70dad5c.nq.gz
│   ├── be5632dac66b46c2afc651f264ee844b3e0ad70e.nq.gz
│   ├── bfe3f7f3a580f52b2db3824f3bd81321bc860250.nq.gz
│   ├── c0b384c20da88b2ad86f115ae1c15b6f4f1e455e.nq.gz
│   ├── c287aa9328f17a3959b3d24f3ae93cf2710aaa90.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c3a82aedbfefc98f680d353214db3824980ccfa5.nq.gz
│   ├── c64144ed7c03fd39ec2148201e40cf6e2b2dcee5.nq.gz
│   ├── c7fec454e75df928e4684f9cde708924fa911b29.nq.gz
│   ├── c9ee574f6d5419bd844029e42e086640ef0fc207.nq.gz
│   ├── ca19c42fd62c1bd8cf85e40d78fa01244fdc9d49.nq.gz
│   ├── cb9282090e083ded6cca7cf8c46e633df857aaf9.nq.gz
│   ├── cfac1cce520cb90455047c903c4637f5f5436a44.nq.gz
│   ├── d92bc2f92d528fff17f86f54ef41ceaaf082c105.nq.gz
│   ├── dbf929f7f22e48c4d5fd156c907e46908c09953c.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── dd82a25c38e5e3fbd704e104d44e9f88d70737c3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73c46655767df4655c9b5ba46b15835e48030e0.nq.gz
│   ├── e7f2b5684268d1d125da571d06753af41e2d50be.nq.gz
│   ├── ecbaf239f3d73723cbb7b81175e342343290e105.nq.gz
│   ├── edfdf54da6f701348b65cea1a7ab472d5b64993b.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f8e53f688827d6fc738d849c92c0f519d01f2f24.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   ├── f9d77ee342a9b4fb6d67f4c4bee73801775f9949.nq.gz
│   └── faeae8a45118a47b57d858cee3b1da21f44e5417.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 96560effaa047da3ff1b7d35c40b4dd4f924040f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 115 files
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

[mkdocstrings/pytkdocs](https://github.com/mkdocstrings/pytkdocs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
