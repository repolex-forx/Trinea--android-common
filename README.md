# Repolex Knowledge Graph of Trinea/android-common

RDF knowledge graph data for [Trinea/android-common](https://github.com/Trinea/android-common), parsed by [repolex](https://repolex.ai).

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
rlex download Trinea/android-common
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56be038544ef00e02c86052ce16398dda1987a4d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 56be038544ef00e02c86052ce16398dda1987a4d
│           └── chunk-001.nq.gz
├── blob
│   ├── 04d4c2a4b0857f57b933026df1e4aba9e212ad3f.nq.gz
│   ├── 094eb541603bdff5f89eac141e3b93cb74b30b88.nq.gz
│   ├── 0bb666dcfe56f4f5a71af3cc4665282308851bb7.nq.gz
│   ├── 0fb3bc70c21a2f5b2209bb8c633e0ff6e12e9d5a.nq.gz
│   ├── 0fbf40fd0d41101367b9aa95f8de5088dff7a772.nq.gz
│   ├── 103ad3d7fa90d12ba7ed4c3f8d396b1030302527.nq.gz
│   ├── 10d1ecb0d34edbb54f985a4a606ddc1707db8b47.nq.gz
│   ├── 13d30fd7dc6e64de5e65cf7a4226065fc4c90122.nq.gz
│   ├── 1df3775939c479d0bc89fd6d89a476759ca03f75.nq.gz
│   ├── 201ebb8c566eaca33747d10461537468c12bd97d.nq.gz
│   ├── 27d243626f4ea94d6f77c906508409f1fe48832b.nq.gz
│   ├── 29c313b7fc9bcbdf79d2cf796e573dc4055cdaf6.nq.gz
│   ├── 31df044e63240aa9c641c183abb0d1a97f2990a3.nq.gz
│   ├── 3521294b1e001e4a140a3fa56fed91babaf8453b.nq.gz
│   ├── 362625aecac7251727232c2dc591a88f24486b9b.nq.gz
│   ├── 3c02e22478feee62eb733842171120650e668062.nq.gz
│   ├── 3dbdcf4ee7fc1fef954b28c51b8f5966a0f24f68.nq.gz
│   ├── 3e2a2de8366b256d5b561a9bf5d3058899909c80.nq.gz
│   ├── 4015cea4b2a68b21eb9da1c669ff54b9bc37a423.nq.gz
│   ├── 40222fd0d15524408264c74d995f535cdc22ca4b.nq.gz
│   ├── 40a8b23b8092f0626b483fcb1264b2b0ee3360de.nq.gz
│   ├── 422c45b60dcffc7ae5abd690524728bb1befcb52.nq.gz
│   ├── 468d46069127fb3d837b914d9a137dc181c79a75.nq.gz
│   ├── 48305d532e73aece7a3b7d1d297f21999375b565.nq.gz
│   ├── 49be12bd92659a82c571c604a1fa5e09c07714f5.nq.gz
│   ├── 4be6d831b5c08f48638221b20b900cd02fbb91fe.nq.gz
│   ├── 4de4bac4032e26c50441702e0d1e2cc773b5e5c8.nq.gz
│   ├── 4f1b1eb438cee3884b9397e9e2d218aabcd47f35.nq.gz
│   ├── 50e58c0ce85068c45f6402c0164e99ec7284ef9e.nq.gz
│   ├── 522ab1e50c2deae895a5f4d2b1616d12ea119ae8.nq.gz
│   ├── 534f212bfe6dcc1c720e6ed247ea5bb94370c4ce.nq.gz
│   ├── 54ba9c0fcc7d12877554964ec45adfbc27b0bb5f.nq.gz
│   ├── 55f937b1ef28c80d4b7ced605ec05f1de1e180e8.nq.gz
│   ├── 56313808b566e0f7ca39140ed96c0fb3cacce2e3.nq.gz
│   ├── 5a476a2524eb92298785c9ccf839ccc0d2b08f90.nq.gz
│   ├── 5cce74590bf4809ff69d0be05a49c3b7ae466a80.nq.gz
│   ├── 5eae988fa34106c26aab126f5332be888c4dc9de.nq.gz
│   ├── 62d0ceeafe70ec9d96be8b9fae3492f80945160f.nq.gz
│   ├── 6562db7292a864f3f8dcd57f1a35291a5de5e114.nq.gz
│   ├── 65659e6e295f303e3f957a74b22d96cbf230d143.nq.gz
│   ├── 6dd09db88f12517bb4fb01094d9976f359e5cf5a.nq.gz
│   ├── 6e7bb2fd6873344e9c1c7245cce20a5cd252a3e6.nq.gz
│   ├── 6f31a9e59606958f3577b141f644c10ed22e5cc3.nq.gz
│   ├── 7297a71d4fd81f114555c5097d162b7ee72f0d40.nq.gz
│   ├── 73f0d0925ad7bded2cc58e242570b9ee07ee32e7.nq.gz
│   ├── 771d1afee27015e5c95800f88571d36e0ab7dcb9.nq.gz
│   ├── 7d10c468176d1664dcfbeb8647a1da4acf691d88.nq.gz
│   ├── 7deb5f1e389ba6719e86991b3e9685062ab8784f.nq.gz
│   ├── 895e344dc3615bc2ac2a67a3a29b6e26f97a3bef.nq.gz
│   ├── 89f54c7758ab5504a68e431268499160a550b860.nq.gz
│   ├── 8adde5d4c3a475ee40d15a9eb0e9432c97a6a9f9.nq.gz
│   ├── 8c4a8cc7cd2bde2f5e5e8ddb3bd06c78d2df10a5.nq.gz
│   ├── 937ce90428b05fdbde62cc8aa3af3a3fb46c8d8b.nq.gz
│   ├── 94df3858dca0afe087c44213eac8effa509345ce.nq.gz
│   ├── 974cde799a6cb25f4137fa2333081beb701a048b.nq.gz
│   ├── 9d34eb84b99030bd93e6b8664c8df54691a30ab7.nq.gz
│   ├── 9d4fbf62268e1568654f2d184994b0c400320c41.nq.gz
│   ├── a0094719ba11be37fba7b900d96a6095d0a4d6e0.nq.gz
│   ├── a00b6e85a663e64da9e716b4788daa220df66176.nq.gz
│   ├── a016c86f1623eaac95884df8685d1dd845488a0a.nq.gz
│   ├── a12cbe9102eb3af8fc9a6fc3ab9d659f88cc441c.nq.gz
│   ├── a28e58dc4f0c1dbc4b794d200ba634443b882587.nq.gz
│   ├── a52f63c10918d23683c8aa8b28a8134f74b21117.nq.gz
│   ├── a7258824edcaeceaf5380ad09994e0c9f139b7b8.nq.gz
│   ├── a78cb9927e1fcce6010ac00e53701dcffd382021.nq.gz
│   ├── acdb8e7b61b25a4fc11f5c2df4e5c4a33b71ca09.nq.gz
│   ├── aea485c4ee62c681e02a099e12317adb94b292f1.nq.gz
│   ├── b19dbdf38bb7068f729c2bf6e0368bc0b124e07a.nq.gz
│   ├── b6570f772dc118bd9be815f7f3dafbde5e3343d7.nq.gz
│   ├── b73cff4c559eca5283da41f895e5139414d6c3d9.nq.gz
│   ├── b7ec54bcbff8e3087e0199e929f193e3c3930dde.nq.gz
│   ├── b966ff105f015cd37fd3d6b53f830bc001091953.nq.gz
│   ├── c0009462e123a1299d64525dc238a27a6d27d14a.nq.gz
│   ├── c078e02ae8044f9d1aece6b8f2e02fe3c1dd2fe2.nq.gz
│   ├── c5d8485bdb37cf3498c581b93eb87b1974814bf0.nq.gz
│   ├── c60b3a53d079a39a97540733d48c815992df7203.nq.gz
│   ├── d022349637608781e8792a6606a9eecc244e1d2f.nq.gz
│   ├── d084b25da9f6d2a0fc00c3c9b384d6daced0633d.nq.gz
│   ├── d22b064cd456d85a4886177bc914c1ed6b25f154.nq.gz
│   ├── d3c77fe19cd38cd0f4414c624499dc97cc25669b.nq.gz
│   ├── dbe01a9fc21b25c1248c1e45ad993a965b5430f8.nq.gz
│   ├── e17b554c1524a5eb1328626b66fa6ca21de4c652.nq.gz
│   ├── e242c5c3f73da01cbdac2da826653ea47dbbbe9f.nq.gz
│   ├── e2f80d811cad5ef95eaa83289a9937727b7d9d2b.nq.gz
│   ├── e39f47b2e5d893920636c9ec5ffdf65d0b56e7e3.nq.gz
│   ├── e4306b6e26f8629bcbaf799fe53052ad51efed87.nq.gz
│   ├── e5ebb80bc2293c061f5aa4a2b84f6c369a17a59c.nq.gz
│   ├── e8eb9d69932274fca3eb787ba2fd38a97ab14a26.nq.gz
│   ├── e9ebf8944efae06f27b7122c3d36343215f7f5f5.nq.gz
│   ├── ef9851f8eadfaa6187f3ff117009671565fe7d15.nq.gz
│   ├── f05e0ced0e5a8f98bda52e4cc763517229b3354b.nq.gz
│   ├── f2a2d7212a6df3ef7cf650a5048a03067cc84324.nq.gz
│   ├── f4054e066bb902052fdcbd25f65cfc23b62ee921.nq.gz
│   ├── f45d1389c8c8906d12bf97b860bc2f51d380182d.nq.gz
│   └── fbadcfd2a9be701e059310d5c62d7e9c2ae7d840.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 56be038544ef00e02c86052ce16398dda1987a4d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[Trinea/android-common](https://github.com/Trinea/android-common)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
