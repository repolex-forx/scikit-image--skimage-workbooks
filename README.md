# Repolex Knowledge Graph of scikit-image/skimage-workbooks

RDF knowledge graph data for [scikit-image/skimage-workbooks](https://github.com/scikit-image/skimage-workbooks), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-image/skimage-workbooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0e3c1575f5f261f48554064d4104a791759f57a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0e3c1575f5f261f48554064d4104a791759f57a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c67d180e0d170c447b52575d9139be5e607fc0a.nq.gz
│   ├── 1cbd925eb61c23f844cfb181f11b947b957d5558.nq.gz
│   ├── 211cd99ceda0aa960619e5204dcb0b54c0fe2a30.nq.gz
│   ├── 22daec769b94263af89dccb2f3cdab9f662e551d.nq.gz
│   ├── 24dfc73408627ba81ca0770a65365c18831f6b50.nq.gz
│   ├── 2781529abaaa83f66fe7010180492d0bfc139c47.nq.gz
│   ├── 337d5fc28eb6ced3198b4876c24b3de05ceaabc5.nq.gz
│   ├── 448f8573fcd367eeb24d4601df35332d9bd8e41c.nq.gz
│   ├── 4848798c1afbaa718d42572d14f9be1634dbed26.nq.gz
│   ├── 49887a00409c184030f3984aedf9ffc4b99755a1.nq.gz
│   ├── 4ad7e607116674a20ddd2a791b26d9727b1a9baf.nq.gz
│   ├── 4b86c49a9c2a00aecb8260b7976951ef79b3ec25.nq.gz
│   ├── 4e71c4091c593de2ab5b0b9a6a5fe05872717f1d.nq.gz
│   ├── 4ede2cf28005fd69c73fc56ea037f896f585799b.nq.gz
│   ├── 5006287bc7dd90118efa23ca4478d38a7d1f288e.nq.gz
│   ├── 501d7c6a43ba9e7592954286cf1d80b7490d8204.nq.gz
│   ├── 56706aa4c932837e17f372be49bdbb84a3669899.nq.gz
│   ├── 5749270390c1f14072bb0b90d106613475459187.nq.gz
│   ├── 6184114f66420fe0979ff0a1bd6a352d2e5a1066.nq.gz
│   ├── 69a487bc0018e79d41bfd035554d7d9cf441eef2.nq.gz
│   ├── 7305ae56416f603adfdcac2479dda308ae205c49.nq.gz
│   ├── 7dbbd29d72693c392217e7758047e991969fe91f.nq.gz
│   ├── 7e18e705b7c94d1c070faf06a84cb3e8a6259470.nq.gz
│   ├── 7e5ffe989e99676a3ff56ba4f9586dd483a707ee.nq.gz
│   ├── 806ef875a3cefa836c15467a16dcbb934b68533e.nq.gz
│   ├── 832b0ad8bd1fb04b374b0a2012b52921b7cb23dc.nq.gz
│   ├── 856196210f72e899988c7b4601a9663bb412e14d.nq.gz
│   ├── 925a96d07317cb45094dc62e9006a322c96120b5.nq.gz
│   ├── 949712b54407a69bf0d4c664fea8bc45bbd75205.nq.gz
│   ├── a559f095f9221b000d7b22db2f3552251c98fe39.nq.gz
│   ├── a7d28b1a9e02b38d53fb6caaccb92c50a089690b.nq.gz
│   ├── aa49819bc44c55916d65c7b0b6d82aaeba0fd48f.nq.gz
│   ├── afebfd7fc324f5822a58b4339c50a1815814cadc.nq.gz
│   ├── b635c16791a45da89be11a88843e0e1226196385.nq.gz
│   ├── ba67342094a19a87ea79559c299e9021a8226d57.nq.gz
│   ├── be907b49094d48ea8a67048d6c5900f3ffb1b7c8.nq.gz
│   ├── c34b42f60eb2762138cb3aba3b0a891575ee474d.nq.gz
│   ├── c3b8d1b4f2a76ea78dd0ffd6c92fad71952b1ab1.nq.gz
│   ├── c52964a75d38f0309fc34106689dcabd6affacd6.nq.gz
│   ├── c61668b689f58df428557d1e9d07501179de6d02.nq.gz
│   ├── ca641196447b2198a2689dde5710e5da996d5f8d.nq.gz
│   ├── cd6aaf58e4843c748edfb0cec7cf2b90f47ee04f.nq.gz
│   ├── cf6c99db9e6563886047b4c3998d7c3be2147be9.nq.gz
│   ├── d5c5d0bc23748f576626b91239c81e7bb63539ea.nq.gz
│   ├── dd2b9a1804d47e21df1b39e2e73808f7e2fe866c.nq.gz
│   ├── e47e82fb597a0533bef2540b3fcbd091e03ca3a5.nq.gz
│   ├── f28e85c511a03d43c19c9f315e830629b7c9bd43.nq.gz
│   ├── f559eea8b914b3b6af19c5b22273fc839800739c.nq.gz
│   └── f83b2e08ada09a0bead7e405d96020c28a86f737.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0e3c1575f5f261f48554064d4104a791759f57a.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[scikit-image/skimage-workbooks](https://github.com/scikit-image/skimage-workbooks)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
