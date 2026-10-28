# Repolex Knowledge Graph of zarr-developers/cookiecutter-zarr-store

RDF knowledge graph data for [zarr-developers/cookiecutter-zarr-store](https://github.com/zarr-developers/cookiecutter-zarr-store), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/cookiecutter-zarr-store
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d8f692940f64d3dce711553a50fde24ce92f1e2c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d8f692940f64d3dce711553a50fde24ce92f1e2c
│           └── chunk-001.nq.gz
├── blob
│   ├── 04937ed0b08bf44fab52f46423e3661f97cc5458.nq.gz
│   ├── 0925057b7184519eafa2e066f3b7ae4c39219c54.nq.gz
│   ├── 0a220258381104b45c438cff6f0d5493cfa3703e.nq.gz
│   ├── 116ecf3a95c168d0644fd62aad4eabc2fac99ad5.nq.gz
│   ├── 20fd2b8d45a60f78bc4a251727b3f5f94025ffa6.nq.gz
│   ├── 29281f5be9e2de2bede1da4e6aa8908b24893fdf.nq.gz
│   ├── 37719f35229395f62892924bded7da949389c76a.nq.gz
│   ├── 3bfe332496ee2ad66f50764f7700d935d5ff6b87.nq.gz
│   ├── 3eedee4488eb75c281c98b995ea881d50229ea41.nq.gz
│   ├── 42fc08bca23a07e6828d8169a558f9808769c9bd.nq.gz
│   ├── 441cf30822b65addff8c7794b4c1047b6c1a1554.nq.gz
│   ├── 44c771088893af3aaa5a4ac22e0cedf82e79acf0.nq.gz
│   ├── 513a4d35cfac4b7b5d26557b322d28e6b5c04139.nq.gz
│   ├── 553384e0bda73a2dc297faa3718f37ac3c4150d1.nq.gz
│   ├── 566f6536fe1ec85c573955120dd335733562fd46.nq.gz
│   ├── 5b281e0f29c066e2689ed4fa0d595e15028bf9c9.nq.gz
│   ├── 5c84191cc150e3bae8c14cda5aa956534eebf524.nq.gz
│   ├── 66c2ba6f1c8b625d38a0404affe9503d0e31f203.nq.gz
│   ├── 67aa5e0a9bc6fce4ef782aceae7114d4db5c6406.nq.gz
│   ├── 6a293407b3a7b11f3f7540b3a7a02bbba323d492.nq.gz
│   ├── 7da1f9608ee1595463f3aefec0e087e57ca6c49f.nq.gz
│   ├── 802d70240488a8dcf699712d38a89cdd16737362.nq.gz
│   ├── 863f2809fd745fe6944016ff0b0cb9ec2ae7fb74.nq.gz
│   ├── 8dbd22a57ae8d2925d68b9d8079aa000bfacd4d8.nq.gz
│   ├── 8f93aa7d66b6f75115f5ed8b29a195237bf92bc6.nq.gz
│   ├── 962ad6b0c26fae9b40e7bdb1499c016739eb8554.nq.gz
│   ├── 9cb5ec9a784657bc02bc01f3fe8719d0a8d94b27.nq.gz
│   ├── a000ded16336fd7254d194a6378ed6a2ea5af62f.nq.gz
│   ├── a0d41f9841377b1feffb3c1e21c4da64222510c8.nq.gz
│   ├── a0e3929e87d79460dfb0df570c444efa33eb3709.nq.gz
│   ├── a2faf1a285427aa888810eb06eff3c42f33f3533.nq.gz
│   ├── b6115e6e49ec995f7cb7908df56bc66632a265dc.nq.gz
│   ├── ba05f23fcc2822fb97314ae4fb62e5ac43bd373f.nq.gz
│   ├── c85de37d219587bb2838bde76d1349457b9d64a2.nq.gz
│   ├── d352eec4cb5759f9592ee05ebdbe73868e2bc8ac.nq.gz
│   ├── d8e8d4d57a31426ee1d98b6a7d7436e8aa0e1e3b.nq.gz
│   ├── dbc3b95333c27dd83d1525afb83eb95e84e55af3.nq.gz
│   ├── e46578e312b3a3ffc7afa73715b837dc9fc7fb03.nq.gz
│   ├── e6623c3ec9619da9fe8b671e9408cf4026d52549.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ff5171d55d517df30177db926e7ac65c755681.nq.gz
│   ├── e979e70ef376d568ce826216801527f46df85139.nq.gz
│   ├── e9b99c8214ad45a22de155b80f448a2d95f6dbe1.nq.gz
│   ├── f3f810368be2b74b210cf2a557b8d6b0ea1982b5.nq.gz
│   ├── f77f2b579a8055056c1391d04447d0482e150d9c.nq.gz
│   └── f9c77ae00138ad0aa89f4cad969e4c1250b51215.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d8f692940f64d3dce711553a50fde24ce92f1e2c.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 53 files
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

[zarr-developers/cookiecutter-zarr-store](https://github.com/zarr-developers/cookiecutter-zarr-store)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
