# Repolex Knowledge Graph of rust-random/rngs

RDF knowledge graph data for [rust-random/rngs](https://github.com/rust-random/rngs), parsed by [repolex](https://repolex.ai).

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
rlex download rust-random/rngs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e8065a49fd64c55c0a5876fd1546a95f0eaaad5d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e8065a49fd64c55c0a5876fd1546a95f0eaaad5d.nq.gz
│   └── repolex
│       └── e8065a49fd64c55c0a5876fd1546a95f0eaaad5d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00791876aa0d923704da299b2b922d51e7412603.nq.gz
│   ├── 022d0a38c0b1e4e5e7fdfc89c5c491ff42c01d8c.nq.gz
│   ├── 0560a073189a9f55211257fae41ec514894d049f.nq.gz
│   ├── 07dadb909486e4b5d4755119ede0e67090cc535e.nq.gz
│   ├── 11b2b41fa3b0be27a3007c0832a99ef883e542ee.nq.gz
│   ├── 17fca8ccc1a7cbd16b68babc998a877e632716e5.nq.gz
│   ├── 188d31b832fdc890d46dbb3bf899a32597830769.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1e864104d271fa2ab361b0962c1664827fc73c7c.nq.gz
│   ├── 22b1e8da2f557a60db8399dcab560a9ffb4f599e.nq.gz
│   ├── 2f00d608baa5e83b59d877aa31805e26c9302536.nq.gz
│   ├── 30972f501d783e0ccfe86d8616ab2638a08ec071.nq.gz
│   ├── 372e6628c8ea58c0d901e2341d3225998f2f1589.nq.gz
│   ├── 3e0dd6b4f5b828d61a7d0d692b3fa31e69182311.nq.gz
│   ├── 3ecf208ece84a94bcb21b6530d0d99ca085c743c.nq.gz
│   ├── 42e19756216f26cc5043de22b0df99db7a6776a8.nq.gz
│   ├── 42e2023e94084e0a58bcd0cfe1d1d19594838da4.nq.gz
│   ├── 432739d0dda5c51063b946f5d05c3a3779111fe1.nq.gz
│   ├── 468d907caf99fb0cc0dcbb3c322cbb69f740ffd1.nq.gz
│   ├── 474305267c439707a92be7693af28ce4e05603d2.nq.gz
│   ├── 494ad3bfdfe44d1a2a1e20553308ba59574fb969.nq.gz
│   ├── 49cf64ed2aca3576dedee5db29121a2167c71ec6.nq.gz
│   ├── 4b627ecc78b50d45e77e2d34e75a2d798c78fd70.nq.gz
│   ├── 4f01b676a405731f01b44eace4e32714cbd92c55.nq.gz
│   ├── 535cc32c4b378bbc38c56c6827560a1115d5c853.nq.gz
│   ├── 5b0e96e71f7dc989b3f50c8cc4a6a5344e54e09a.nq.gz
│   ├── 5bd276f784f68d42f0821da50eaa3e8bbc3e0e49.nq.gz
│   ├── 64f40ab2960c19f75affd34e294761ce596f5ce3.nq.gz
│   ├── 650505abce900e21b3e5d63da8097f0fe0adb9a5.nq.gz
│   ├── 67b38b345c305b39e08174072972a1e88dab8871.nq.gz
│   ├── 6a755682c6718e9d393bdd21f83f30b341d1863e.nq.gz
│   ├── 6b3ddad98e2fe86576e91d8812e4e0aa4b950a0f.nq.gz
│   ├── 6c6b2c249d30035444166b0fee3353dd464a4df7.nq.gz
│   ├── 76d7c15b6d87a7b55df9af6e8503596173e54644.nq.gz
│   ├── 78690a3add027942243c3774b33a3b1b6097e755.nq.gz
│   ├── 793bee750b8f7227559d585487eca8aac07f01cb.nq.gz
│   ├── 827150b65adcc2ed6b8235b36cbeabb626288655.nq.gz
│   ├── 82bcefc5f98461ce53f5337dc824e072903f2bcd.nq.gz
│   ├── 8413a26b6ee4baf049aaea02ba2d7868bc9ec80c.nq.gz
│   ├── 8970e6b202b95681179f7cc8ea0444837abc9aaa.nq.gz
│   ├── 902cac69572bc807fd658a4e53a0e2fc19459725.nq.gz
│   ├── 95389442341802bfe9d96766410d346ddd386781.nq.gz
│   ├── 9c497171a37c6f2181a0fb9037eee55c9572333a.nq.gz
│   ├── a5e040c076988b8ebc8c209749a88ed0b3a19b55.nq.gz
│   ├── afa5a1600db3d41cc311631fa03bc353337e4203.nq.gz
│   ├── b4745048e25489926e882b9b71caeaaf0b9438bc.nq.gz
│   ├── b6c53883ba844770b8e768e2cef61e3935e4ecfb.nq.gz
│   ├── bc11dc4d6be609a9a527359cb03253f15894746b.nq.gz
│   ├── bcd21f15421affb0c2fbb40adaa0bfce80e24962.nq.gz
│   ├── bd3ecfc50c1ab94a02c1473f55ae7b535cf81649.nq.gz
│   ├── bfce708dd5b31da1e9d1b93fe43a0a5124365a3b.nq.gz
│   ├── c1f4b15b2a1a1d8f4cf0395271a88cdd4acf22f1.nq.gz
│   ├── c45321ff9cceb2c026016e96e26c5f4b050fb193.nq.gz
│   ├── c4fbefad172fb5e28a1ddc5143093a75f4673707.nq.gz
│   ├── cc286839c1d9c9ba4935739d66408e2e3f510a34.nq.gz
│   ├── cc9bbe4d5767dc656bf8504381c19f5a234a0702.nq.gz
│   ├── cf30165dd31d00eeda99212b1a6a632ad0886ea5.nq.gz
│   ├── cf656074cbf6271db6b819562629ac28bc7023c6.nq.gz
│   ├── d10934d8557dfbb0acbac6fa856a9a8587de1af4.nq.gz
│   ├── d2abf297cd78d18a386c278488c7ca1e1bef80ec.nq.gz
│   ├── d93b5baf341d9813bb48a51f42a7e8e4af89ec52.nq.gz
│   ├── dfb927e538643cb8f11515186c7e95a3420a3649.nq.gz
│   ├── e1da7388950b3dc47d6c4cc6a9666b0d2b9b7d8b.nq.gz
│   ├── ed1aee6c684bc148db1ca68e35060513a0cc8fea.nq.gz
│   ├── ee2d658ad22ea53d7900dcd6534d6fc78c0fda4c.nq.gz
│   ├── f6e86d8675055624083272fd914637d2957c3d6a.nq.gz
│   ├── f722e4c191259d8a928c17a8bac8f9b9caabd59b.nq.gz
│   └── fe6ba269603fef08a2d1a565da72bacfca12343a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e8065a49fd64c55c0a5876fd1546a95f0eaaad5d.nq.gz
├── filetree
│   └── e8065a49fd64c55c0a5876fd1546a95f0eaaad5d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 78 files
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

[rust-random/rngs](https://github.com/rust-random/rngs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
