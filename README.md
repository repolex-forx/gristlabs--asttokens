# Repolex Knowledge Graph of gristlabs/asttokens

RDF knowledge graph data for [gristlabs/asttokens](https://github.com/gristlabs/asttokens), parsed by [repolex](https://repolex.ai).

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
rlex download gristlabs/asttokens
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f97a6e1403d9f0e93940a11b507524550a5c3896
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f97a6e1403d9f0e93940a11b507524550a5c3896
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bc8a02c21ff6a947deac1f30629e5ecf3762de.nq.gz
│   ├── 03f218a338f998656ba6f4dcc5c409f03aba97ac.nq.gz
│   ├── 0a1bd1adfa71b26e38ac2984107fb3cddc755458.nq.gz
│   ├── 0cbc6d26831f4325b923b260d47d41df2cbafad5.nq.gz
│   ├── 1171bdfea913061e56644ee29ab5d7cf8f42e154.nq.gz
│   ├── 11fbb4a22107c207d7067159b58ec2ee6e5f4a2c.nq.gz
│   ├── 19272d6b9e00cb2619037a00224283d9f5c547c0.nq.gz
│   ├── 19a05ccd76158c954f645635082efcf1594ab49c.nq.gz
│   ├── 222b79270d09fc933c9af4e23834dd6c7cee08df.nq.gz
│   ├── 23383cc3d9ad7c129f0cfd937eb30291e5b2e1b1.nq.gz
│   ├── 23f7d2b66f210c589dcf5bf165046e840e7203ca.nq.gz
│   ├── 2a52ce4af558a918e39c2c573948ef0f861d4be3.nq.gz
│   ├── 2a5fb58cd88aab08f9f86e30bc49576d58b41204.nq.gz
│   ├── 332e2e7236c7c9624b57d2693cc9ecb15a71c068.nq.gz
│   ├── 3d3fa348dfc99baf97926dd5b0f01ca8a0a8e9c3.nq.gz
│   ├── 3f1bc816fb236e30b197e0ce04c52c4fd3d3723b.nq.gz
│   ├── 43cc6342e992a79859b01b545b75cc6773609c45.nq.gz
│   ├── 4c33f941fbdf89c254e07fae8ef994a52a87b74d.nq.gz
│   ├── 4f66f4c0e6176150e5af74095c68ac16d287bac3.nq.gz
│   ├── 539a0d408c8d70181d63296b4cd83a0f30a7164a.nq.gz
│   ├── 587765b5a7b05ebfb4a8c670406d0cdc61d4085a.nq.gz
│   ├── 5c9cd05876f054355efe977774855d6b1464ea6d.nq.gz
│   ├── 5d7f09afe11d3ab3b80aa020f8d27582bf72516f.nq.gz
│   ├── 66cbc10b298cf29a3d0d01d3a25a0becd582acc5.nq.gz
│   ├── 6a67b9b684686240dc210a917bea7a901dfed3b3.nq.gz
│   ├── 7085e57f0f208e1b92542cf86b1e31f59c3b6d9f.nq.gz
│   ├── 735ae7fe4675e5bad4509726cae67cab2d908b7f.nq.gz
│   ├── 7379706192ee2e0ed51b6a333a8865c7fae27ee9.nq.gz
│   ├── 78765c854440a458281b24a68bdbc1d0f258585e.nq.gz
│   ├── 7b717d9aea96ea5d4cd88bedcc6b108d96331c38.nq.gz
│   ├── 7be27b18cdbe677a0c3726102b4a41ec9be4febe.nq.gz
│   ├── 813469fe86f798b1727cbe34dbf4e934306a74a9.nq.gz
│   ├── 87b4e51e452176e06cc3ab0741a5f58fb93a8c75.nq.gz
│   ├── 87e9f1bf9b521a515fcfe64dbd075667dc4b5ae2.nq.gz
│   ├── 881c69a03f5816a8488c4b133261628e48c284a9.nq.gz
│   ├── 88f9d955d19fc719a3f0b4a4e544731a4a75bef7.nq.gz
│   ├── 8b5adf3800b3d3f87d1ad1e5ed8c6d841fdacf6e.nq.gz
│   ├── 9a895edf656044896308d07d10c23bd42d9f9569.nq.gz
│   ├── 9af3e17e028d5718e9a34da08d4bc3c6757c0596.nq.gz
│   ├── 9b259bdfcf9022e7f4999a318ab7261300644e11.nq.gz
│   ├── 9d35aa3a021c530730a2dad28c68ce90a583370a.nq.gz
│   ├── 9e3c15a4555b652e1b03c9affc049da658f70591.nq.gz
│   ├── a178ca6d2da186dd7de44c19876f115cdaa421d0.nq.gz
│   ├── a34dad32c9e5aea297cd1e4463229bbfd8e81028.nq.gz
│   ├── a9ba33dbe527b5a0cdfbbbd3b0324c5ed4186830.nq.gz
│   ├── b5b12244db6b5c605e8778ae05b5c5b3c2d1a500.nq.gz
│   ├── c654af3c71782896800f5d91c8a63a43cda84703.nq.gz
│   ├── ca1af58baa0c4607f83e1b2e466aac5372859b79.nq.gz
│   ├── d49672be86c2be115824d70f61ffddb10fe8d5cb.nq.gz
│   ├── d78a44db58062d30ec26b2a3db421b3e4751e49d.nq.gz
│   ├── dc593564ff180f9a5a01704359e10ba206527534.nq.gz
│   ├── ddacb4777010f6a845be0a6dc54bf359a20abbe1.nq.gz
│   ├── e17b92cc63b2e2e14a300fa2a39af4d98d49842f.nq.gz
│   ├── e1d6e4a1868615369c3fac4d8bcb550c16291d53.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f5a8aae44d1d8a056158a7b5e0b08b6f02a50bf2.nq.gz
│   └── f98effa6c18a89bcdfec184e002091b133e5839f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f97a6e1403d9f0e93940a11b507524550a5c3896.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[gristlabs/asttokens](https://github.com/gristlabs/asttokens)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
