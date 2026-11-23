# Repolex Knowledge Graph of Keats/jsonwebtoken

RDF knowledge graph data for [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken), parsed by [repolex](https://repolex.ai).

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
rlex download Keats/jsonwebtoken
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 900010fb1be550ec2cfa8c32038eb154f9ef56d7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 900010fb1be550ec2cfa8c32038eb154f9ef56d7.nq.gz
│   └── repolex
│       └── 900010fb1be550ec2cfa8c32038eb154f9ef56d7
│           └── chunk-001.nq.gz
├── blob
│   ├── 057d36691a8f0dfbf124a2ab560a551db73b92ae.nq.gz
│   ├── 09ee0a812f79573a0e5e42d24d6eb327a493323f.nq.gz
│   ├── 0d2e659642ab8c60e0d40b2a55057efd09ec89da.nq.gz
│   ├── 12301e0110a4c40fbbff591ac55e33b86591c1d8.nq.gz
│   ├── 154cf2b3a49fc90593f68cfa524b53e8c124630f.nq.gz
│   ├── 188c9d8029433c60ac540c340a655bac2f9732a7.nq.gz
│   ├── 1a20479f29ec800fd01f77082475e95f277b170d.nq.gz
│   ├── 1d805cb880e85643debae075140538a30c58bf79.nq.gz
│   ├── 1dd5bec4892b703285cbdcdeb98b8b99ffd5cfe6.nq.gz
│   ├── 1e6911a174892c236ecf021a0a5b2b5418ab4690.nq.gz
│   ├── 25da1228cd862aab53bb191ac0bcb74dced09285.nq.gz
│   ├── 292bbe47252875d6346703d5da7e847c6d1d8c09.nq.gz
│   ├── 2df7451a707b90d8d5142ba348aada0b155a667a.nq.gz
│   ├── 3199873c6b94586fc85bd5cc97e3345e8ccb560f.nq.gz
│   ├── 36272c3f2172b40366015103572041d174132ad4.nq.gz
│   ├── 38c7b66a1941c3a0e2888f72d7d1e57f25bcd346.nq.gz
│   ├── 406f34594d35b042e68677fa9e16df0e8f7d36a9.nq.gz
│   ├── 4613a0da294a45670ae91019b071cccd9b4d909f.nq.gz
│   ├── 502d2a874555ab6c9f040370603a589767fd9798.nq.gz
│   ├── 5a7ffd9800cdbd997ad169bcd2fdeef8bf0b1c37.nq.gz
│   ├── 5b509e4ec7e96751db350ee4a486be6309808c29.nq.gz
│   ├── 61056a54985217c234e5a718818b9a17b97958b0.nq.gz
│   ├── 62c7f506169a9ddac2caf4135065ca47c330b94d.nq.gz
│   ├── 6a89d0f87b7a1ce92bd32646ce6ff9a2b525630a.nq.gz
│   ├── 6a8fd9d30b654573d19b13431d8d436c6cab5148.nq.gz
│   ├── 6c55fdb7eb33419ae253780f81a0b4cdfb21cc65.nq.gz
│   ├── 6c66f198e305dd8b6036ae18981b5a6ac6264620.nq.gz
│   ├── 6e8b0ccfd72747323bec47605e5ebb91e0e79fee.nq.gz
│   ├── 708fa66b3cbb0c7fabb56a06960d682585f3b6c8.nq.gz
│   ├── 746be05317cf8a5d8c395ad6ffa5ddc533ed9e65.nq.gz
│   ├── 794157c62fea4b9a795ca80c09843138aff5e017.nq.gz
│   ├── 7f6986a841233ce3aba45caeee0d9c6d3fa78cb3.nq.gz
│   ├── 7fa67c9e3065c207729df193a0a3e90ce30e7fda.nq.gz
│   ├── 81eac4ed772634d0aeb57ee6cc8b2ae9a37ecec6.nq.gz
│   ├── 84b5e06d92631cc4e2e4db7c23d2d87f132be1c1.nq.gz
│   ├── 893d58e190fc3d5297eedd6af373da313a177e3f.nq.gz
│   ├── 906d9a6389b1dbdd666c65e783f1c101930071cb.nq.gz
│   ├── 955d96bbffffd97fda2a9566484dd780bb222c52.nq.gz
│   ├── 99753de58a4e0879666ccde11fb35263711d3a6a.nq.gz
│   ├── 99e2a40bf31937ea2348aa32bff045e506baf4f6.nq.gz
│   ├── 9ea2b43aa7e85fc829fbff38d134a15f18e2d3bb.nq.gz
│   ├── b5112eda64ea0ef02f00a3fa5487afc3e285ce81.nq.gz
│   ├── bc8344c49449ccfd6189a60ad9ed997b434f429c.nq.gz
│   ├── befc0b513e428678bc6be33022e940dc4b38e745.nq.gz
│   ├── c07a4c0398c4a88ba6326c1113f07624bf81f3ca.nq.gz
│   ├── c15d83a2c3a83cd551c019a9005761f971e26790.nq.gz
│   ├── c3eb257646c2f6e0309d1aae92cb36845b426080.nq.gz
│   ├── c49bdeca2c9b3ac161624925459a8ed676ffac5a.nq.gz
│   ├── c5c015ca46bd62b7888038db469d2902628bcc77.nq.gz
│   ├── c64306df29642c0bf8ca4bae673f6bb3e6bb98aa.nq.gz
│   ├── ca2db7d6257f2f2e31c7594f176811c7f27ade92.nq.gz
│   ├── ca9714f505dd412c53a4da8efaa792957e676c07.nq.gz
│   ├── cb968348e3620711006dcef9293a20b00e6edaf9.nq.gz
│   ├── cd47015957c6c97428a8ed1530b17b81e8d00b1d.nq.gz
│   ├── ce047b42af246e77708dcb7f9f1121f88525b639.nq.gz
│   ├── d1f040a232f3a959fd4e9a31be6053d4de80cb8d.nq.gz
│   ├── d45dc0e894d385155e61653e9aacf73db55ba22d.nq.gz
│   ├── daf967c936f56a86273b90727d8d896bf4ca95d6.nq.gz
│   ├── db809c05f7ab5416598aa44c0b4462455a42eeb4.nq.gz
│   ├── e112fbbe18c22a0b5ddd331b9abf976b9f2e8d0b.nq.gz
│   ├── e1c7ae93d54cbb15ece7313f02086511de2eda7c.nq.gz
│   ├── e577d8150dc8b0589fa67ae807b18b3a0e7bacf4.nq.gz
│   ├── eaade202b7ca7a19159e6511d8b22d5de58b1dc7.nq.gz
│   ├── ead21d970e91ad77618ea276a134da7f39e2bc5c.nq.gz
│   ├── ed20c5f8c3d8c13e4deb9115055284a4bb7e9800.nq.gz
│   ├── f41295fd7ee073c627d0263b0c782a6ea822da55.nq.gz
│   ├── f4dbe95dee767e3cdc2d06df999df9d0ba710400.nq.gz
│   ├── f548e15a9e76e96e999c22af68e92150eeef63d8.nq.gz
│   ├── f689c83d5dacaff5f1211c5b9141affdfac87864.nq.gz
│   ├── f838b0488205eedcefee26544541bd2d28bcf577.nq.gz
│   └── f8b9c8eb4233d9a65c1f587993435e60cd7f0469.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 900010fb1be550ec2cfa8c32038eb154f9ef56d7.nq.gz
├── filetree
│   └── 900010fb1be550ec2cfa8c32038eb154f9ef56d7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 81 files
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

[Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
