# Repolex Knowledge Graph of psycopg/psycopg

RDF knowledge graph data for [psycopg/psycopg](https://github.com/psycopg/psycopg), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download psycopg/psycopg
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13824881c5dd715b73f5873c1a773b35d5f2b8e5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 13824881c5dd715b73f5873c1a773b35d5f2b8e5.nq.gz
│   └── repolex
│       └── 13824881c5dd715b73f5873c1a773b35d5f2b8e5
│           └── chunk-001.nq.gz
└── blob
    ├── 00cd54abef810d714becdcbc5e1e9c93d0d01b83.nq.gz
    ├── 02f8fdf3b487e0b075a663cfb61334a53c3b6063.nq.gz
    ├── 031173039ec70b52803684275246ba71710c8cc8.nq.gz
    ├── 03a2c703bdf70c2cc31b8c12c58482211c17225e.nq.gz
    ├── 0537eb82db5746e5d6bbeff0af9033fdf47f2cd5.nq.gz
    ├── 0542465046723c82c9c6936fc363ef39b612ece8.nq.gz
    ├── 0739a27c8e8cbc3fdcef8f65ab36c6bde280a2e5.nq.gz
    ├── 082dca25d0f06e8ed32c46f22f8b883912622fb1.nq.gz
    ├── 089d0ff4b987c2cfc7dfd42c44a7b9a42e1a21d2.nq.gz
    ├── 09dcc93e70bc542cf35fcc8b0768ea50e7acf722.nq.gz
    ├── 0a041280bd00a9d068f503b8ee7ce35214bd24a1.nq.gz
    ├── 0ae3c4e91c685aa4bcd60702286da32fa6d0f168.nq.gz
    ├── 0b6f10f6ae52be0fdc9f9ddada0a57fe762e4dbc.nq.gz
    ├── 0bc6d8a4feb13b93d36c5f2e3264cf67322016ca.nq.gz
    ├── 0c9064f65fc29bcebecc1f754c9460185c72f8c1.nq.gz
    ├── 0c9d1fb37faa1242b570722bd5265c4f840659b1.nq.gz
    ├── 0cc6c5ff58e135ab1c63295c8cdf378b3530ff8e.nq.gz
    ├── 0cf1686b4576d98607b12dff8cc9746515d3637b.nq.gz
    ├── 0d39fa8f9a5c1034577166f53ae57927d8aad203.nq.gz
    ├── 0da729ff1b270b3820bfa0aafda55b367ca0dfc2.nq.gz
    ├── 0e94ff4c5536fa2a7ee0db0738f2854122c7b1fe.nq.gz
    ├── 0e9ee3246f9e264caf97ea19a1554ec9bab0c141.nq.gz
    ├── 107e67d6df62e587075db4fff5660b27f79fd5ae.nq.gz
    ├── 10ddc1f314f614f51641952c8f933f39a722d754.nq.gz
    ├── 117298e0d19d972c8e51def68ce7502c8059e6c8.nq.gz
    ├── 12e4f3941bfec22928fa997ecb768fcdf3bab50b.nq.gz
    ├── 14176756be80b893cf72cb8fba2fca47e018658b.nq.gz
    ├── 14db92bc24bfc01843607b65e1d7ccab1945e38c.nq.gz
    ├── 14ee5bee366ee4012257e5c03745f0ccb0a015a2.nq.gz
    ├── 164be69c3973886c2444e9a27debb22c0e2387cc.nq.gz
    ├── 172b52d618a61afacac3e1b566570826045f04d8.nq.gz
    ├── 1975650c6654138862ec4f8542c7d8e88994befd.nq.gz
    ├── 1a2847a7d2bf547542a91e95715db172beaa4b58.nq.gz
    ├── 1aa562c0f19dc4868f0f36f25f8c0c9675864df2.nq.gz
    ├── 1add98ccdcb70d885adbadf6c96825a8122b2f88.nq.gz
    ├── 1c5b69717deb1bb8e72d246862fa52a809b95a38.nq.gz
    ├── 1e9c8c342cd4dc05ad50fa70710ad8f8ccfb2c93.nq.gz
    ├── 1f04765b4581ac9910a8eee26b9c9757e0d6fbfb.nq.gz
    ├── 1fcab4b9711cec676ae92e76d3385d5e67af71e6.nq.gz
    ├── 20b52ad8c5292f4ba034c9e580bbeadb409d1daf.nq.gz
    ├── 20d09e29170539454689238b85e53da241361fd9.nq.gz
    ├── 21228b4d46b4a97a16c3915708d3e3f97e709c1a.nq.gz
    ├── 216d9de86cd1dae18c7bf704b0fd8cddce087613.nq.gz
    ├── 21e410c74b3e8c7fade8709ffad94c2cd1debd2c.nq.gz
    ├── 24675995f57f05d5a30d871e5b13f7648b1735e2.nq.gz
    ├── 2561be575e12ba6336b84ac968cfeb5bd2903c1c.nq.gz
    ├── 25bc0dfd74208bf09be992154a49c432040b2427.nq.gz
    ├── 269aa304df292ffd34a36632a5549a1099c4d642.nq.gz
    ├── 26f7779f804a2f8eac869e99b36b037dd161b2e8.nq.gz
    ├── 274a0c0ebf81167191c3a29616bd551c33a61383.nq.gz
    ├── 27ea6d04c88bd01f1ab1ca85cb1b5e9c5c3e3823.nq.gz
    ├── 27ff8baa1b786ace9d27b18243a87306a0dae647.nq.gz
    ├── 2809617bb24d71998caeb168e41f7ce475a9666c.nq.gz
    ├── 289287b83898c0fc7053f4fb99bab72d67f296b5.nq.gz
    ├── 28fbc9aa1d4c6f2fab938360c2f82d380be14beb.nq.gz
    ├── 2a59c948e88f69010e2feb0a56c46f864432ac5f.nq.gz
    ├── 2a758fce13de5dd73ff1727b3efd96ad4e5a3fe9.nq.gz
    ├── 2bb44985f0370030b93320599bb071d26032c458.nq.gz
    ├── 2c397557b5a3c725962fb2249f2e40353cb744e7.nq.gz
    ├── 2cff0a735a3e2024d201575c7e09717f245dc8b2.nq.gz
    ├── 2dad83cdcdfd98ce10e72e22ece86e55c72dc4ff.nq.gz
    ├── 2eba78f2326836f735a2a7aa45ce6604e36ebc38.nq.gz
    ├── 2fb061765eedb8fa32a0fe5d653c98b6de8e8e8a.nq.gz
    ├── 2ff96e06cea4ed36aae95685d6c15828ad3c170f.nq.gz
    ├── 31b04417e04b6ec9e003b457ce21045e66f2bee9.nq.gz
    ├── 31b9a961a41782e3a1410d542c6688de30cf7efd.nq.gz
    ├── 31f77aab35d60ccba1cd0c7cc62b36235111be33.nq.gz
    ├── 336ceb707d6f5cceaa103d7b571e539a49580ff2.nq.gz
    ├── 33b08d768ceb0002ba839d2c779d8f3c2320287d.nq.gz
    ├── 350338b9e63b5a9e049569229c17c494847e72ff.nq.gz
    ├── 35fb887d94741039b32e68de6f3b4b44323a3bda.nq.gz
    ├── 3620120279dc7b149e1ef2e77e48218e2bf3ebf6.nq.gz
    ├── 36edb643b7030194822f8324c3d7455f49f055a8.nq.gz
    ├── 3730e14182baa9b88d3eb17c233ed62793efbaea.nq.gz
    ├── 383d272a2c704fa4312c8c7ef5026daa1d5a1ed9.nq.gz
    ├── 387120cf43290f0ddf38757bc28d15a3a1fd8c4d.nq.gz
    ├── 3875a97bf2e61b2f743e98f092faf55712f1de51.nq.gz
    ├── 3929bb6d3a39058ddc21ba42dcb07be3c7bb48f1.nq.gz
    ├── 39a41ef6372ca8ab298e9aeb63dd4b114b7b2b52.nq.gz
    ├── 3a73728758d2c8af9e03e0908ae970218cdf62b7.nq.gz
    ├── 3b8a4f1eb8b9dcc298bc4601c12eadfb9c33a428.nq.gz
    ├── 3c0567d17b8992b098d3aabe8605b1997e767504.nq.gz
    ├── 3c426713332fb092253c10932626c8ae29a6247f.nq.gz
    ├── 3df6fb5102d38cfd5cab560192c3a8776fe6d2bc.nq.gz
    ├── 3e9719f2d8b4930b57242fbb90737cc5a11e7816.nq.gz
    ├── 3ec4ca85498a0f0935920400a822f6a1b2eb9196.nq.gz
    ├── 3f82c489e89b517da95e2c035db414606f2ced9a.nq.gz
    ├── 40a061b1e954b4de28869853a004d04fcd5459b7.nq.gz
    ├── 411434a75d9be39e6d638db6fc682507f455f3df.nq.gz
    ├── 41a4686cd81eb84b242fe0a2ba632162d2699789.nq.gz
    ├── 4222dce3050cf9b3ee4ed7fd89d451c7e700b78a.nq.gz
    ├── 428185516117cdcac62c1eebb4ec1be013b30bd7.nq.gz
    ├── 438ffde839d29f71a413ef856202f53c55e9260f.nq.gz
    ├── 43cbbc679c3372b10ccd77f8e59dd7adecdf6a87.nq.gz
    ├── 446ffff59c8ffbaf936f97d642f1c62177df78b1.nq.gz
    ├── 448847ec755dd079805a7ff2b8019809c980565c.nq.gz
    ├── 45becba3e44b860b98efb49be4284b4071baebee.nq.gz
    ├── 45e865299883c493c41bf64d84a290ae1d7307a4.nq.gz
    ├── 468957dc46e5fe9a3e213e49fb243250a060c009.nq.gz
    ├── 4755b8c83e0c97d0a79882c79bad6fc132df5893.nq.gz
    ├── 47bdfbce37fb7a84bbcdb3ac0e80f20632b146f5.nq.gz
    ├── 47d6835d91d9953dcc8fd144cbc85dbe44c1b3d4.nq.gz
    ├── 47f4a2f8336d7196305b0470d90bc18b372413f8.nq.gz
    ├── 48456082d0ff30b6946f66c5491afbea37c3bc75.nq.gz
    ├── 48a012cb09553215d2726f445d1d643532c902c2.nq.gz
    ├── 48ba7b50d0594a505aa8d20a4d25523eea6bd508.nq.gz
    ├── 48d97d9ea338772c2824bcc8e44bc38feab1ea78.nq.gz
    ├── 494c06944072b15a6af6e206a42ccc9103956904.nq.gz
    ├── 4a983e1f3161f84cb8c5024f55dcc9de3c3b74e1.nq.gz
    ├── 4b5b760c8731a82af2658b6cb5fb6285e42043c8.nq.gz
    ├── 4bd5227462bfdb0ab34f7697501eac0e1192e2f9.nq.gz
    ├── 4d111c890dcd4267b208e8207a84779e6f02058f.nq.gz
    ├── 4d25645b7f4941e2a73c8cebedd91a7ae021a6cd.nq.gz
    ├── 4d50942802a5ddd979a8b8a7b8ce4789dd27e7d8.nq.gz
    ├── 4d7a4f6cb0466a2621a2247468286beea6a75a1e.nq.gz
    ├── 4dfaec271ba1632a4077c29a22fad6c29be82580.nq.gz
    ├── 4f242980de359b5a49b2789f18edaf94f761f1f6.nq.gz
    ├── 4f683d1edcee28cc217113dc39ce53301d290d2f.nq.gz
    ├── 5088b16b257c9a2564faa259b2341ee94d574270.nq.gz
    ├── 51589975f3f84c6a570830fd8652f2e18b4f238f.nq.gz
    ├── 54bf08ff8dc7360292605fb5e56616f088dd6bda.nq.gz
    ├── 5646d4e1a242913ada61e08de93e77a42c8b3e06.nq.gz
    ├── 56a76bfef37e1d11ad367012f688b5eb3f027040.nq.gz
    ├── 57c7871da4ae22ccbf02576cef1fb21ca9f28e14.nq.gz
    ├── 57d5b40344fa4deeea3470d2a975585be2adc342.nq.gz
    ├── 58db3640066b2f8bcb90319e92f8451ce2b060cb.nq.gz
    ├── 5963377466d391f0d0eb4d3ae2b1843b91d50dee.nq.gz
    ├── 59e53d9448713e93f9b481d20076c4e9f6cf17c4.nq.gz
    ├── 59f676df22df59ff33bae68b193583a2321253f5.nq.gz
    ├── 5a22ab384856f510c911dc1e48e4bd31fc7c7ed7.nq.gz
    ├── 5ced68a07236389d0977b862c28f2786245265ec.nq.gz
    ├── 5d38e774276fce0252ba59fd9fea0f97a64ee6cf.nq.gz
    ├── 5e20b73ad2de091db1636854df07617bd761417a.nq.gz
    ├── 5e7000b269be7d3b954fbfdf6f228cc9425b0535.nq.gz
    ├── 5f6e2902e73539536ce9a080b2b3f00baaa831e8.nq.gz
    ├── 5f6f06426823d41f6c0aa3e0e2d7282c8cad4ad6.nq.gz
    ├── 602146f6dbf14576298add07bb7105be011c96d4.nq.gz
    ├── 608eebd8603e63998e1fb9267216a4e277d5b281.nq.gz
    ├── 60c52ab52f30a9dd731b5bf2a77a5f7bbca9cecf.nq.gz
    ├── 60d721c2155a28494f34c2159d23617fa3cca04e.nq.gz
    ├── 622c6409c1766b266148284a11939ed0f7682bf4.nq.gz
    ├── 627d9bec14ebbb0a445116c56b9df2f3b156c0c0.nq.gz
    ├── 6436e0d0b8c6a9123db0909d1f5ba041119afcb2.nq.gz
    ├── 64888edba6952a0d13633334625bd69a0deb0983.nq.gz
    ├── 64af11e4f9fd53d9972596029d0ae07572fab6b5.nq.gz
    ├── 64d8b8fd688767a74f6121745000fe1645cdef44.nq.gz
    ├── 65dd313741aebc5a3749fb524d25ede4c8f00d20.nq.gz
    ├── 67466af4d7ecc10e4af9de0579590056e72ffcbf.nq.gz
    ├── 674a083c208e1c3a079adc02ac24209cd527fc63.nq.gz
    ├── 686ecc746f0ce384864a6f4feb973d6ddaef96de.nq.gz
    ├── 688dfec4e7acd5479c370d4cb7d3647b3782f33a.nq.gz
    ├── 69118cb0036ad5a41984a04bd89e754ab691fdfa.nq.gz
    ├── 6920bd74f059d87a3b68b36ac31e632c6a7b651a.nq.gz
    ├── 6a6283addab3495a0d369c365b2a955699d3d045.nq.gz
    ├── 6a682bebf0ec510c0587cea70a3f60c3f27e32e6.nq.gz
    ├── 6a6efab0929ebeff7ff95ac81c8a948e1da67425.nq.gz
    ├── 6b41a7c05155dddf87206e9895d252daf27c2770.nq.gz
    ├── 6b9bfcd81ac7d01c3ea1817f8e7f2db16f4c22f6.nq.gz
    ├── 6ba57a0957e41e5f5feb010c4c8254b2f566701a.nq.gz
    ├── 6bb859d8b173f65f817a6889d0630320447db54d.nq.gz
    ├── 6cd79f0217f3e31d909af7b803dc1f962a66d0e8.nq.gz
    ├── 6faf9be4f1c0ab96ddb360f339857e763618a992.nq.gz
    ├── 6fb389112be2b57d2ffc87c26e749c656368b152.nq.gz
    ├── 723e06d1c0035001b5bfd0421bad2e0030b5689d.nq.gz
    ├── 72536d6bd7d6a00814aa4a88fd0a209522251131.nq.gz
    ├── 7254294de6a532565738077b838d2dde36a5adf3.nq.gz
    ├── 72ee9d4e17aba094a1b5a7549500ffe560f42900.nq.gz
    ├── 731ba581c4c60fde811e243d623feaf13978ca31.nq.gz
    ├── 737fcd843cd0a405825b14c346be8ebb54f179af.nq.gz
    ├── 75277c08d2796dd3d952ad0fd54afee318b09753.nq.gz
    ├── 753a4968c4875a81e04872966d3f36934a59bd3c.nq.gz
    ├── 75f61ed62c47710f0b5dd6224a405c327fa7487e.nq.gz
    ├── 7629d1c460d161375662e6c0c8dde82d6fc4da39.nq.gz
    ├── 765e0360564a8bf7f9d960c0592f4ee5a44ee63c.nq.gz
    ├── 76aed2b7db7c5e59c3e1a9c80c1d2e652b46f3e4.nq.gz
    ├── 7945c1b7eba71265bec6a482d0d06ecf59e349b3.nq.gz
    ├── 7a012aaee696da3563e37c09488a2be6cf8289e2.nq.gz
    ├── 7a1b0f5d2efb8a90134a9efe1b8e68f5eaacd0d4.nq.gz
    ├── 7b1879495cd7ebf59900e26656bdd286dd4bdfec.nq.gz
    ├── 7c3fbb841da656c5357f8c25fe2bf90ce862d198.nq.gz
    ├── 7fb94d92f540631f8eb865b748019548edf477b9.nq.gz
    ├── 80c8ae0df8c89f2a41e7c2568725fd16734b6966.nq.gz
    ├── 8157a329368d45613cfe5938be84290e07261438.nq.gz
    ├── 81a96e2f28ec35ae25bc624cfd7c97be565c4907.nq.gz
    ├── 81f1aaecd88a1c1e01568cb2b4b65f8e7e90c167.nq.gz
    ├── 82e14f419dab27c00a05905ee9a08b90d3cf8696.nq.gz
    ├── 84554c6f97029aecdd9a29d5e17a8abd8ebce7dd.nq.gz
    ├── 84d27cc6a7a923ec31d78366e7dee148f3db4387.nq.gz
    ├── 84f70b73711a704a6fdcb4d4ff3113f52c1ac877.nq.gz
    ├── 85c172f07c6b82e1795f562a590f8b154bb81e27.nq.gz
    ├── 86fc7b378e5f6bc8f0434feb7c7bc9c9f540da75.nq.gz
    ├── 89165a859a18a98f5c69d7b4a756b445e5ac693f.nq.gz
    ├── 8918d1537a94c391129912f74863ceb83a4975d2.nq.gz
    ├── 89935662bb179f3dbb1071dfd0a78dc5bf1274e3.nq.gz
    ├── 8a2dbd6343c11db141bbc0efa58c28a2ecb29fc5.nq.gz
    ├── 8a7c806ca5eb14f8092a871048ddd5afc8e6704d.nq.gz
    └── 8aa8288648221023342096954af3ce9a2473b296.nq.gz

8 directories, 200 files
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

## Source repository

[psycopg/psycopg](https://github.com/psycopg/psycopg)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
