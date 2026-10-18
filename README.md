# Repolex Knowledge Graph of scverse/mudata

RDF knowledge graph data for [scverse/mudata](https://github.com/scverse/mudata), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/mudata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6038e1ae0bdf3b6d5b747b2a6145ee1d6cb4a39a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6038e1ae0bdf3b6d5b747b2a6145ee1d6cb4a39a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 00cae913dded8a533f82145c3cf224456e4661b1.nq.gz
│   ├── 033f61d082ee501ce8c561faaa3505b65a3dcbfe.nq.gz
│   ├── 067610eafc86d98d6c4cc502c9015203e2dd44b0.nq.gz
│   ├── 08e9658901225ac7adad2b41e87572ce312021e3.nq.gz
│   ├── 0fbffefe3ab9d6fda9b0584a38e74c7ce0c0c279.nq.gz
│   ├── 145bf2d689439c97cc8cbdd31907f20dd456a83a.nq.gz
│   ├── 149b6b6740b24594d325636f168ece083b8b69de.nq.gz
│   ├── 21fd997118c507f3dfc81bd4173e3ad59ff14259.nq.gz
│   ├── 23992e36b8aeafbcb7e06359b0922b1bc4df20e3.nq.gz
│   ├── 24f8b5fe3df6e91ea591da05da658745a8021d26.nq.gz
│   ├── 277ec24e14538691adbb14c39c54645331e12419.nq.gz
│   ├── 2790886077f108fae35bd4a1b71090f228b7bad7.nq.gz
│   ├── 2e300cefc818cea1788f8b4c804bcbd8bfc72738.nq.gz
│   ├── 2f1b060a6157ca81179d2a818cc09db25e944a60.nq.gz
│   ├── 2fbc9c4c4bb8154b5fc90687f50c53376d0d639a.nq.gz
│   ├── 32de32705a1d7741043656a36a7a58bfa20577e9.nq.gz
│   ├── 34b2cbf58d69eb95882792057e7f2b8de63716eb.nq.gz
│   ├── 34ea17315eaca42b608145f00e3e2956316d94b7.nq.gz
│   ├── 3512f32a1a5dc3e0bf137c01e0239e5096c36db1.nq.gz
│   ├── 3b07f7ffc460faa7459f5539472529da17439fbb.nq.gz
│   ├── 4156737e9460498b52a0cce8e9f90a8b15cd2efd.nq.gz
│   ├── 41b89d5b06df33e5e3b9cbb367ad1cb9d474aaa3.nq.gz
│   ├── 4496f73f3a68a6b6e0467fc3a0081ddd6de84bde.nq.gz
│   ├── 4617e1479a68a13dbb4508571927db57740c9cbb.nq.gz
│   ├── 4b11653b015f855833ac12babe6d1644ecc0f12a.nq.gz
│   ├── 4b4d90ad4da7e04e88fae0b52f01c68845a07fa7.nq.gz
│   ├── 4ec426561ffb89af1d228d92069bddb00c4adea4.nq.gz
│   ├── 4ff1af5e66f96074789e8bc82ddfdc993c79ed06.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 607adcfbf112d14782297322bdf3d881868d0dab.nq.gz
│   ├── 6104b9e6f4ae97e25a2fd85f24bc2370b23bab6a.nq.gz
│   ├── 630dfa2eb4eb95b8d05b37926e49eb15a67ea437.nq.gz
│   ├── 63711cf5cb51428e2fc412a3e1ec10fa4fc9c988.nq.gz
│   ├── 63babb1acfd31134fd6c2674a982f0efb2c47789.nq.gz
│   ├── 64c380aef27f002d44d8c812819d552018634892.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 66d3c61c2eb53b6cc36e44a3be708ebca4e517c1.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 68d2c710fbfb4f8f881ea36e29228309db361727.nq.gz
│   ├── 6c9c25e5fe4ea90ba569a7ebfc6ba3968388f381.nq.gz
│   ├── 6f1b3d8dc1639f835ec340ae165b263b5a1f3534.nq.gz
│   ├── 737ef66829fbb2cf407dc2136931450cfe643009.nq.gz
│   ├── 77c8cd17679549c756617cc21b6e2fbe4ff06291.nq.gz
│   ├── 7a51c2906a7d76a11a55ef43d83fb40769eefc4a.nq.gz
│   ├── 7d413de8e1d9ac14e784ef33f1d4e9fd73ac4425.nq.gz
│   ├── 7ffc46c9ac93e455492273a8a56ba0a0cce7e792.nq.gz
│   ├── 8158215c870173df8c02bb2a7ab292ee14d1a23c.nq.gz
│   ├── 828af1b2c40c99eaaaaeb560a6eae228485b08f0.nq.gz
│   ├── 854d0eb9d38c1f685378fd5801caa695332ded8f.nq.gz
│   ├── 85718915e00e20932926ca409b8de05f2dc986d3.nq.gz
│   ├── 8816943715c9ba9c4f1335a40dfda72990491564.nq.gz
│   ├── 8abf67cbb21e53635ae8deff84a456c7843c8b8b.nq.gz
│   ├── 8bd3b87552165a1d3a6d61baf6f36e07cfc640d4.nq.gz
│   ├── 914ad69d5046bebb8743ad4f7a9f003284d56925.nq.gz
│   ├── 9327220e38754d5498ba0da58d64376ca89612e0.nq.gz
│   ├── 94383f98373a7a813e078ab3611a021d67637b14.nq.gz
│   ├── 9dbee9b5a3cfad0ccd5d36feba9201f329559b46.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a34432f2c0f2e02101117625b276147ea20c6936.nq.gz
│   ├── a4513927bb8458d51f4eb07175a7a11c52756ef6.nq.gz
│   ├── a70eff5722af1376b88057b5b0ce664dec062bbc.nq.gz
│   ├── b178710f2de1d688a4de13a5f2fd208a1c3c3855.nq.gz
│   ├── b7d92498ab98271a7ec9c0dbbebf50a34c47c8dd.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── c0db62c8bc4cc61f933fa12152982cea34945376.nq.gz
│   ├── c3fe17c0054914da90836e51c85cd843904daeb0.nq.gz
│   ├── c4e1c69a0180585d2e4b092b9125cd3d3d462da5.nq.gz
│   ├── c64a8ac49de552fab8852adb896289081b5f79c5.nq.gz
│   ├── c6d0db27802e297705b956fff073dfe8ff58dff0.nq.gz
│   ├── cb1d5beb4093d391f6fe066f27e6ea34d9340a68.nq.gz
│   ├── cb4785b799a211a5a022f7170d31a3e518c8de74.nq.gz
│   ├── d0a3137b0f39edc2167fa7540bc72ea92668020f.nq.gz
│   ├── d1ae690cc4eebc25153a9c2036b663e040fcf662.nq.gz
│   ├── d1c8c43d460b84fbd727601830b3e658aa8007e0.nq.gz
│   ├── d4139c2a0c78caa3e1a8dc06b80ddb9555fa8360.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d61e71b1004eafd8b7a02c9fc1d80bc892adde30.nq.gz
│   ├── d62fbf7a7da1b6e928cfc5c232d4b90e92f9aa55.nq.gz
│   ├── d94f43dc6b5b02f2972f0df35679c77d30cd1876.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── de008d349ff08644b97cbe526087517c4f66e323.nq.gz
│   ├── ded07a07fc47fb0389ba3b7b6091f20ba49a79fe.nq.gz
│   ├── e20cc580ee87fea44e902c47893f4a2aecbed17c.nq.gz
│   ├── e2685a6cb66fff033f465c704945d5708374b6ef.nq.gz
│   ├── e4b4b338e6274af00682f15b97aa65d76728b6ef.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c148b6236bcfcddac1828e0839a9d72ead1239.nq.gz
│   ├── ea4bb3f4ba43cb074745e70ec23dc8fd05a89fcd.nq.gz
│   ├── eb4a07c8025fa0eb4b5f4eff34d5dd443da643ad.nq.gz
│   ├── edca23720a07ab86f91f650ef3234605a5862eb9.nq.gz
│   ├── f05dc517f1adc09294baa034551f38ca03a2c4a1.nq.gz
│   ├── f3d45c28d3c24b3789a58429e0ad4a295bbc7d03.nq.gz
│   ├── f41a2b5c7ee0ed01819901f38b7e6ba06e50c7e1.nq.gz
│   ├── f601df0a3f994a815bda0752f94b5368ed03e522.nq.gz
│   └── f6371452dd654c50be70ca868722950f1672d376.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6038e1ae0bdf3b6d5b747b2a6145ee1d6cb4a39a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[scverse/mudata](https://github.com/scverse/mudata)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
