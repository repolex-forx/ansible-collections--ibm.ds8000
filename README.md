# Repolex Knowledge Graph of ansible-collections/ibm.ds8000

RDF knowledge graph data for [ansible-collections/ibm.ds8000](https://github.com/ansible-collections/ibm.ds8000), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm.ds8000
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bda9d9c35823ed5a6ba788ca94fda2d25678a78a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bda9d9c35823ed5a6ba788ca94fda2d25678a78a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 017ba3b3038c94f8b8e1834d8637833015248389.nq.gz
│   ├── 03424aed5179620793d3589b692b122d7498b114.nq.gz
│   ├── 0983ecc54d717522b50d6b4ebe259a0661023aa4.nq.gz
│   ├── 09d3bb84c88e23509cdef47bb23a977e96165dc9.nq.gz
│   ├── 0c7af8f6587c74395040ee56281a4190f50ee169.nq.gz
│   ├── 12664bf25b2d9087e9bfd33fb847a5354249e93f.nq.gz
│   ├── 14d2cfefa95e4374187ae9535dd7d3a14e0a8889.nq.gz
│   ├── 174472f43a6b1b2f67194d2f8471b52928304bad.nq.gz
│   ├── 19527303bd455aa2d2140f0ac2c467231d3ef07e.nq.gz
│   ├── 1b5f4d9eb6f12ea15d155efa5f2ecf6502e83679.nq.gz
│   ├── 1d0a8f07491fadc03fd846a820213720878c644f.nq.gz
│   ├── 2bc63d02ccf19f2cf3201f7057586d548c3b709c.nq.gz
│   ├── 2fb5c5e0fb233f07f6f76a3e4fd9c679c3e8a7a3.nq.gz
│   ├── 33df7b486eed7edbb44bb647df47a12f42a22093.nq.gz
│   ├── 351c28fa53d82af218d15991f1703ed2f36c5e8f.nq.gz
│   ├── 362166016ed8800f2b7166a6443dacd63105a6c3.nq.gz
│   ├── 4494f74e9b6089e8e9ee78e654f525df9595c72d.nq.gz
│   ├── 52ec0eb06f82148c01353cd53f14cd617fed67ba.nq.gz
│   ├── 5b23642c48999c0298ae84a3049c6a46bf6b0c9a.nq.gz
│   ├── 5b36cb4c28a36cc73de31a31f3d9c2a0f029997b.nq.gz
│   ├── 5d182ba74f4c76d4db3cbad93cd5d4c9ae4e344c.nq.gz
│   ├── 5eb42e34846d34d00ee06b9a34a80161e51ace6e.nq.gz
│   ├── 5f8114b916e15f8b1b969c7a3c481ff7899d0f75.nq.gz
│   ├── 6187aa0b2f42d05b5dc25b62d2a8f786cf7ca02b.nq.gz
│   ├── 66836fe2dcb3ef22d9e2b46844cded800f7ee06c.nq.gz
│   ├── 67e4ece966c26caff088e6eae214209f88b04d79.nq.gz
│   ├── 6ada1c95a2b79f6edc3372bd81bb1bd9763111bc.nq.gz
│   ├── 6ee96c0d8f9e5e04c61031707ab08a20c843d83b.nq.gz
│   ├── 70ab27d7d1b364a2c9ce8cc16f07fc6b58f4c0a0.nq.gz
│   ├── 71f9f6f2ad0d952dece7341456684918fdd0a2fb.nq.gz
│   ├── 7719d7dad1e5049b692ffa31281f72d0629e54fa.nq.gz
│   ├── 7b64b75641431df3075a6f3cf5bee0fd8b79ff85.nq.gz
│   ├── 7e4742475d4d8ddbf8b5299b90196344c14bb86f.nq.gz
│   ├── 832dd9df1fd1e583a4b183fbfa57f8a6028aff46.nq.gz
│   ├── 8592cc68440df8a89bcd6850dfd01e8e51fd96a7.nq.gz
│   ├── 86e1e1eb3696166622a963e0766fbc6599561804.nq.gz
│   ├── 8b25b8e5a3e16fb4cfec497d3136a9e82e0023bf.nq.gz
│   ├── 8e77af1243158540d57639c2e37ab73d43a8be9b.nq.gz
│   ├── 9791c9641bc26648db3163c60e717d6dad312ff5.nq.gz
│   ├── 9c8d09d8f26c51d20a62dc99cf9227176a86441e.nq.gz
│   ├── 9edc0eb0318d0da6d946e3ffbea256bf2e87ea76.nq.gz
│   ├── a078770f163bc7eca84f2697abf27a34e9264c18.nq.gz
│   ├── a0d5713fe27870ed9321406b3a00ed4ce8f74783.nq.gz
│   ├── a414d535a64db8c1a509c4572a78fa9b7945bb7d.nq.gz
│   ├── ac8a066d2a5947d05e0495493bddd8037318656e.nq.gz
│   ├── af278f7272dad79bb21dbc809c110bea5d6773d4.nq.gz
│   ├── b2ecea345ef1779ed7decd7fd36798ffb912d58b.nq.gz
│   ├── b5d8e49d6c0a0c0e71955a595742f71f7baa5804.nq.gz
│   ├── b93f88ac7386249b44a38c83e88827240fd75b5a.nq.gz
│   ├── ba3f03bad1e0f426c9dff15a3c5b2d5d08225963.nq.gz
│   ├── cc66d575c9ffdf36d6d2ebc49c683c7c225cda55.nq.gz
│   ├── cef0de95318beda89768134f6c2a3a3f7e347d75.nq.gz
│   ├── cf0961e9671f7074a4d810fc0f87c4ec1b2ecd14.nq.gz
│   ├── d477021d513137541ed2abe19f11acbf97fa25d3.nq.gz
│   ├── db78c72940cd3a176e8c692880bc458612a7b2b9.nq.gz
│   ├── deb3b119c15f8b042c92f3648f5caea9f3f618cd.nq.gz
│   ├── e51f7eaa56fe99a5cf440df00e30a90063745a66.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f855fbe2c7a070549ee72065d5f48d76a70fdc.nq.gz
│   ├── f00aee10c55b6adb27ab1b3d659c98c3820b01da.nq.gz
│   ├── f5de94c05bd8362ff3d775fce6cca4b7c8b06d77.nq.gz
│   ├── f7d61418a0d1fd4f92207aa6eb4b73f571315534.nq.gz
│   ├── fbaf6ae6cc7793f7986c67ba82c3c2387c98134a.nq.gz
│   └── fe4ebb2fd587a8c8d34a9dd0bbeda096e6f8cc8b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bda9d9c35823ed5a6ba788ca94fda2d25678a78a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[ansible-collections/ibm.ds8000](https://github.com/ansible-collections/ibm.ds8000)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
