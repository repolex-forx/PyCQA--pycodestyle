# Repolex Knowledge Graph of PyCQA/pycodestyle

RDF knowledge graph data for [PyCQA/pycodestyle](https://github.com/PyCQA/pycodestyle), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/pycodestyle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96c007cb4e1b8ff3c632fcc280740d4be6b8cd3b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96c007cb4e1b8ff3c632fcc280740d4be6b8cd3b
│           └── chunk-001.nq.gz
├── blob
│   ├── 053148f848642cb6c79ecb61968f0a9d3fea8bb4.nq.gz
│   ├── 0e546234adca57252f039a46e12654cf3706c13e.nq.gz
│   ├── 148269ace9e5cc8a590756eb1eb8a5f78f7d4c50.nq.gz
│   ├── 1a9011248fc47c4c1a170028b0a7d1af805e408d.nq.gz
│   ├── 1bedee5d96bf3c8b8fd63134c9074300e31304b5.nq.gz
│   ├── 1ecae62eb9bd030495eea9167b2bbe707c23f1fd.nq.gz
│   ├── 20a0eab8328a87c454ee0e3574ce6438b843b7b4.nq.gz
│   ├── 2355f55e28bc0182d7e19657bd1d78ede5915e42.nq.gz
│   ├── 25e05b058c5f4ca9a260e9f19c7b15dee1af7d19.nq.gz
│   ├── 263ea367be69e9fde3600c4a697b692dc6a39436.nq.gz
│   ├── 2875f9ea6ce018f5643083be9e0a6ec0ea388661.nq.gz
│   ├── 36fb4aa7ebe8e0940e732970e317c444d26ab551.nq.gz
│   ├── 3d02492e5bcebbb8dafb7e592596d1c5184e984f.nq.gz
│   ├── 41f0d0fc6445bf07e42649ccab688b570767a215.nq.gz
│   ├── 44737fedc4b5473fde905143b66e8b987c516238.nq.gz
│   ├── 4769e06f65025819069da7f402d742125702fe27.nq.gz
│   ├── 4870fcc2327f98d5cb4afd0eeca0df63bba57203.nq.gz
│   ├── 5aaee6204565043e90bf8b63bd231fe2f42d9660.nq.gz
│   ├── 5d1046cb0a4b07dc41f77d73e3a0558d6c81531a.nq.gz
│   ├── 60fcd2390887ffa95291096d1a3d035bb780b8b2.nq.gz
│   ├── 67537e72ea9cc10f56fe722958e31d10eec9851d.nq.gz
│   ├── 6c71fa2b0f295e45e85999b6ea35dc203e225d03.nq.gz
│   ├── 6cc1ac84e1ef9f279711dab2c5136687385658e4.nq.gz
│   ├── 6f96df7fa4165307d08de5e4ab90b140c3e8d9a4.nq.gz
│   ├── 723f0e1cec38f0b44905c9bb2fc58558ef82d4fa.nq.gz
│   ├── 72d9921cc18d8f473cea6c13842ebede4bb3b271.nq.gz
│   ├── 7886e804ce3d3bd5d8d00d6758895c9cc4827ee0.nq.gz
│   ├── 7c01edbbea22abb7b05518d14b79c617b4aa8889.nq.gz
│   ├── 7ef468901ab84426d7b144c21a8c608b503f0aaf.nq.gz
│   ├── 80a5529b5d33b3d58aefd39f50354de5dee4af93.nq.gz
│   ├── 8328cfba9e7f6075b58f4a819b4e3cd2c6ac2fda.nq.gz
│   ├── 87bb5a6a3f857d00467c1ed34c59a21c60152476.nq.gz
│   ├── 88981576efc629da69ec06f6f2af7ca9ac9c72f2.nq.gz
│   ├── 8bf1ba938af9b4993f625db4fc6e708be9f3f3b7.nq.gz
│   ├── 8f68a410c7159d8bd82979aed6179fedf31e9087.nq.gz
│   ├── 937ef721201d2e94243582f3b0f4cdb8c71487d2.nq.gz
│   ├── 959956e5de992a6780a51612d044f84024e08541.nq.gz
│   ├── 96b55b8790138ffbdc48c625244547b735e938a9.nq.gz
│   ├── 96c920f38df658c08fa44a9ae30e77a5f66877c4.nq.gz
│   ├── 99a8118394afd1e2b273639e9e4eadc1319d2d80.nq.gz
│   ├── 9bb4c5811bc573faa982ca283fd46c60a309f1e9.nq.gz
│   ├── 9c065c9494ebe1b30ef60202c869fdde585e16cd.nq.gz
│   ├── 9c33236b7170ab6fe786c408c037591d0ea50216.nq.gz
│   ├── 9d4eb4d08878ffffa9724f3929364fa1b0363d3d.nq.gz
│   ├── a405125a9eb4472703f6400131ceb2a54a8bbc9a.nq.gz
│   ├── a7187a270aef200408ae0717d445bdcea75a1f31.nq.gz
│   ├── a92739e5806be4100908400386d6487abfb68255.nq.gz
│   ├── aabb6a42660896b304b19a4a20eb6717a6bb5685.nq.gz
│   ├── ad98aaacc44d78ee39a012e41597dd075f3832e9.nq.gz
│   ├── ae70e427b6b2024bf130d58ddda5462990ead8ae.nq.gz
│   ├── aefd6540c995858e21cb3e812d51a2ddc140753a.nq.gz
│   ├── b4b53afcc39df4ca840e782530896b11da84249c.nq.gz
│   ├── ba3f3960ce497356fd781270c2a7b8252ba30d9d.nq.gz
│   ├── ba74c72f393828223ff869b778741647db9b2f2e.nq.gz
│   ├── bab8d71cf5eaa079b0f089a4094d89a307d0446a.nq.gz
│   ├── c9b9255f30192c780c5a71b5db24fc0fda8f374d.nq.gz
│   ├── ca06930698bfcab477a5db4517ae50702ef96475.nq.gz
│   ├── caf68d5030af6bb75ad78ccc500130094922f365.nq.gz
│   ├── ce3058a92b30ae9c0650d086caf88e6e8b593806.nq.gz
│   ├── cf719b4df8e7d5921aefc9cb7c26254717f90aac.nq.gz
│   ├── d1f78eae128cf8740adec9079d41edb33f55903f.nq.gz
│   ├── d55bb13228f4d0ccc85f2d3b6f23edd50b9ce2fc.nq.gz
│   ├── dabac0d75df78ec393c505b38cdbb43fa945f552.nq.gz
│   ├── e0a10d045f74e1bc5ec81e504d4b5f70414d2d36.nq.gz
│   ├── e1d5e1b97366ec556f1ec38f8d594bf90847c09e.nq.gz
│   ├── e2f10ba6e9b7e6db7fc264653e3c22ceed339b69.nq.gz
│   ├── e3f2e5d0033d9de8e34c2dd53e9a25f256de7e44.nq.gz
│   ├── e4a75e1c1a3847f9bc119b626f7669e214ff19bc.nq.gz
│   ├── e561fe795f9b4c51180b433232ab3bb351fba5c9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e716b9a1206d1a1eb18985d4281837a50a948222.nq.gz
│   ├── e7a79ae31874e9d73cd478e1d2094745c26dafb6.nq.gz
│   ├── eb73c35e409c0f0ab0389f7f7daf615e78f87202.nq.gz
│   ├── ed21b213be1fd042762e4ad1032475744c0781f9.nq.gz
│   ├── ef87d9291a4dc59a66d9d93973e0f483401102c3.nq.gz
│   ├── f0cb9888664b4469faaaf82f6fe759390dfd4a82.nq.gz
│   ├── f847197639cdd22e4bbf173eae0579afc0b8d087.nq.gz
│   └── f9c706682ecdc8f8b860ff93cb41cb2662dd6ee7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 96c007cb4e1b8ff3c632fcc280740d4be6b8cd3b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[PyCQA/pycodestyle](https://github.com/PyCQA/pycodestyle)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
