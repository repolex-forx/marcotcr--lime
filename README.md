# Repolex Knowledge Graph of marcotcr/lime

RDF knowledge graph data for [marcotcr/lime](https://github.com/marcotcr/lime), parsed by [repolex](https://repolex.ai).

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
rlex download marcotcr/lime
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd7eb2e6f760619c29fca0187c07b82157601b32
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd7eb2e6f760619c29fca0187c07b82157601b32
│           └── chunk-001.nq.gz
├── blob
│   ├── 0220f2493bf1c938e2b30f1d0a8af0d8d37e2acc.nq.gz
│   ├── 02380ad7d9220225aecae128f96c59971f41c04f.nq.gz
│   ├── 096b982bd0c4a8f5c85861eeb7ab1e61ac7fbc9c.nq.gz
│   ├── 17a7391bd947bc37e7d85e2e31ea6cb59e339f05.nq.gz
│   ├── 21165818ea857eecc9b70e7e7c808440935891b1.nq.gz
│   ├── 23d5a8026f4c945337391339271247fc56c828b1.nq.gz
│   ├── 298b925d6796b76f7a3eccadb1562269aed2c732.nq.gz
│   ├── 304f4f6553d24f046df394892d5b431ffb0b1078.nq.gz
│   ├── 32d796bde505f3e2efebc7d5e064729ce2894da6.nq.gz
│   ├── 36b2b66b31e46fa0fd278536c8cf5abb2f24abb8.nq.gz
│   ├── 3866704a9888fb4f248b82cff7cea4a6fa966abb.nq.gz
│   ├── 40b92d2d9851b88b6c4509ee7dddbb7c138fd4fa.nq.gz
│   ├── 426079b48b8a54f4376e989b8c1d463bb0636eaa.nq.gz
│   ├── 45270bfaec42f2dc56c90591b75fbaa550f6eeb6.nq.gz
│   ├── 45decc31e1bed646ff61716795802afacab9fa18.nq.gz
│   ├── 49eca0b6fc8432c7f2c6d830f26c4ec82278172f.nq.gz
│   ├── 4bee9aee3028bc8b3a7255e6d0072b98c7841cf9.nq.gz
│   ├── 4dbb769f0935dc0de87875f10efb1723c7bb0735.nq.gz
│   ├── 4f62a2e310762c311e1c51517dbc8e788427273f.nq.gz
│   ├── 51b50a0465baf354d5f08c76e1bffeaa9cbf1780.nq.gz
│   ├── 5412c7020c6080b56717560be5bf1cbd75d3130b.nq.gz
│   ├── 5fe0dfefcd3dca3b1d169c7ab51b93de327e07e2.nq.gz
│   ├── 63bc05a5578f7d9535d4ca5b5111f266bfae3e5d.nq.gz
│   ├── 68af3dc56998bcdedf92cf5bf39d89760df34a48.nq.gz
│   ├── 6c1739155ec971d43a99a408ea949b3d9b812112.nq.gz
│   ├── 700438d157f4da89d929c7eca767ce9729142338.nq.gz
│   ├── 7040a1feca5bd25f716f1f2a7fd09a25f4fb6c0b.nq.gz
│   ├── 7055a9b59bfe9ffc6d0d34cf79a3c114881152ef.nq.gz
│   ├── 7c18040cceeddd25b7cd2867a8d0f59da04ca974.nq.gz
│   ├── 7cb007d4ab9a387f21eca884ee5ca6bae9595f7b.nq.gz
│   ├── 815f588b180b6f502b853e4822862663d38093b6.nq.gz
│   ├── 829b9c2fbe437ef363ec6bb69a6004fac551425e.nq.gz
│   ├── 880f3d391154abeae8f0927bb68f9af97f1db606.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b4b905402df0616c7c1c23288eda02e5d219acc.nq.gz
│   ├── 926a47928ea4d9de2773d2022883314ec1283036.nq.gz
│   ├── 931f77fb459a05d03e0c44ddc94555a02fb46066.nq.gz
│   ├── 9b13077121d03a7c60fefccecfd7d32ab707af5d.nq.gz
│   ├── a189729abf566ef9a0d9347ad37b6d25252a6ef4.nq.gz
│   ├── a5b6707f275b3c7583c7faf55c24b915aa81314c.nq.gz
│   ├── b02f2058273ae88b3ff00e617fa4e11b7a823403.nq.gz
│   ├── b2f519a5b8e554b7d98cd31f2320558ab3ae6629.nq.gz
│   ├── b37b258bbfb2c1ebe454c03fa01016073f2eb00b.nq.gz
│   ├── b3d82486ba2c33b72ad72d74d3afa7dd295911b2.nq.gz
│   ├── b8ae62fd0472d4df6481be5a660600872e50746a.nq.gz
│   ├── bbf504e66ab1e13be08434b948b1f12a523165d2.nq.gz
│   ├── c0f366a0ce0ebe422a6dff228b87780f16f0c458.nq.gz
│   ├── c5fa1a29924ad795104c6ce7c124a58d1fa06dfe.nq.gz
│   ├── c6187cedf1aa26f60fa171f1d9920fe53f998d96.nq.gz
│   ├── c65816c6dee02ba01fa65b951c7664a6825563f9.nq.gz
│   ├── c99de46677750987ece4ba191b3c9fd020987019.nq.gz
│   ├── d071b6f7a4fa69e2cc4f87f39e491df930f8314b.nq.gz
│   ├── d0d2f728e457c5f8fa9b19f447ab8d9701621a43.nq.gz
│   ├── d8a0931731145acb3d0edb89d5b4cf0587a80666.nq.gz
│   ├── df3c87ab3218c7328a539a62aaed02a98f1727b9.nq.gz
│   ├── df3df0a1c64cf428c8855c08a508c911054e3588.nq.gz
│   ├── e05d9488c0915e614304ce24365513fe2581f78d.nq.gz
│   ├── e2ad324c6299fe92371d19ca43936bbc4acd5eee.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e84c2b090e0fa9b65bd1e8043fde6d6556911d2d.nq.gz
│   ├── ea3940e2a4cd48b7c4a845b24d0985367827de13.nq.gz
│   ├── ea7eca06b04cd7e5178dc112ffa60eb10e643158.nq.gz
│   ├── f4d359f398fb26954b0995b50ffe3dbc3e6e90e5.nq.gz
│   ├── f5b68c6b48b30c7238d6784ce22ccc832efccd35.nq.gz
│   ├── f8236ca7a5cb10e58d5badec49cdfd8a41b9b019.nq.gz
│   └── fb09c03d593937e7e59ad85c4481f6bfde485505.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd7eb2e6f760619c29fca0187c07b82157601b32.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[marcotcr/lime](https://github.com/marcotcr/lime)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
