# Repolex Knowledge Graph of faern/oneshot

RDF knowledge graph data for [faern/oneshot](https://github.com/faern/oneshot), parsed by [repolex](https://repolex.ai).

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
lexq download faern/oneshot
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 83fd0864be7289067ce96cc79cd96c0928742979
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 83fd0864be7289067ce96cc79cd96c0928742979.nq.gz
│   └── repolex
│       └── 83fd0864be7289067ce96cc79cd96c0928742979
│           └── chunk-001.nq.gz
├── blob
│   ├── 0338d88d6ce0baa81bcf66ceed89f1a0dd50ade0.nq.gz
│   ├── 042778570726b56cdd9500b93d541e7da276e7ce.nq.gz
│   ├── 06a35e6f0817f489052bfe7fa73cfa9d1058d9a2.nq.gz
│   ├── 0ee53f9a38ae79425cbf458e158d71beca224541.nq.gz
│   ├── 19bfa385f02187b9d9de71e38d17223ad8001630.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 23d448b8f7381bb7d2202b98f665871ac4cf2fc7.nq.gz
│   ├── 2b0e531a26afbb00de257a98ce76afc0a7e1aa2c.nq.gz
│   ├── 2eda3dd6105183c0067c91282e376b5bc0e9f6cd.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 32c31fcd9ccfef912cdb9faef4356e9256c65441.nq.gz
│   ├── 39547586213b090e386876a416d3c9110edf0815.nq.gz
│   ├── 4431ae0f143232ad4d8808f4ed7fdc08ff6302e9.nq.gz
│   ├── 53225f99fc71935f0988382039b3a74b2c0ea6a6.nq.gz
│   ├── 5a10835a0fad6a91a755cafccb7ef1c183311bb7.nq.gz
│   ├── 66aa5c6485537853130f940096a1e492e361f682.nq.gz
│   ├── 67ea13c03dad58e7abf9d9f58239812fd194bee1.nq.gz
│   ├── 6ed74ddfca7db38ab7221c9aff60741ac687cecd.nq.gz
│   ├── 75ff3d600629fd358b336b689e994865d1a7a870.nq.gz
│   ├── 85a2ac88bea979006d21e3f5068a146ca35c6333.nq.gz
│   ├── 8a3c7af65efbf99aa582b05aa0bdae2766ee5089.nq.gz
│   ├── 8b82a87a0d4a34c0e365576afd1aeaf2f4cee84b.nq.gz
│   ├── 941c508d5ba56ecf8b9ec8d5494babd61f5ad048.nq.gz
│   ├── 96e4a5d2899795ac0f19a3d56af4fd9901fe9f65.nq.gz
│   ├── 9e13a57c94bef22dd5c8876ca04c41d14c58e1d2.nq.gz
│   ├── a993ad715a7a8b7b9a3b144976b631be569e1ff0.nq.gz
│   ├── aea7d66b9004189946c6991b02bd0feca1a44bc0.nq.gz
│   ├── b1e5032aa955fe14b9d6669684063567e3b55f27.nq.gz
│   ├── b31c6d0bee870428a6d696d2307d0d9833bec0a2.nq.gz
│   ├── c31ba658d3a6625da01e36d13fa0b013cd981a1a.nq.gz
│   ├── c86a7dcdafe03a9ffda5d7273f7d6e0931b839f0.nq.gz
│   ├── cc549e93d39658d56fd346aaf203bac15d779a02.nq.gz
│   ├── d3f4413bfb34faf43dfb5e4b9ba2882e4931c3fb.nq.gz
│   ├── dea2fdf81534e1bf6ed40fb33f1ee3b730ce899f.nq.gz
│   ├── e26d467e946a5bfcf6a0d0297e2e0f8378899295.nq.gz
│   ├── e277fc7774234682d9fa7ffc2047cd9742bd350b.nq.gz
│   ├── e699df021cbad580877fd8567560aa557faa2ff0.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── ebba580ed62c7946b195a798318b798d9915b63f.nq.gz
│   ├── f05f0137933368b8b3b19cc3c135e329a68f964a.nq.gz
│   ├── f7a7171e1b883480a428fc7d734b3317fc59b70a.nq.gz
│   └── fdcff43ac3581160a4f918cdc9ee275dce2d3174.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 83fd0864be7289067ce96cc79cd96c0928742979.nq.gz
├── filetree
│   └── 83fd0864be7289067ce96cc79cd96c0928742979.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[faern/oneshot](https://github.com/faern/oneshot)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
