# Repolex Knowledge Graph of django-ses/django-ses

RDF knowledge graph data for [django-ses/django-ses](https://github.com/django-ses/django-ses), parsed by [repolex](https://repolex.ai).

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
rlex download django-ses/django-ses
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8355851ad8c054799540d9f76d7c6902b3b9d602
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8355851ad8c054799540d9f76d7c6902b3b9d602
│           └── chunk-001.nq.gz
├── blob
│   ├── 05ab0fe448f6f150c3fe857a9c64dd395ae634e0.nq.gz
│   ├── 0725360ad426a4d362f9e310d0848e9304896971.nq.gz
│   ├── 087e9383e97fdea31f0983c59a4dbb5bb42b12e1.nq.gz
│   ├── 14dc36a2d8bbfca45967c376652d815d6ec86244.nq.gz
│   ├── 1fd8cd4f8e8a24840542310814e3ee8d291ac4a9.nq.gz
│   ├── 2372ddc08113cb3b237bf8a220fed39e4b8c5a61.nq.gz
│   ├── 2391343d11722b25b08e15b77f54cd349dd8fefd.nq.gz
│   ├── 25cad21d7b259ac36ca4b6d6d09b219a4978aea2.nq.gz
│   ├── 287c35ced2d240d241ac235c601ba7250bff230c.nq.gz
│   ├── 29dc11f1ab2cd53da0b10543d5b2a20dc7a20c7b.nq.gz
│   ├── 2c28a08d299301688214464d4c1ceab80177b2c9.nq.gz
│   ├── 314d930585e9ac98c1cd3a16565990c4a665818a.nq.gz
│   ├── 47e7809f0897d1c8c800853262824dd0655bc7e8.nq.gz
│   ├── 50515d000bd41f6f5195f8432d50a9d145aebbc7.nq.gz
│   ├── 56f038a33d805848762ef156c8f188d9f4c692fb.nq.gz
│   ├── 5ae4c59b436ed8e9fbac33e0ad3be40b43f54eca.nq.gz
│   ├── 5be68bfaab1899237b08949f7665d696ed956ba2.nq.gz
│   ├── 5e1ebd19719c2c9c0f2d267414fb39016c9a7cf7.nq.gz
│   ├── 6f0ad8b1e742dd8489081e3797362af12a702328.nq.gz
│   ├── 6f7b831f1aa8e2176b5bb2a281d7a2c26ecf2d11.nq.gz
│   ├── 7327f9b64dbab679403caf252a5c05126b9c75e6.nq.gz
│   ├── 7c21e7d412836e62465cc144459e271b34d08df0.nq.gz
│   ├── 7ee8c4dd709a7f5320abfd41fb26610c16f196f2.nq.gz
│   ├── 82848b4eaa23316e50ed4adaad52b8efb1079236.nq.gz
│   ├── 850b241461c021abb15e388c7ecc946095812172.nq.gz
│   ├── 9b76eb8a5c4e26d8a00cdabf27f43f5c5e8a296b.nq.gz
│   ├── 9f9fa4b292226d58ca8b1af18de8502fecbe1213.nq.gz
│   ├── a41025ffe02334abfadcb7f31392773519068ba2.nq.gz
│   ├── a6cfb7ec3bff2502472c32168b769711fabf4413.nq.gz
│   ├── ab1033bd37224ee84b5862fb25f094db73809b74.nq.gz
│   ├── b0d25a60489083014fbf6b6183ab3a1157089057.nq.gz
│   ├── b393583bddd14b9b454ecb17f768b543cc455639.nq.gz
│   ├── b3d6ffdaade3ee0f25fbb40ed941b7b4a8a579c3.nq.gz
│   ├── b4812196aba347245bec12e42dd152f74cf0bb29.nq.gz
│   ├── bc299c403b5f768ac654d8fe6af57a9fcaee829b.nq.gz
│   ├── c33eb225fd4a275e694635df06629f7740058dd9.nq.gz
│   ├── c99e75ca2dbc8b23a24ba0d0b35e8da772786c83.nq.gz
│   ├── cc495e7f85b7bba37f182226c1e50967ebe5fe8a.nq.gz
│   ├── cdb390865a6709128099af9bcec4853a85a35732.nq.gz
│   ├── d0ba84ba0b167dc6c908792d469a521b08ef4003.nq.gz
│   ├── d85ea2787de07b9511a9fa3407d888a5c423a7b2.nq.gz
│   ├── dc6e02d5c150debf1b7c7f9326559a11b87e4219.nq.gz
│   ├── e495e3ca0f4bcbd62222b5f545c83cb90a84c0e2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed5fe7758d718b9cb03c9e3b2aeb2feadcc3faac.nq.gz
│   ├── ee69be2dc428869bc4887e7555153fdc9198a9ba.nq.gz
│   ├── f01c32eaea34d6e5f4781ab3b9fa1ee27c631c56.nq.gz
│   ├── f4603bc1bdfda47caaa6cf52dc2e3ada88ce1755.nq.gz
│   └── f6fb6e198386076049be9c6f0362d13cbab95e71.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8355851ad8c054799540d9f76d7c6902b3b9d602.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[django-ses/django-ses](https://github.com/django-ses/django-ses)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
