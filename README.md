# Repolex Knowledge Graph of jazzband/tablib

RDF knowledge graph data for [jazzband/tablib](https://github.com/jazzband/tablib), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/tablib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 966876c76a6378557c1951badc1665b4d1375875
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 966876c76a6378557c1951badc1665b4d1375875
│           └── chunk-001.nq.gz
├── blob
│   ├── 035ebb87dbc3a11ba53a713842d8e6c0bd26c896.nq.gz
│   ├── 060d0742fe2dfb3fe82269ccff812f7f845ede41.nq.gz
│   ├── 08693375ea12888993c6f70b8c7597d8e8d15794.nq.gz
│   ├── 08c7502e3e78148aea7036b52340a827431534d5.nq.gz
│   ├── 0ab42b3eb0df78b1b040d9e2fbffa9ab918d6fa9.nq.gz
│   ├── 0bea5508f70a3ebce43f79ac185557051cc41ce4.nq.gz
│   ├── 0f410b14bb7653e2b26bd134dc5bd8c2e9e99c5b.nq.gz
│   ├── 0f72e9caff26a0631038b30a10f0bc7e45231885.nq.gz
│   ├── 16737037369fd700d718e7b5050f0af8a9fca7fa.nq.gz
│   ├── 197a1856d6d3160829590254097f4696b99f39a3.nq.gz
│   ├── 20204201eddab4cbbfd6f002de9e30e33e681f30.nq.gz
│   ├── 21ed1016512cb475dddb90ebafbf027ec8f7fcb9.nq.gz
│   ├── 246188369f135cd34a71921030731a8c28d9fff5.nq.gz
│   ├── 2911d6dab26ea074a2c9bb8eee269cedde294857.nq.gz
│   ├── 308982a557166ad19b409fac8a09dade6ad45439.nq.gz
│   ├── 32b87e390599b474a12da34a3f59934938ebe544.nq.gz
│   ├── 339ec22b11798877814c3140bbefc26488eed673.nq.gz
│   ├── 40329185e4d6a8d428048a98fbc78bead75ff587.nq.gz
│   ├── 4c2b49f95b491b9b0b886529a802fffa61211467.nq.gz
│   ├── 4c82fbe27658773078016684476920eeaa430912.nq.gz
│   ├── 5e5bd595f8d42a5fec74a769479830062dbc1d22.nq.gz
│   ├── 688e0943bde12997892e230f559c990205820ada.nq.gz
│   ├── 77f3b6b3460877c12ec91bba3e9e19f0b1dd5923.nq.gz
│   ├── 78d5e94eb8bb76ad179566a69663fb4cd2d432f3.nq.gz
│   ├── 79816111b604af8fb5f79592d46ad3244e415de7.nq.gz
│   ├── 7b98a100289468447e0e42a59e3140083aa8e242.nq.gz
│   ├── 7d22dfe941658a3e902f7992ed04d090e980c750.nq.gz
│   ├── 8493760deb70d89847d3a3ee8631352065d8560d.nq.gz
│   ├── 8bc8b28618339b5efcafa2cbfe8f0e0b6004ab5a.nq.gz
│   ├── 8bf4ac990bf00e5a4f8d486e176ce29c0a874979.nq.gz
│   ├── 928246c8e449edb5a54a194e37dde7b929b0e6f4.nq.gz
│   ├── 9ac6c408eab5fa1539b2f351f4fc8b6ec15afec4.nq.gz
│   ├── 9bb62e79c3eaeaab08ccba51f838c41fc7ebcbd6.nq.gz
│   ├── 9bfca256684905e950decdeaf85de465c2977b63.nq.gz
│   ├── 9d1e0987bfc323000b570d680343f00c53ddbc3d.nq.gz
│   ├── 9d5fd7e0ef88489245e08be1d03e4957157d50ac.nq.gz
│   ├── 9d915590df37ddb48b1ae1442227c34c5db400eb.nq.gz
│   ├── a4f9d80c39dcd1ae49de5fa8a62dd7805ec27f90.nq.gz
│   ├── aa0122762e5a6b387b5902799471b2c9a41ae1e2.nq.gz
│   ├── ab64ad25fc9007f5c5ba1142dd71bb5e85c39d74.nq.gz
│   ├── b0b56fd2323cf5e0809c756a829327a64c17a693.nq.gz
│   ├── b2d073d061322997abe6e60cf028dd657c9b190d.nq.gz
│   ├── b3ad88bd77cfba4a3ae6b996ca78ed7a3c20c48e.nq.gz
│   ├── b3fbafd9af8407b42c0f22bc7816243736173f33.nq.gz
│   ├── b6ff2b54006ededf10dabdf0826dd55d0c692096.nq.gz
│   ├── b74a045028af5bbf1d7e12831fa88dc44ce8bc2a.nq.gz
│   ├── ba3e05304176487cd661ce097e5750ac383c84e7.nq.gz
│   ├── bd53a2a8f389873418c3fe5270fe72527e40a76b.nq.gz
│   ├── bd6e41e3c0d736480867cf6b59ceb26df2925a5f.nq.gz
│   ├── be7f8c56de0e4508ca2594343845203b7cf9cf93.nq.gz
│   ├── c20cec11819375ed0852596ccec6f5ebd9ea6b82.nq.gz
│   ├── cd73e6574899f595d1065e9c5ceeb6a553e192dc.nq.gz
│   ├── cd92bfda2155184691abb177a555b6a091ac9326.nq.gz
│   ├── cec9947798c3016776f0d9218da7dedf9560a30a.nq.gz
│   ├── d528c7bf8230d76e874fb2221ed63e7e7a05b91f.nq.gz
│   ├── d698d59ffa91be9b48ce6921eb574549736a8a5d.nq.gz
│   ├── d91f050084a6dca05c51d54538a0e0a9cc6a1bcf.nq.gz
│   ├── da2699ac8775dde75c932bdd5b6bed3fae6d293e.nq.gz
│   ├── db57a9c0a855a5bb88b42e493bcee94532967e65.nq.gz
│   ├── db6e4c4080f06dbcce073c4f6ba7776c26cb5aa6.nq.gz
│   ├── dd98db4ba3ad36b2ae7e617e4220dcb86b728523.nq.gz
│   ├── df3ae4039cafb57b78ab4ad649a9266cfc447d12.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e3cb3f30546522fad6ae71b223287e1f01062ab3.nq.gz
│   ├── e4c2ae6f9730e29acc7413147219c54db715ec63.nq.gz
│   ├── e4ec8f9e9dde9f9fd9935f7c92bb9107baf31411.nq.gz
│   ├── e57e1d9ed12cfcd140997ab1c23ad105a89dd9b7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e86c87426cdb606124f6f1eef2c1a4171246d3.nq.gz
│   ├── ea3e45c40317d0db67f6ea4471790068b538e8b2.nq.gz
│   ├── f61df365138eea6429d61476d3234916ed5e0cd7.nq.gz
│   ├── f64e2622f2273c61c8381d6b3f1dc78ff901ceb4.nq.gz
│   └── f85770fef901c5725dc43cee1f2754d22d520f75.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 966876c76a6378557c1951badc1665b4d1375875.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[jazzband/tablib](https://github.com/jazzband/tablib)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
