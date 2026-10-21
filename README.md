# Repolex Knowledge Graph of vispy/vispy2-sandbox

RDF knowledge graph data for [vispy/vispy2-sandbox](https://github.com/vispy/vispy2-sandbox), parsed by [repolex](https://repolex.ai).

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
rlex download vispy/vispy2-sandbox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 670269944bcfebab31a68395c8503d36dbaab538
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 670269944bcfebab31a68395c8503d36dbaab538
│           └── chunk-001.nq.gz
├── blob
│   ├── 00576cc126055cc45c59c4f60beb3ef09895a7f4.nq.gz
│   ├── 09e206762992ea2cfd2d2c9efa19821ee270b075.nq.gz
│   ├── 0a46fdd6f128f84e472e44f169848eb9ac685050.nq.gz
│   ├── 0a483752515594ecb53a2fd1ae9359788272e52c.nq.gz
│   ├── 0c34bbc36d3c55b969884137efb843397d24f9f4.nq.gz
│   ├── 1112ae0666ca6197c96ed308a0084f55ed3dd2de.nq.gz
│   ├── 1931a8394ac989138eefb98b5101ab63d0d08e2e.nq.gz
│   ├── 1a9456ed567fd003607a041cb638d7c05008dda9.nq.gz
│   ├── 1b5802fa809d7c757c247219b6bdfe71b065eca2.nq.gz
│   ├── 20c9bb31bd8f9d8c85a90334ad8f76aef746a97e.nq.gz
│   ├── 269f172a830fa2c6f0db5929c3212e30ac4aad30.nq.gz
│   ├── 276456bea51bbb21daaea8072390cb6e440b8006.nq.gz
│   ├── 2c2d622482f402d5f901524873bfe2f6219172cf.nq.gz
│   ├── 2d97eaf58fb6e1f3b74e57caaf67740076bb3af3.nq.gz
│   ├── 33c0094135a1b595494d50479b7430b3e5b8684f.nq.gz
│   ├── 3d4b8a8e328e68836793f9979986cacaa1ced861.nq.gz
│   ├── 45e820c93e39d9c5944a55c6e5102b52451d6251.nq.gz
│   ├── 4a3e39a01f460e0cf2d950a94d71d447f1fba049.nq.gz
│   ├── 4d5923418c575e02f4a55f3823c2d31669f50bae.nq.gz
│   ├── 5584ab0d9386b59e2db24b6b7133ab3545af0c88.nq.gz
│   ├── 5c1cab9e05259af64a9ece73af9df49e9dabdefb.nq.gz
│   ├── 63f33d2732152f28a5ce7ecfd64bf07c4965418b.nq.gz
│   ├── 66742087bbd53135c56bf4ca754544c19deff0cc.nq.gz
│   ├── 6d1d14e56f901267989a6974452e4ee2b1bd7eec.nq.gz
│   ├── 722c16e7fe657ebca0f3a13082875b99f2e1083d.nq.gz
│   ├── 754f76fc906d61734c852302f5f68c1719b23ad7.nq.gz
│   ├── 7cb9728676dafe0443454578022f73e1568fc2cc.nq.gz
│   ├── 8182c2498b42912aafa024dd66c53016d1c41736.nq.gz
│   ├── 84e486170927479d5bac30ab3b5873e1a856ab6b.nq.gz
│   ├── 85ab04521147f0c9e8394ce46fda04b9504f9589.nq.gz
│   ├── 914ab30a9eb62c1ca790dde85ba858230c1f6f33.nq.gz
│   ├── 944351811366fcedcce741d11e1ffa57c7632aab.nq.gz
│   ├── 9754aca7b39f913a9ef4e4351c9a06bab6bf74f0.nq.gz
│   ├── a7a9de0da991d8e6a1b4432bceba45822fca97ef.nq.gz
│   ├── acfe9f652ec8ae0ee9c0d9241598949d8515f9d9.nq.gz
│   ├── ae281605070e8a8b4078782161ab3d5d7831a505.nq.gz
│   ├── b90ed43c776f9c405a08e1e04078094d5a6bdf26.nq.gz
│   ├── bebb2642db0c507810b5a5105c97e3a94ae4302f.nq.gz
│   ├── c013e39e69ffa321d54af210e0ad92ce00bcd922.nq.gz
│   ├── c1ed50a2365df6c6b7c27a30e1a3bd31a4fd9b57.nq.gz
│   ├── c6ed395f2b8a98bfcaeb1fd7ed3f22988f9338a1.nq.gz
│   ├── c891fe4ac31a20ebd6fff67368988a0ff7354e05.nq.gz
│   ├── da7d1dc49ba27edde2a73641a5125acb0d17a282.nq.gz
│   ├── e85353761eb9d888beee20bcf50c9116daf359b0.nq.gz
│   ├── e9cab8ee1dc423d687d06a841333584cb32e9436.nq.gz
│   ├── ea8856bf570a76dd3ea251dac6f3917be2ca9a45.nq.gz
│   ├── ed6a868892ef46ece5e1f95fe341815b77e85cd3.nq.gz
│   ├── f35e443d3f4e5f8c4baaa44c853dc835192e3690.nq.gz
│   ├── f85b4ce8ef291ed763d578db2c958721f257c4d5.nq.gz
│   └── ff34d9d518d9f0ad7b4841814971983c7de7807f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 670269944bcfebab31a68395c8503d36dbaab538.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[vispy/vispy2-sandbox](https://github.com/vispy/vispy2-sandbox)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
