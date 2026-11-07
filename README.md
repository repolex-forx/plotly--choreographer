# Repolex Knowledge Graph of plotly/choreographer

RDF knowledge graph data for [plotly/choreographer](https://github.com/plotly/choreographer), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/choreographer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ee850422796370086c4e2c8aa878deb414a38fc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7ee850422796370086c4e2c8aa878deb414a38fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0257ac88ff0abecef80419cf2ec276dedb026574.nq.gz
│   ├── 0b71f73821767877d5a60b04ab5700535b56fdb8.nq.gz
│   ├── 0ba670cbc0c9dd6ffc68a5c917e07951c03c14c5.nq.gz
│   ├── 0d8ea1608bf8ff339170b1d4d101af332c6cafbb.nq.gz
│   ├── 0f7508723548438b4c7d9d815171528faa5dfd8d.nq.gz
│   ├── 0f9fc6827fbe761472316fe96fba0f8d08a2a59b.nq.gz
│   ├── 1114dc872d36384cd843b74266675d5cdfe8df15.nq.gz
│   ├── 126f4c439fe884464950b4f76acd59ae8ed42e6e.nq.gz
│   ├── 19847a022fe9732a442b81dc15298f80ad235881.nq.gz
│   ├── 1da299ba104ed3ff561878a06123a219d69d4dee.nq.gz
│   ├── 20c3502e76136fd432b2fb469fa2730fb39d42f0.nq.gz
│   ├── 214fb0070693b9f350b7efc5bcf110fec9e38385.nq.gz
│   ├── 269baa838cd25597854a9f1e30cdb041f23677c7.nq.gz
│   ├── 297954d8aa6a78f5c4ccaf232cdb4b01d4433fc9.nq.gz
│   ├── 2b68f0c715716d7893d0eb99b114ec1352829d03.nq.gz
│   ├── 2d0d350a94527b23dd03f7c4177b46f3a462955d.nq.gz
│   ├── 30000ada9eac46310261ed5d97d69f2c3428b0a1.nq.gz
│   ├── 357132f3f81a003a7278659df7d81de06db306c4.nq.gz
│   ├── 35ec58831065ba1dc0f3c1e48f3af5f4249a10cf.nq.gz
│   ├── 41ff391405b31b58bcdfeef8f949a27997d3a9eb.nq.gz
│   ├── 448a1e181e6b68b17cbeebe1b849516b192f3551.nq.gz
│   ├── 45efdd7b98cddafa35c202f62a274d84aa150893.nq.gz
│   ├── 4b6a7bdafb3fea517050ecf0112b0fed4f7c995a.nq.gz
│   ├── 4f4148fcd8a76f3558df6e30cca600f154bb70e2.nq.gz
│   ├── 60174ed544fa8f6cee250e59a4e7debed1bb796d.nq.gz
│   ├── 67512d5b392bb99644647545d63b19e8fabf7345.nq.gz
│   ├── 6d87be374363f9fce12f2524fd49216c7fa761fd.nq.gz
│   ├── 6ea2e5199a416d92fda350967ba68c16c1b93238.nq.gz
│   ├── 7030610b9916bbb991b77fad6f1f22d2dc5088b5.nq.gz
│   ├── 70a10c9c4332d602b7f691e6eda18d140aacc73d.nq.gz
│   ├── 7412fc0adb798b26b06ce11048ad1a283f5f8ff7.nq.gz
│   ├── 792077450d3ee5faee8cf106e24833ddc6c36421.nq.gz
│   ├── 7e4ccbe2d85ba42893706b37bf911ba9b7a20884.nq.gz
│   ├── 84659846ab7051ec13ada5c1d3313f82046ba66d.nq.gz
│   ├── 86a83132c71fc26c8dd8e58f294edb2a93371ee6.nq.gz
│   ├── 88dea264a00a7e2ea66fe74b6804a03325685f55.nq.gz
│   ├── 8c6e02139e25c119da6f07cd27bc711cbe443491.nq.gz
│   ├── 900159966c79b10c7b24d6a371645fdf0110b0ef.nq.gz
│   ├── 9e671e611c834c6758e1249fa5073057a3d5771e.nq.gz
│   ├── a1a502b14ff55b29f9f4ff34fd78790471f933f2.nq.gz
│   ├── a468084792e71330ac727fb582ce29d9c0ab0d6a.nq.gz
│   ├── a77f2ab360fadd49a6804a132c2107e0f1a6bbbc.nq.gz
│   ├── abcfb7908f975a11a1c5d3fda271fddc8fb72b41.nq.gz
│   ├── ac14bec8daf1675504eae2db1bbf682499310d13.nq.gz
│   ├── ac19e86a08b67238c3772bc8f08d212186b6c428.nq.gz
│   ├── af0d2143d4c1f01688b4427a3e251f154c506580.nq.gz
│   ├── b0af3669e34fda4dad9af7c7ef0026871108a93f.nq.gz
│   ├── b1d4a51f2a2108592fe02d2729956cbc16110cca.nq.gz
│   ├── b2afc338d11bc6ccda17fd85789024349a7a6799.nq.gz
│   ├── bcc60e4ef3a9e26ac042bcf0bb816534349d59e8.nq.gz
│   ├── c0397f4dea8313d29da6b18bb7c03495a040619a.nq.gz
│   ├── c166f4700769e009a38c09bd85e400929123cf61.nq.gz
│   ├── c1d2d25010335fc25a382cbed64ebeed52ae6c7c.nq.gz
│   ├── c34e10ccd9245d86bf0fbf7c656dc7e4ddc78320.nq.gz
│   ├── c57925206f4f323085ca1a088432dd27257d1756.nq.gz
│   ├── c6c3b1d1f9aa47a3ea18d49b778242dec0345526.nq.gz
│   ├── cce6324638c6ff17ea5cede34341bc8ce6944ed7.nq.gz
│   ├── d636e55be9686d1d9ffdf56f55c2760c76484450.nq.gz
│   ├── d64bad42d76b3440b3049c3b426234e15be461a9.nq.gz
│   ├── d66e60042fb669e5338fcf025feb76e6a8f46983.nq.gz
│   ├── d76759fe396ae67d872c1a5814675d2b434d031c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef134f3c54a2e00d38b77bb997064aad02d1f243.nq.gz
│   └── f036a65c34517f51718b20b76710ad3ee5273eb7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7ee850422796370086c4e2c8aa878deb414a38fc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[plotly/choreographer](https://github.com/plotly/choreographer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
