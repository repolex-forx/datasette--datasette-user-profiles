# Repolex Knowledge Graph of datasette/datasette-user-profiles

RDF knowledge graph data for [datasette/datasette-user-profiles](https://github.com/datasette/datasette-user-profiles), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-user-profiles
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5e0079532e056b29b7546864ad769facefe6a4f2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5e0079532e056b29b7546864ad769facefe6a4f2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d8c58b3f811fc7a6984817a52c09d4d90efa9b.nq.gz
│   ├── 02f5a6b85cf2895efc7ccc9ed865c8ac3275da8a.nq.gz
│   ├── 03133a146e988a9460869a325e9d7bd05033c4d5.nq.gz
│   ├── 1438ed7f30c5b9fa68ee2ec7ffbfbd1a89b0648b.nq.gz
│   ├── 17a5efe95aca0b325fcab03c8d7c2bb417fc8d47.nq.gz
│   ├── 1be42729f4d2d050094bef1042a545283ee282b4.nq.gz
│   ├── 2594541733a907507886afa9c4a689f7fc48fc24.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2adf69eabe3106f68d9b32db9a2fd54acfe95664.nq.gz
│   ├── 2d9f49d5227ded5f423e3f3ad69836109074f315.nq.gz
│   ├── 30b41231d7f61ea2e84d277770b63833467732f0.nq.gz
│   ├── 34aae42b2c18f420c41135e6e57977eb3887848f.nq.gz
│   ├── 3777f070f8cbb80bf04cad200803f9993b034472.nq.gz
│   ├── 393b485db1a070dd63def35a10177ab9b56effaa.nq.gz
│   ├── 44903f7cbbfa7f5f122ed0e98d7fd89093f44bca.nq.gz
│   ├── 46458ecfb7255eb4331f67e3a4683228bc44b707.nq.gz
│   ├── 4e485e77f20af3365450cb5c45bdb9af8c5a42de.nq.gz
│   ├── 4f0887c9d402e86e86ea198f010ea400a3e77b5e.nq.gz
│   ├── 5352e723f28a8c3d6bd36f7e2555a4dfdb9cdc53.nq.gz
│   ├── 5f65587e07fc126714f36d4d4af3d354e84370a1.nq.gz
│   ├── 664a9c2269afee185534754a85f9b0ec54b8160d.nq.gz
│   ├── 683b0584e3b1df54c2abe7f74c961b6605bea42b.nq.gz
│   ├── 697799fcc6b1a545ceb5edade4734cf9f7e198f3.nq.gz
│   ├── 742e21d08fb42de18c7f6292e5a2ffb36b5fe886.nq.gz
│   ├── 7e18d1b1ca6d06c5db093e581e9c2ad9806930f9.nq.gz
│   ├── 7e510e2f741875081461be3e833c68fd0b6203a2.nq.gz
│   ├── 871ea05febdf96ba6d2f21d6f705844395de18cd.nq.gz
│   ├── 8abe4369b8151310c0f1aecab0e22b6b45fd4c5e.nq.gz
│   ├── 905dbc9ba580a3479e771754f6b2faf00c3dd415.nq.gz
│   ├── 92952ffe29f1a393769323b9eb7421fe283757fb.nq.gz
│   ├── 98471d291162d7dbd5be069f78a70bdcb9a03ac0.nq.gz
│   ├── 98ea060fe2167ce724557e6537cf3c3fecb6f4b2.nq.gz
│   ├── a1c30fe0cdf6103ea45a9446770a6e0fa555512c.nq.gz
│   ├── a58e6dda0811b4355ea31a2f17174c795f8fb338.nq.gz
│   ├── a75b2ecb1f7c3860c545884327e28b5f807d9b2b.nq.gz
│   ├── a7cd3bba4413b30684178b87b49c9a17198128d0.nq.gz
│   ├── abde0180325cabaad81799775dfebdf0d53f0c6f.nq.gz
│   ├── ae1395782917d141215b3542d53a594951d7d9b9.nq.gz
│   ├── b760e1f8ea49eb10c79af834f5874a9b6eee078a.nq.gz
│   ├── b77597724e203a558f56688c7f6fb433de2ea5a9.nq.gz
│   ├── b8e66361eee7b16f743d9f7d2642e098219e026e.nq.gz
│   ├── bd36ae75d23d158b9f9c2ee1599e3039cfbe2f07.nq.gz
│   ├── bdfcccf9bd957e86520052bfcb223b74a54ab7d5.nq.gz
│   ├── be935116ba1e636f01a94b92630231893bdeb423.nq.gz
│   ├── bf2727306e01bc16de90b98959065a51bc60caa4.nq.gz
│   ├── c51245d115381a1588fbea126c9877d6c7975fb7.nq.gz
│   ├── c6fa204593eb0e797043ba11b912fd90eab7f5ae.nq.gz
│   ├── cbbd434edf04ebc0d16397f7f9657c9a5250182b.nq.gz
│   ├── cd8eeb1e3dcc2177b4a6e9baefbf274e707c4763.nq.gz
│   ├── d01bbb60d1e5838e053535f1055f78ca4a7d9bd7.nq.gz
│   ├── d07dc3076a417584f4a942f68ad03915c59ffa9b.nq.gz
│   ├── d6fe21e45795033a696a375d792857c14639a751.nq.gz
│   ├── dd51e805d84ed891657fc892a68f38ebbfff6387.nq.gz
│   ├── e1c66f59f74cf30f97cbb5e0e7154bff4fd321a8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6aaac33f52a7449cbbb25416fa5c6a924e3c734.nq.gz
│   ├── e6f071196130dcb839b0a518632c2847c61af03e.nq.gz
│   ├── eb00d5f6bc00b518765fc82e154389c149a625e9.nq.gz
│   ├── ecda400e62fe2694714c72868ac79d2a6a483750.nq.gz
│   ├── ee0b18b04ad2df01bf4d917e00ce7d9cfb6c374f.nq.gz
│   ├── f56d87128db3972658dae850d2e099c137eb5851.nq.gz
│   ├── fccc8c07e3fa8253af90fc6216afb5b935db290f.nq.gz
│   ├── fcdcb1cf38e0b1cab577663cd3bc26604045273f.nq.gz
│   └── fce39824d279ee4406b909bc1617aa8aa06ca56c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5e0079532e056b29b7546864ad769facefe6a4f2.nq.gz
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

[datasette/datasette-user-profiles](https://github.com/datasette/datasette-user-profiles)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
