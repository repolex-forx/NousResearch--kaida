# Repolex Knowledge Graph of NousResearch/kaida

RDF knowledge graph data for [NousResearch/kaida](https://github.com/NousResearch/kaida), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/kaida
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d881d44490fa947e487efd18ed368136042dc41f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d881d44490fa947e487efd18ed368136042dc41f.nq.gz
│   └── repolex
│       └── d881d44490fa947e487efd18ed368136042dc41f
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b43e8c8ab08aeca87742adce52e965364fc3d5.nq.gz
│   ├── 0700fc0a71d0490ed8029a620f5c7cb68efa591e.nq.gz
│   ├── 096ef95e3faf3327df68a30aa7fc9243c27d59a7.nq.gz
│   ├── 11a16836fa0fa83b18867e035be1a10c39ab0ac9.nq.gz
│   ├── 158a03bf2cd7cafaaa2ef4ae64f72976c4031de5.nq.gz
│   ├── 15e387836f162c4e77509ba12f9cc486d7d0b49b.nq.gz
│   ├── 17de371548fb03b3fa33670e577c33371358b28c.nq.gz
│   ├── 19429b2d7f3ec9f84f2cfb01e0dea9e3521af5fe.nq.gz
│   ├── 1b6c787337ffb79f0e3cf8b1e9f00f680a959de1.nq.gz
│   ├── 1c2fda565b94d0f2b94cb65ba7cca866e7a25478.nq.gz
│   ├── 249e5832f090a2944b7473328c07c9755baa3196.nq.gz
│   ├── 3031007dea482ad2b376e7980c757c66e1895f29.nq.gz
│   ├── 3099fd84cefc54228922c51ec8317a309832d391.nq.gz
│   ├── 3d69568033cbc10286d8abd67eb5a2a0add8e445.nq.gz
│   ├── 3f3bf83c476c7c32d258b667a1525198d9b62331.nq.gz
│   ├── 4bf19ef1772f4b17beb5edf07a7215d3517ea422.nq.gz
│   ├── 53fa05dd76a974784848d635e974b5d0f94fe654.nq.gz
│   ├── 55521e3d89cf0fb401a8fd23cc064e18de505904.nq.gz
│   ├── 5ac4c8fc80b48eed177350de632e8172a8c6552d.nq.gz
│   ├── 6303e5cf50917765c361aa1d8211d088fe82db24.nq.gz
│   ├── 657bf9f6443e21254f10d86d6483c30dc62f41ee.nq.gz
│   ├── 6e33eb74b666042014c11385c9415ec6976d3237.nq.gz
│   ├── 6e74ba3a1909cf713eb66189d7f040ad7d2ff774.nq.gz
│   ├── 7018df49c919e234235d55037be54196e07e7556.nq.gz
│   ├── 7dc5161da5ac8feb3f2134ab9ba6dd18fd725ffa.nq.gz
│   ├── 7fc6f1ff272ee12d8be9694acdaa36b4284eefdb.nq.gz
│   ├── 8568c6b8a190bcf807a49762143533528c15bd64.nq.gz
│   ├── 9661ac713428efbad557d3ba3a62216b5bb7d226.nq.gz
│   ├── 971133db28e4aaf78cb6ca59d28c53fceba85de4.nq.gz
│   ├── ac1b06f93825db68fb0c0b5150917f340eaa5d02.nq.gz
│   ├── b0622fd0407faad951605844fcaa426983823ce6.nq.gz
│   ├── b1b088a3b509e30e27fa9a3e3ea38bac62694d53.nq.gz
│   ├── b400a5eddcb952cc657510ddc4171965c26ee58c.nq.gz
│   ├── b6840a91240671548523cce1414995955462dc35.nq.gz
│   ├── bc298e700e211c83e5fb5bad619a9d8aa2fc844f.nq.gz
│   ├── bd68789be32131939ee329a5f3658653aeafa2f0.nq.gz
│   ├── bfeaddf48ad6aa841fc8671acecc9cfcae36de91.nq.gz
│   ├── c137c68606e6c091585b1b4e0b1b2403deca1889.nq.gz
│   ├── c1db1338bd9b02e9faf99e7112a8ef772684b772.nq.gz
│   ├── c2b65249944ca1d1bf000b389dff4e6a5a068e6a.nq.gz
│   ├── cd9573fbb46f100f41577b391b79984ae8a93609.nq.gz
│   ├── cf15177f1c3a95ebd19a576f125d16415e198352.nq.gz
│   ├── cf31438115aaeab4a0d8c9abd5e9dc78b4deca61.nq.gz
│   ├── d7b19893b7051340da45c5dc32479f8a6f4af829.nq.gz
│   ├── de4d4a5529c4f7351188616ba068f6d1e1dae67b.nq.gz
│   ├── ec8374b4e92bb69de8556e2409d13404da8eca49.nq.gz
│   └── f1fd2cd592d4ea23e5c8c4aae6ed7b0a1ace8974.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d881d44490fa947e487efd18ed368136042dc41f.nq.gz
├── filetree
│   └── d881d44490fa947e487efd18ed368136042dc41f.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[NousResearch/kaida](https://github.com/NousResearch/kaida)

---
*Parsed on 2026-10-05 by [repolex](https://repolex.ai)*
