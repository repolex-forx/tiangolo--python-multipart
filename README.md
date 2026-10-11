# Repolex Knowledge Graph of tiangolo/python-multipart

RDF knowledge graph data for [tiangolo/python-multipart](https://github.com/tiangolo/python-multipart), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/python-multipart
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d3d16dae4b061c34fe9d3c9081d9800c49fc1f7a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d3d16dae4b061c34fe9d3c9081d9800c49fc1f7a
│           └── chunk-001.nq.gz
├── blob
│   ├── 016e7f7c18c014c059214b0ef09dd1ecf97cb8fd.nq.gz
│   ├── 031515beb9b8cf0c27b9cc5b7683815b335d541e.nq.gz
│   ├── 0c81daef83de66cd18eeb9c104e08427695efb76.nq.gz
│   ├── 0d7ab32e3ff7e747ec8c5e6b17a53c07d5e1bae5.nq.gz
│   ├── 10331505a3b311dad002b8325f20059c50e8b061.nq.gz
│   ├── 10fdc25d81cd5e9bec84aa492e7473cee49a1e6a.nq.gz
│   ├── 13fe6fb0a00544184afab3403707e01cd965d186.nq.gz
│   ├── 16f7b05cb9567502b1a88e9165c51258f3a441a7.nq.gz
│   ├── 17133c91464f4016a1a7f35b629aaf78fd732905.nq.gz
│   ├── 18c720f804c6f034cdb1ee02a616cc1e271a4007.nq.gz
│   ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
│   ├── 1f15a78d63ae4679200f4e8d9b03bf9993a5a85b.nq.gz
│   ├── 202d977eb4fb333958410fc84e0b5e638a112892.nq.gz
│   ├── 21452ecd53809fb87484ab4bde1619e8fdf1409f.nq.gz
│   ├── 235493e757affb4391c7c290e6ab5c4e6c93a55a.nq.gz
│   ├── 2a8e005d5188eb1cac32fbbbb69c19c5eee29192.nq.gz
│   ├── 2b4e5f6485db557f200b48aeb75bb8173199a4e7.nq.gz
│   ├── 2c6bbfb2480d273233e115abe7eecd929af5fda8.nq.gz
│   ├── 303a1bf5015ca5c7374a9bde74dee5e2b205fbe3.nq.gz
│   ├── 311105160f1f4f2519ba8265cdf87f8ceadcb80a.nq.gz
│   ├── 3179a9def8f97a24afebbf94502cc23f8077daaf.nq.gz
│   ├── 328dd6a4ddcadb365ea13160b5a051851430834b.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 3b9cefa8681b865c67b9097aae69fedbb8010020.nq.gz
│   ├── 3bf70e2ca7579d0a55033bbb272b810e146f86bc.nq.gz
│   ├── 47c8d6e0352cd9a256322c427814fc674627b9b2.nq.gz
│   ├── 4eea5b6e69e157060b51050a628a3b259f247296.nq.gz
│   ├── 4f24b23c0b48eb05e46f7238001a07881310a5ef.nq.gz
│   ├── 507ba2ce09b373d62fd62e3c6a186f2440a12f57.nq.gz
│   ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
│   ├── 5724e30a4f704821e762730280ef7f58612b7880.nq.gz
│   ├── 574ed4c24806008b8a973833e1518188cd3f496c.nq.gz
│   ├── 5a118409520813b083045416201e0feabb3043ae.nq.gz
│   ├── 5a61d836610e017e2114d37e78c7c3329f02fae8.nq.gz
│   ├── 5d59788309257daec3bbd4e3809c5df9fc52cdc5.nq.gz
│   ├── 5fc1ec07a7ae63ae6c53e6880a0a9ba9eac73ed5.nq.gz
│   ├── 63078f718638f0ed366cefe4890ca87e0afe4859.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 7346e0321c217b852ed171fb442c4234e1292eef.nq.gz
│   ├── 7373025ecf36dc127fa3670dd06e6711e261561c.nq.gz
│   ├── 7690f0860208a7376a8164e304b6b4b943f0b18f.nq.gz
│   ├── 7bdc864d1c6dc9fefe99c354ba4a938188e97607.nq.gz
│   ├── 7d97e51b45f0d0125257513833088cfa1d44506a.nq.gz
│   ├── 8439954e5813ee83d02f0f13f407166b6099142d.nq.gz
│   ├── 8720be85a639437f170836b1a2b5646d5e3d8198.nq.gz
│   ├── 897188d3eea01df0e86e8fa18e3fba6fa3ee8498.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 921637f918c15c11c1ad41c2dc6e09803d0e7542.nq.gz
│   ├── 92652e020173f59b8ab151de7865966e730178f3.nq.gz
│   ├── 9d5f62a65db8ad9d08e14f97ac6c65eb18d518cb.nq.gz
│   ├── a6efa7dde3d6ef99a0ce4d70c20b0c3e26ad7c74.nq.gz
│   ├── a9f1f9f6966bb362c7572aa773c7cd08b869d588.nq.gz
│   ├── ab4977b2c0a3658bbd982228d46fd4da0d921cce.nq.gz
│   ├── ad6bb552b85106149a944d34e35f0183298e33cf.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b49d100084b50abf746a4eb3014eaec778a852ed.nq.gz
│   ├── b5ca39bc1ea7d9c27dfb80b986a59acb14594468.nq.gz
│   ├── c045a56ad3eb7afd882feae34c49e372b26f9375.nq.gz
│   ├── c0a3b216a5a512682f6cce25837b28128ded6e76.nq.gz
│   ├── c4488099481499d8832996888259587997e198ec.nq.gz
│   ├── c9b55f246d288519da053aae3371c03953f7a71d.nq.gz
│   ├── cb2c2d6a8969deaac82eacb234ab864091533d79.nq.gz
│   ├── cfa999827c4029cd7f22a17fffd62650d4613c1e.nq.gz
│   ├── d13072e0d4f2d423ba80bb6b06c620174c3a39ea.nq.gz
│   ├── de14ae119c9993ae9552ac4b6177276250a57ee7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a5a6cd5824f311094e0342b921394f54cc08f9.nq.gz
│   ├── edf26ebef2b734e7c968d4aeeac502580c23321e.nq.gz
│   ├── edf594c13f3551daa1857e3bab033b096c8a3484.nq.gz
│   ├── ef0e9563803bf2ffc282b030f48c0a5acf20b403.nq.gz
│   ├── efb1b327cd5ece79a226e99c6477c4e5310be349.nq.gz
│   ├── f2cec11fe564efdc0bd1897602a3430ea7b88dfa.nq.gz
│   ├── f3dc8346b90aeb3b4e881cba92c7d5a176e9d50a.nq.gz
│   ├── fa92a94d860a579513561ce33dd4875366d01ccc.nq.gz
│   ├── fad74e7955ddc394d0e473da906266fe2f1f39db.nq.gz
│   ├── fc380cc6cdc7988c507a5c60e552ec4fa4360b72.nq.gz
│   ├── fe2141c565e6976b6a2a5b73f318ad7c6dc3d58b.nq.gz
│   └── ffa4eb78cc87c88bb9b82e97cacfd078a81e1c75.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d3d16dae4b061c34fe9d3c9081d9800c49fc1f7a.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 84 files
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

[tiangolo/python-multipart](https://github.com/tiangolo/python-multipart)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
