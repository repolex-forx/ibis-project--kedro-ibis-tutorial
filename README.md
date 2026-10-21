# Repolex Knowledge Graph of ibis-project/kedro-ibis-tutorial

RDF knowledge graph data for [ibis-project/kedro-ibis-tutorial](https://github.com/ibis-project/kedro-ibis-tutorial), parsed by [repolex](https://repolex.ai).

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
rlex download ibis-project/kedro-ibis-tutorial
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 79df70547337cbf15e42e0102bb57be15983843a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 79df70547337cbf15e42e0102bb57be15983843a
│           └── chunk-001.nq.gz
├── blob
│   ├── 086c74635cecbfdd439d8597f4d96f9b7bf49c90.nq.gz
│   ├── 0f7f7a99accb5242e79c06045c67cd51d7e19fd0.nq.gz
│   ├── 10e60dc64b9840f49711d9980ac46ffe93e91217.nq.gz
│   ├── 14369b43b7ff6f8ed12cc1e0be011ed3d0d99fb8.nq.gz
│   ├── 16c0261f1de3c0f2ee005fe5ed477e37a60b9a11.nq.gz
│   ├── 1cca0a526c6d9e59a804ebf57d08598b99974c68.nq.gz
│   ├── 1f6ddc49f9060cf6f25e98ab5b8f60a0793132ce.nq.gz
│   ├── 213b95db17d5c0c43f06ab317bbd5277152cff3c.nq.gz
│   ├── 259c5ba22164f69e657c61f1ee42c1e84258ec79.nq.gz
│   ├── 25a776fc6167d391e5cece6367bc64b63d11214e.nq.gz
│   ├── 26f12880a536a4aca87eea93ef3f87b6293e6bbb.nq.gz
│   ├── 26fa13c96f2ecaf5fbecf3d450078ec19854158e.nq.gz
│   ├── 29392bbeb20937428b634605e5c661489b1a78b0.nq.gz
│   ├── 2b28d6c1db4886195d8cdc56e59ee78275c52c28.nq.gz
│   ├── 2d4272e3122c8d200ed56778b14c1bb0f0455a12.nq.gz
│   ├── 3195f1c7dc9f4326fd1312cb1086273852dc6f39.nq.gz
│   ├── 3b81ffccfdc8c03d28e656d171034d09ad2fdb13.nq.gz
│   ├── 3e82f7d41b466202b01b459341cd63fa79e86133.nq.gz
│   ├── 416786afa58c0354bff8d448795389b86777c22c.nq.gz
│   ├── 43a91bd247cf7df6733333ac6778957c66dfebca.nq.gz
│   ├── 45c46c5f151f2432fdfe97267240342db798a030.nq.gz
│   ├── 4784a3513a3ac4579cb16acde761e67f313f3ae9.nq.gz
│   ├── 51a4444c61e508eefdac82d532d110fb0b1758a8.nq.gz
│   ├── 5ac07fb35fcbbc805faf39b89cdb17bde2978db6.nq.gz
│   ├── 5f3ef2609ab42ad4dac7cf50e2f1dc75c0b501f4.nq.gz
│   ├── 68e431a391fadecde4d365768497a236ca8fb4e8.nq.gz
│   ├── 6d64cc58103fc21c9d431dd379510eb2f86e7095.nq.gz
│   ├── 736730bcc165e3924259ce37df388bd056e2ba9d.nq.gz
│   ├── 7c169ce49f9b54914e4a4f7ecf07a83c66d601c0.nq.gz
│   ├── 7dd0589fe9f53858d49336cc9fa05c31dfcc3907.nq.gz
│   ├── 8795656b0fadff026e177fc59055a0044e5e6977.nq.gz
│   ├── 8c98b9c366aab1f3be9e2962b17ce7e660832b70.nq.gz
│   ├── 9cc5e8891b4da28b230ab185a2b6932a28529925.nq.gz
│   ├── 9ee97e8723604443c305bfd5b0da576dfda91c01.nq.gz
│   ├── b0323f24047a63e2b81a0ec87ab7e8a5d8f72d1c.nq.gz
│   ├── b135e80c2c031a76c8af07305ec7ca65cf969aa1.nq.gz
│   ├── b1e511a0ae40705e86b9ffd37fd97f3d4841779f.nq.gz
│   ├── bbd1a901a644f41fbcd2fb062a04f621560b5b1a.nq.gz
│   ├── cd48599bad4f43e7c9d3f2fff0413936df8d3b78.nq.gz
│   ├── cdba0c738828e79c62a96871eb29d59e259b3a75.nq.gz
│   ├── d17f629528c2272cff58effbd2339ec8eec7b37b.nq.gz
│   ├── d4398fc2cab99bd9177903ce08ef871eb8d29271.nq.gz
│   ├── d45a0182674af4f5e01a0a60dcda1bebef34b087.nq.gz
│   ├── d524ab7fcbf18ca68182b329edae7495b7438a78.nq.gz
│   ├── d60f1f480b920f77a6dfaaed4ffedcd053da1727.nq.gz
│   ├── d668964242399b1edc190e2fce60ca875ebed97e.nq.gz
│   ├── d97856ee865d9555fdaccfae400283bb20baa197.nq.gz
│   ├── ddfdfdea5af5e87d16ae88d86aac605d786fa514.nq.gz
│   ├── df4d9e98f428e9f3957a478b0119b81afaafa1a6.nq.gz
│   ├── e2f95fe9f328989fd405322b3775b65e8249301d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed15a81428fe61ea0490c4d89660f0863aae1ff3.nq.gz
│   ├── f2e3bd9df8c696ca1431a4f80e6e5ee86b611a73.nq.gz
│   └── fcc59b4be1aae09782ea9f3d69e13f88d4b3f268.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 79df70547337cbf15e42e0102bb57be15983843a.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 61 files
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

[ibis-project/kedro-ibis-tutorial](https://github.com/ibis-project/kedro-ibis-tutorial)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
