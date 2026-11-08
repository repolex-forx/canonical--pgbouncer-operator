# Repolex Knowledge Graph of canonical/pgbouncer-operator

RDF knowledge graph data for [canonical/pgbouncer-operator](https://github.com/canonical/pgbouncer-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/pgbouncer-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68d3844248a8c9e838e44edefdd8b45a0b4c42f4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68d3844248a8c9e838e44edefdd8b45a0b4c42f4
│           └── chunk-001.nq.gz
├── blob
│   ├── 002e6c58e755ba372fc8240384375c7425903eb9.nq.gz
│   ├── 0591f6fe1ac21c5020736347a99354427ba8e065.nq.gz
│   ├── 05dc4e23efc7f0fcf066096fb55bf1326742330d.nq.gz
│   ├── 06046d8530bc1fcb288a5e5bb1b6ccb1e1eecbd6.nq.gz
│   ├── 063c5506ee7fdb9380e5979f878884cab4179e0f.nq.gz
│   ├── 087f6f3c58d5885b5ea92e0efbde8524c04b57a0.nq.gz
│   ├── 0a1d95ee6c7b2eefff510085094ce1c94ac603af.nq.gz
│   ├── 0a4a9791d65953d2b90831e5f86a76216ec61268.nq.gz
│   ├── 0ab358137a8dddb59c81755ace58a2126b12d76e.nq.gz
│   ├── 15e65fa2691cf2eae9f86f8e2c40a32fae21dcce.nq.gz
│   ├── 1b1532f56e612b03646b669eb40a417cb8736b3f.nq.gz
│   ├── 1c6ba878d3e58c6bef5aff5f01791c23adf6106e.nq.gz
│   ├── 1fe326a8170b775122b1747fae7fef143cd4a676.nq.gz
│   ├── 2248632c3260857633a66e17c0c5a4015ed8f5f7.nq.gz
│   ├── 274cd0ebad9fc821ca95daf0334a7081bdb6dcd1.nq.gz
│   ├── 291cb925def343b66309b597c5588c2f335fd5e9.nq.gz
│   ├── 29d78b95b551f789a1f3d3c5a1c7adb40b7a86f9.nq.gz
│   ├── 2a28864f531a918824c6c885679527bef3a44ec5.nq.gz
│   ├── 2d7978a1e455d6da15d1d744ee504821fef5535f.nq.gz
│   ├── 300a08a268a8fc9a94c8dc5cb582bdd5d4eb352d.nq.gz
│   ├── 31fbd0af12e8f61941cd8f127bc599a106fe8ad2.nq.gz
│   ├── 324c0b5b8a08f3b62fed704f544aa010ad47b711.nq.gz
│   ├── 328d5c0def8720dad74d38474f3d81df5fdbfede.nq.gz
│   ├── 34a2b8969aaf6e6b5e890363cd83eb50801b6d0e.nq.gz
│   ├── 351c150524b675b57cbdb797f92b01675d5dcae8.nq.gz
│   ├── 354f67a543b360dfaa12fdf2942d69a0b70f53c2.nq.gz
│   ├── 3702ade44093796bb3ff1578dbe066583f76a293.nq.gz
│   ├── 385e9fd4131c11c3ce8d39caba452b08d0287d0d.nq.gz
│   ├── 41c1d3f4f3a83543ba1ec26da8135e1162d5451b.nq.gz
│   ├── 435c79ba5ec1be337868b366e625a4883c3b53e6.nq.gz
│   ├── 45b7bb64735c1dffc734b51110e2949e08e7a16e.nq.gz
│   ├── 49948b9c478e6d944a6217f47dd7f51daeac42bc.nq.gz
│   ├── 4b76827403b0d7bd5a59c3bb17a3b556465c22a4.nq.gz
│   ├── 515ccdc72aedf94077768c615246db7826348dde.nq.gz
│   ├── 542cb170a3b0e35c00743a97cc5c35be8b88058a.nq.gz
│   ├── 54c6d8b3e48d1a072c60b7ede8c8d7f6cdb33e74.nq.gz
│   ├── 5676ae9de83a607c52eea842d1c6d10600f2662a.nq.gz
│   ├── 59d4c6bceb8faf7db2e41bf24ea9aa746cf84315.nq.gz
│   ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
│   ├── 5c6b3f535addacb9545f96dc29f10ffe20d875af.nq.gz
│   ├── 5d051e9b5cee08646e9ede20a58e3d6e14e1c73a.nq.gz
│   ├── 5d86395d1d692443f67a177a0cd68719e08f8e07.nq.gz
│   ├── 5de64a8251efe695eb96041532d2e49837cca286.nq.gz
│   ├── 5dedccf918bd55f98880e14d94be56306cac8aa9.nq.gz
│   ├── 5ea366548e8fd6aaa50163faf7b6cfd01e914244.nq.gz
│   ├── 5ed7bc1bece95d3f4df6f5acf703e2dcc77ce111.nq.gz
│   ├── 5fa67e3a635f0e9724f31a3b4a48c02eb7196c2d.nq.gz
│   ├── 61cc10410ef5be90b6740dc5e6ba6e010288e712.nq.gz
│   ├── 649f373e2d939038951ccf1d3b9fa276a9f05aaf.nq.gz
│   ├── 667d8b8604e41fea8a32e3dfb3ebbf95a4a2d657.nq.gz
│   ├── 68870a2db64d54f400baf3929e6c3e87875f37c9.nq.gz
│   ├── 6a4862729b6bc45ccf0b3f5097daca4f072dbc33.nq.gz
│   ├── 6abdbce4a4d11e0252f3d22e33a2d2052bc850c7.nq.gz
│   ├── 6b76cc46ca66ae228f0463d254223c2912b75a30.nq.gz
│   ├── 6cc9b302dfb64012ed91704e2900ce2b4ba69773.nq.gz
│   ├── 6e24579a6f52d45a9f59abf6434126e68a457b29.nq.gz
│   ├── 6e9ddd7e14fb6e0537020eb7fcf924f9a992eafc.nq.gz
│   ├── 71e44ce0a02fdd11386a8b77c8f1980ba09d2fbb.nq.gz
│   ├── 7374a93b6145189257d96e1f24c00b00c427e55b.nq.gz
│   ├── 75c59827c9ba2a967001f7f45b9e7a7dcb8dc92a.nq.gz
│   ├── 78313751659e28d359f7b1274a8daea733175546.nq.gz
│   ├── 7ab2aa450c951478fb0e406dad324683845e5c76.nq.gz
│   ├── 7ade63ae37373626f63a96575d8ad5bb83836215.nq.gz
│   ├── 7cb06a0e3c273251ab9c3c748cb35d47159d112a.nq.gz
│   ├── 7d13cbb2a74b78287466ff1681928b1a811089ec.nq.gz
│   ├── 7eace628c58cbead0fab774cc48053796f701712.nq.gz
│   ├── 8023d85ddd50aaf00010d9f891a3a38180eed323.nq.gz
│   ├── 8412f01f054d6f6db2a0981ce70763629c572996.nq.gz
│   ├── 84a0ed68da16d79b8fa323024643073874a230e2.nq.gz
│   ├── 853bf22de6816234707c2380215e8e2770c1e543.nq.gz
│   ├── 89387aabe2424d06878712addc9b30118ac90425.nq.gz
│   ├── 8b591655e242b682d861bf2dba197a4f3cdba8ac.nq.gz
│   ├── 8d396840d96225e4e27b149e9ad88da7f73eeb73.nq.gz
│   ├── 8faf6c8811583eb9458f1286147dc75b6d04326c.nq.gz
│   ├── 8fe80688a444c5181ab2c77753733ad24fb6c982.nq.gz
│   ├── 9139674bd39529ece55eaf008812da623fac4b77.nq.gz
│   ├── 92219d71c83a39ce54b28b41c505260ffbdf0ebc.nq.gz
│   ├── 925f4d79c68ddb7a7232ca81fdb0e532071ef4c3.nq.gz
│   ├── 95eda8f468c837d6b73f798d08ecbed08254c3f6.nq.gz
│   ├── 96450bdc32382abbcf9ade4798ce335b494b9dc6.nq.gz
│   ├── 96dc7c2c6ec47b3d3fac7373e734dafb28fc0954.nq.gz
│   ├── 97367647b93db16ac3675f1e7658963971b21402.nq.gz
│   ├── 99a5284c58230f2b54f1b6c6544e2bfae6003e61.nq.gz
│   ├── 9d8fcac4b556e0ea035b30246c737d7f1372f715.nq.gz
│   ├── 9ef36aca6d2980f250f98016204ad1e4b0f11d84.nq.gz
│   ├── a015624a2b3cd1aeb7f9851300cd6cb471f0d187.nq.gz
│   ├── a0b17fd9edf6e00c1ea3f7f9f9e87847b19b5e6e.nq.gz
│   ├── a2153727eb353674e5bef302906bc59bcc2e348d.nq.gz
│   ├── a2d250e4fc0751a0dfa4ef81594a6ea91f90e6c8.nq.gz
│   ├── a313585d4696fd067d5156208e5a95535062721d.nq.gz
│   ├── a6fcdf8cf3afe3b744e7d69860fbd191c27f0a70.nq.gz
│   ├── aac3d0fb02f25e0eaa30a79714a272384bf6b32b.nq.gz
│   ├── ab720c0edba7be0f61134f99e316c9840c9670b6.nq.gz
│   ├── ae10b530f1670b0e1b82b44b2051474022f2168c.nq.gz
│   ├── ae229c5bba0cbd02e5c78ee3682863fa55e80205.nq.gz
│   ├── ae2841bf464ce63f1d5c0c0866fb60ec74a11b33.nq.gz
│   ├── aed7885edb5dafda3cd9e6618d5b689b101d9c43.nq.gz
│   ├── b095897164879ddea0deebc57ee8444bd97990b7.nq.gz
│   ├── b0fbb34478f1fbab8cd4e79f0f42987afbf911aa.nq.gz
│   ├── b261442339617bb213e5c23e2c405c52df3b5929.nq.gz
│   ├── b2894d9d8986487e264f724f8710b0e11c498fab.nq.gz
│   ├── b48fd599fe9f68fe9b5dae3a8e88f5177fae2284.nq.gz
│   ├── b63455b6d4d1ecd2eed7616e59eee94d19426f7e.nq.gz
│   ├── ba2abe09172123e2e979569f3696c6e0ef6e4dfa.nq.gz
│   ├── bab2d1bdc46d420e1cd021aa41b46e1dbb4a1833.nq.gz
│   ├── c197c4d9232e19413aaaf5218223dbe52e0c94b0.nq.gz
│   ├── c2536588faac1b2563b21e543b3d41fdc24fa94e.nq.gz
│   ├── c82d55a939526f6db2754b7d2bca0cb6dbfa04ad.nq.gz
│   ├── c85c323d923a72a32776e01d9a87389bc0756e69.nq.gz
│   ├── c8e00b757b3636b10c44cf55acd088ac5be7ccb1.nq.gz
│   ├── cb0e336bd8f7983157ef784360fd24bcb5c0f5cd.nq.gz
│   ├── cbf0d72c97a1f083a895a59cb3e3a17d30e38ae8.nq.gz
│   ├── cd69cbea25e1e48a0872e8a4581629ef2df3d5f7.nq.gz
│   ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
│   ├── d350e6036c535aee8d8310c13df45e58413ef51b.nq.gz
│   ├── d3944207ccdaae42beb931dcc2c290b202325856.nq.gz
│   ├── d5f6daf0215ed84ae2570162c45977db89f32eab.nq.gz
│   ├── d60b1973c84a08e784c042afab39e8d50e7ce710.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6baee6f51b0400125ca93fb526f9b5c8cbf0eb2.nq.gz
│   ├── dcda150f26375a0c84aa574a16b88839f627e9b7.nq.gz
│   ├── e2ebf6259afc6dcffd5892bbb44a06dac17b70f4.nq.gz
│   ├── e58d556c7108c624cd05fd15cace04a5623df1fe.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8986b4d3b25c43c3beca3df0c911ddcff673657.nq.gz
│   ├── ea9e6f5820ed32edc7a296832fbcb736a6e43104.nq.gz
│   ├── eecfbf7eabc29d5d8c73af465f77d2be27efde61.nq.gz
│   ├── f0d2c1924945a4dc3da46d1fce55dc3a9ad85ad6.nq.gz
│   ├── f21f0fe1efdd24cb5b226d67a3bd3b95c9b8def0.nq.gz
│   ├── f330f89b38fc50328df7cb8547409644f212eb72.nq.gz
│   ├── f3341c51511fd30ff4065ce3232787d2b9c9250a.nq.gz
│   ├── f3cb1ad08b7382d695608c815fda204785d6d21c.nq.gz
│   ├── f3ed01a4e6eceda6d758b49f590bc251a83640ff.nq.gz
│   ├── f9b99841799451e12cac38a43c8f5d4c9b36f38a.nq.gz
│   ├── fba5f85b0f44a1e2356ceb3b5d927f214f55814e.nq.gz
│   ├── fde16d68eb0be32a8ab39bf9387542ea6d61fe7c.nq.gz
│   └── fed39c304178848701e3961c8843d3d7b0a30c5f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 68d3844248a8c9e838e44edefdd8b45a0b4c42f4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 145 files
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

[canonical/pgbouncer-operator](https://github.com/canonical/pgbouncer-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
