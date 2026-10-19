# Repolex Knowledge Graph of pysal/pysal

RDF knowledge graph data for [pysal/pysal](https://github.com/pysal/pysal), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/pysal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c27b6e34901e1868ed169a0e2444227e5e29f71f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c27b6e34901e1868ed169a0e2444227e5e29f71f
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ac93f9477c0133ec693f4f8c65a601e74a35f7.nq.gz
│   ├── 02ae302044a3d5acb893c8d42f9e805a9fbaf4a2.nq.gz
│   ├── 0314d6dbedf6e57ff60b2a06391cd697e6bfcdd5.nq.gz
│   ├── 07198ba5e8b072e3c3bfd1ecdd2df161d7352915.nq.gz
│   ├── 09a67fa0f946f64c4e492516000c88b985ea4303.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0b807689101c9e2c7f76126a9e6c0a82d80f5d38.nq.gz
│   ├── 0e2f580fae9dd66fda8252d609cc81c93e4243ce.nq.gz
│   ├── 0eee805c7c2ccfd0b98a7913c5858299f1addc9e.nq.gz
│   ├── 14f40b8f98e1f4f03049d54d039e0beea8968673.nq.gz
│   ├── 19368e2196bf6abfedf8b1e9db3be73e4143d233.nq.gz
│   ├── 1a28d80bd3aa4e10a6494998fc6c3f8fc5a06c33.nq.gz
│   ├── 1ea151e879019296ab096ec480bc2dd6466a4ec3.nq.gz
│   ├── 203f3c889b1613b7cedd82d99d70ee0ea7408144.nq.gz
│   ├── 2189ccbcfefd3d5f3e636e4ed15ff846bef882b6.nq.gz
│   ├── 28dbb4259310652bbe9b600692ca4ac6d11fe035.nq.gz
│   ├── 29ed2ff94a4a8f3034c537fdf32646075a31f0cc.nq.gz
│   ├── 2bb29d5117df7c3f5efec848685ac9d5c446c2f1.nq.gz
│   ├── 31fbe47644a1605d75dc4a6dbd0468f549b0f5cc.nq.gz
│   ├── 32ccf0475b42b0f1b8a67d0ed4e71165ab753c99.nq.gz
│   ├── 39206a05339c2756049d1d77512058254c488257.nq.gz
│   ├── 3a307710b8c9cd3c0cf588d773122da5da1f8dec.nq.gz
│   ├── 3e19d7c462709a57a86ffa34b622c4b9566a0504.nq.gz
│   ├── 3e28515f70af9d70525f6bcc2304e5622ecf3bda.nq.gz
│   ├── 3f474a0cea996f4b530f23bd825346512422881d.nq.gz
│   ├── 4c8345df8840baa152bdd3e14ca3826fc877e06c.nq.gz
│   ├── 4f76e0a11a927a3cf851f613a00dbc3f39c81ed9.nq.gz
│   ├── 507920c5337a5900f44cb6d0a621e748205f310b.nq.gz
│   ├── 58f1bff2c25e1b5c0a0495ae259c9735571f27b5.nq.gz
│   ├── 5a25766d7fc4b1f062800092ba98d24557640b56.nq.gz
│   ├── 5e0c183a49fcaa13346ca3ebd117791a3614d78a.nq.gz
│   ├── 5f5fb65387b9919e341d3c8503983f7cc7d2201b.nq.gz
│   ├── 6bef4f4e86c9c07643b369924a33123aa3ebb076.nq.gz
│   ├── 72e991055b4658a0b9f80d5b0192877f3436c69c.nq.gz
│   ├── 74a5cbb1783bd6bd6db68d368a1d99ceeeccb704.nq.gz
│   ├── 74bfe6fb726fda59975cd3eb23bca5dfdb600fc6.nq.gz
│   ├── 77d9cf75b0735dabbf116105aadb68f031a2371e.nq.gz
│   ├── 7b7b113ec7a3ee43dacf3d0c55280d608801bdf7.nq.gz
│   ├── 833001d677a5fee794b007f270ebd71633d67374.nq.gz
│   ├── 88a67a253806d55f5c18b7a3b7c24847215887b8.nq.gz
│   ├── 8b684ed4b852986c79f5cf246f0b54d1f8ac6203.nq.gz
│   ├── 8c6e15196663477c341f11edeef4ab70757b979d.nq.gz
│   ├── 8df47634a56ad151203a3b1f63327498f7bbdca9.nq.gz
│   ├── 8e05f3ac5b616e2c5715572cdd2f98a9651ae0cf.nq.gz
│   ├── 922ed4cb4940877425e03b96f8451dc36bfdd43c.nq.gz
│   ├── 9832bb7fb8b9e6aff7952a9998b3a6d01c083e9e.nq.gz
│   ├── 9bedbbdf10102d0958b96b628121d37c6aa13ca8.nq.gz
│   ├── 9e9b7a476ac9d1e89057395f0c7e9e3a1528cebb.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a403f2e171de6d2f83cb403a91b8e5bf13b5ac36.nq.gz
│   ├── a5384264cd0ee60934a0caaf9fde1950391f0d61.nq.gz
│   ├── b0507cff786c9a2fe12eeda5ab32c53566f2eaaa.nq.gz
│   ├── b682e98ca53f994afef20866f3a2b15d3af8000b.nq.gz
│   ├── b89a040e2d026f6f5b94c5447c124d82dd72002b.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bdf85a8542654d64a912ace84946be5b77a6db2c.nq.gz
│   ├── be5dfebf478dfe054fb82f7b2c6612c35f23a31c.nq.gz
│   ├── c1f79a62425b5914609afcae58d23573a8df9a47.nq.gz
│   ├── c2ff3a1c28321c0ba6fafef6734807029446de6f.nq.gz
│   ├── ccd76b47616dce67eb0faddf8b95a9446ea4dad6.nq.gz
│   ├── cfb865931fa74d92290c3739be19b7713e0c7cf7.nq.gz
│   ├── d0c2f46c83c5184d336a7f936666e5442cb7b3c9.nq.gz
│   ├── d2dc5b8b3da2de8b68c1748d5f97127d5d45c506.nq.gz
│   ├── d66e4ba7c7ecd7f133b700782d70e9a769dd7050.nq.gz
│   ├── d67e8726972551da6f9108e27c8a7e3745b517f4.nq.gz
│   ├── d764e8d87e4110c85d20a588c4772f7bce3e8a46.nq.gz
│   ├── d7eab29d816a643ecee72098906c3047ec6c95cb.nq.gz
│   ├── d9a036f48e03f8d94fa47fa9a29d53400d811baf.nq.gz
│   ├── dbeb58770cb7237e4c21b2f3ade6de4fffb1b621.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── ddd91c9077ae139e3ad91546597b81fb07f0cce8.nq.gz
│   ├── de9e463e9df185e6257d36c511cffcd85feaab7b.nq.gz
│   ├── e38d40c3d8fb7427aff40c4584fca914eb16d5ff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5dc99a06dbc4d13ee3e78126a199bf78d5b003.nq.gz
│   ├── ed1e3c2006bfc3f5ae98d135bfd6968bacaa1ff6.nq.gz
│   ├── ee13b6dc0b4261bdca19af9368c738e6e9757f42.nq.gz
│   ├── eea29a572eed2c197e19a988a673640947bbc9be.nq.gz
│   ├── f68f844eca0f7881ce2eba400966de8b40f9d4b3.nq.gz
│   └── fc8ea1ced641b26371a2c9dafe1cf563b680e35f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c27b6e34901e1868ed169a0e2444227e5e29f71f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[pysal/pysal](https://github.com/pysal/pysal)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
