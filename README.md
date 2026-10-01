# Repolex Knowledge Graph of block/coplan

RDF knowledge graph data for [block/coplan](https://github.com/block/coplan), parsed by [repolex](https://repolex.ai).

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
rlex download block/coplan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5640e3881f9b4d8c52bb16e38fe63535635df1cb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5640e3881f9b4d8c52bb16e38fe63535635df1cb.nq.gz
│   └── repolex
│       └── 5640e3881f9b4d8c52bb16e38fe63535635df1cb
│           └── chunk-001.nq.gz
└── blob
    ├── 00c024cf8ce7d6363807c8ae27323bf245e13cbf.nq.gz
    ├── 010890a1422f120544030a4d9983168404f6bcdd.nq.gz
    ├── 01fd0d26e29df094913100fe32c50f80bd6900bf.nq.gz
    ├── 025f8afb97bac252b847129a49dee82610fb22fa.nq.gz
    ├── 02fa938142e6b1528e3cc4ae0d20e34babff5521.nq.gz
    ├── 044d0fcefebedac113ed38a04cb78e7a9d087fec.nq.gz
    ├── 045dba44eafc5f2749929880428f3227d7d111de.nq.gz
    ├── 061f8059e6a83145ddaed43383346bde68296eda.nq.gz
    ├── 066425b34c21a0d577effe3fd1c1a4bebd8e5b9a.nq.gz
    ├── 0687c9a6b263a166d2589bf54c7fc714507bfb0f.nq.gz
    ├── 069ef3b89c63a48195a67670a74c103ae06d1a31.nq.gz
    ├── 0737c6ab6b91503df3215e57cc6a3fb83e3f3734.nq.gz
    ├── 0739a56420d7c4e22d4fe9807c8dc130f3f7b908.nq.gz
    ├── 0775a88886a77f07e350b3e2430a5855bf7d1c22.nq.gz
    ├── 07d9bd2014c380573ef22c835ce37fd5667b1c70.nq.gz
    ├── 0844eebc360fd4cfcffa489aaaa5ceac1b4be40f.nq.gz
    ├── 0923791e07cb7889a019468243b2d312ab6cdefd.nq.gz
    ├── 096f8cc768af0e95bfa2ea3ed0622a57ac3b394f.nq.gz
    ├── 098a04e17164d0bf5e18345d2a92e330394be0ae.nq.gz
    ├── 0bfd9f7aa577ea5f95c1c80822fc169032e483b7.nq.gz
    ├── 0d2a2bfd505424a4c2ae83f4ec2e1eeaf350e16d.nq.gz
    ├── 0d7b49404c35d6a69db67a6050d83927ef46f320.nq.gz
    ├── 0dad8b213ac536cbed24a9c910faa4aa47d0ad41.nq.gz
    ├── 0e5cb91f9306e4c98a8855eb7e1975c968f4ce42.nq.gz
    ├── 0e8760fb3550a53c6ecf9b2b1ac8e6f5e4a4fa82.nq.gz
    ├── 0ea51d3b991a57624cc7cc3892aa798ee757461a.nq.gz
    ├── 102a1f558013b934417ea1ec47af5f83d356865e.nq.gz
    ├── 10e22cc5a07af542c0d71c92f8af9a34fabf0192.nq.gz
    ├── 1141df49b4252be56f126896cb232108b3fc91a1.nq.gz
    ├── 117ed298768800887f38ec4dc55c44a74404a4c8.nq.gz
    ├── 120e445788203a4c7085676e7ed906b96fb15bd1.nq.gz
    ├── 1213e85c7ac805be18b4ea04f93ab028cc975255.nq.gz
    ├── 124a1785a6643e861f53987be856a7b54f721c9b.nq.gz
    ├── 12fc814e65833da602e534b2962a59ca8452ed6e.nq.gz
    ├── 13c2ed30648e76e873b5d630846baad29fd678d3.nq.gz
    ├── 14927eaed0c4fda26c751ff7f7ab6145fd0821ce.nq.gz
    ├── 1494a79a32ba53ce22ab3088308cc79bee1939e3.nq.gz
    ├── 150a238857c91e70c35d869407a573b158975486.nq.gz
    ├── 15103b2e5b5a7aa25dabd0bed26197a8683ca570.nq.gz
    ├── 154e0cd1537809953ae8ef13bd3b81275636e0ad.nq.gz
    ├── 1581c61d150ebbfb3df01d4611acffe05f8fdd0f.nq.gz
    ├── 1600fd46261e920093a7bd86188e2285cb22510d.nq.gz
    ├── 1662583d22e48320e651703b91a0ebd9363f167d.nq.gz
    ├── 16e7e73da0ec952b3b3fc74bbca802bc29f56128.nq.gz
    ├── 174f34e94f6ee567e9ffc3d4ab33a5a7b85d4444.nq.gz
    ├── 17b08b496a1a00587c91e77810fe4e7b6c3120b5.nq.gz
    ├── 1895f80a909176536cb860d8642a1c0e40ef943b.nq.gz
    ├── 1950366aeb21c654ad1a5feb3336e3cb340fa174.nq.gz
    ├── 196e63abb0b622843a15441c22fb2fc42ec696f3.nq.gz
    ├── 1970db55806a96109f583e9c4832b5ac0853dcfd.nq.gz
    ├── 1a5ea1eb93830ae7d6def77b96a4a25cc522b44b.nq.gz
    ├── 1a8745d0165271b3e9bdf1d50f610b6602abad6c.nq.gz
    ├── 1b12de6bf2acddd1b07ab4678028352588b052c7.nq.gz
    ├── 1d54aa1ea6b44fa42c66721db92426d5844d3436.nq.gz
    ├── 1d6042bcc0a4f3dbb24aaf5b8f0b6a480962247f.nq.gz
    ├── 1e7ace19c2413f09b82f61c8b64e49b5b3444076.nq.gz
    ├── 1e953d439a73ede02fd35d8844f7d34993686657.nq.gz
    ├── 1f6080a0f2a68548d50d2f4e75f5dcbb9ce5c829.nq.gz
    ├── 1f9040200f439aa7874aeca9ea605162daf65359.nq.gz
    ├── 200ea5267cfbaf2810f81d8ecd4990b26b9419c2.nq.gz
    ├── 2017abb21c3eb1c5be958f27a1188f2bc1ac548d.nq.gz
    ├── 2109d7939f6b32d7fdad22b6dbc5f3e91c2d53ce.nq.gz
    ├── 2229d512e1c24899942e582eb799b725b22e6f5c.nq.gz
    ├── 2241f5366202108588f5e23c119985b3b3660b5a.nq.gz
    ├── 2328a7fd1c543fe4c159db94ef6f5534cc116920.nq.gz
    ├── 23321c739dc6a1f6c3a107993792f9c6d563263b.nq.gz
    ├── 237cf8542bb746bf6bc0b93d19c413527663c80b.nq.gz
    ├── 23d1214c888dba4b92fa4dff21b7545b02dfc8f7.nq.gz
    ├── 23db6c025581aba0b52cb407bda86de7de293c4e.nq.gz
    ├── 241ff31b658825af53b5f48076de6f9d7bc87957.nq.gz
    ├── 242985cc3f3113769b38d3ba2d9d3fab167cc664.nq.gz
    ├── 245189c932427d198fae72df36cc3483080fdb36.nq.gz
    ├── 249092ef98e3bce0294f75b3b8289f0f29eaf7c3.nq.gz
    ├── 25732e05a674d7fd531400e7c29ae9f387c3acb9.nq.gz
    ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
    ├── 27b917eb35f58d0477b7f7a397d8477de6d9f268.nq.gz
    ├── 290ba107b94e2aa3e90fc95d3bdf2990954c73c4.nq.gz
    ├── 292573b39f40d63c6d37843cf07a7cf18ef12bf8.nq.gz
    ├── 29b1c226658a9299d0bd82681f1e4fc7a2cb0238.nq.gz
    ├── 2adfc435dc243975240eec62de8a893d6eb40f58.nq.gz
    ├── 2b8f50d6391a8cc86be3b5209636eeff52824d11.nq.gz
    ├── 2bd668964f7c02caf1190e3699938215952d7581.nq.gz
    ├── 2be7d66d0c15604d08deedfe4d3df1de4f89c900.nq.gz
    ├── 2c0096bac9351d99ccc5dc1e8888d0ce097a6d77.nq.gz
    ├── 2c455152d48057e7bacd9ad6d42ce275b5513234.nq.gz
    ├── 2cce92353a9a9b6c2e46f6a4fbcd08f7c3c3f1ae.nq.gz
    ├── 2d6b257de737e7f6fb1ad87fbde3cc5e0272a4bf.nq.gz
    ├── 2d89fbbd17333b9c76591abca44f8aa9657b1270.nq.gz
    ├── 2df38a57997f66b77cf8f25f15a9d09b87226eca.nq.gz
    ├── 2e0c02fdd8d3d6ce4af5708899f976fe0efee98c.nq.gz
    ├── 2e8e5067b59d6022e71388ce81bb6d15f06adf26.nq.gz
    ├── 2f26055b035fa07d54b1959115720466371e9048.nq.gz
    ├── 2f337b7913d76d53dee49da0a3f9f6be30d68a4b.nq.gz
    ├── 2f4d8474b4c331ed50e01bc5dfe8502a09b85df3.nq.gz
    ├── 2fb07d7d7a33b7e6585ef9cf0dc2e7c516e48d2c.nq.gz
    ├── 3011511ab699690056277003f20084cdd53cdb99.nq.gz
    ├── 31885bfa10cd705c6f632691922a199eaaed2d0e.nq.gz
    ├── 31aaacd29f75db9741baa1d414140e99750c1d1e.nq.gz
    ├── 31d88d5e299db338a9dde5950d047070a32fa959.nq.gz
    ├── 3235bc212475185e2072d6e20a03a6f7e87787b0.nq.gz
    ├── 327b58ea1f01fdc8e9ec434b3c9710bf84c8a5a6.nq.gz
    ├── 341af89f2640f60a5eeecefdb8a04fb9a08bae8d.nq.gz
    ├── 346d2bb90faccdce13c2989d7d844572225378ad.nq.gz
    ├── 347787f9a0ad3f1e03fc5007c18bf8ff5954fddc.nq.gz
    ├── 34af3d1056cecab7a222b2297aadcc356f91c6d7.nq.gz
    ├── 34d6154d5455253d9588236456cedce95cd1980f.nq.gz
    ├── 351043acd1b751c910cd7f0ae0b134b1c662a51d.nq.gz
    ├── 35983b13f59b6c536ea5ae1d632827bf36ade329.nq.gz
    ├── 35bf89025d91bff6a544c829ad404b3d46116fb9.nq.gz
    ├── 3649890fe5405a3c869d11a774512509bc447be1.nq.gz
    ├── 36502ab16c7adf42dfc804702966e684d68610dd.nq.gz
    ├── 36bde2d832f6c5c1545ec6eacb82cbb79f4473b6.nq.gz
    ├── 378d4e09fa64f321da89b336879c8d73f95d79df.nq.gz
    ├── 37ddd9991c9baf3fd555db76082ec897e0cc08cb.nq.gz
    ├── 37f0bddbd746bc24923ce9a8eb0dae1ca3076284.nq.gz
    ├── 3860f659ead02224f524351d612cd92aefcd5d8b.nq.gz
    ├── 38c4b865963840c115dded07ec5c767b7c1c2483.nq.gz
    ├── 38f87adbb9b6da9f7501c5a28aaafdd1c2ba121b.nq.gz
    ├── 3903b93952de547f0cd51be16251eb86a47da397.nq.gz
    ├── 3a148f73721e427b2abf328ed186f6903f4fbef1.nq.gz
    ├── 3a77a19fbc6f5ddac9a06ae404d552926c26676b.nq.gz
    ├── 3aa92195c851675eff94fb30223ea45255538b49.nq.gz
    ├── 3aac9002edca73300507bcd9f9589ffb36ba1faf.nq.gz
    ├── 3af3019ba4618dda3d5311a753dbc5e287817423.nq.gz
    ├── 3b73eb25de3955a25ff2e8d3741fe26ea4627d2b.nq.gz
    ├── 3c34c8148f105d699e8ec9b769531192f8637d9a.nq.gz
    ├── 3c8dc730e8a11f7bb0ee2b29deedfc22fb69c0c6.nq.gz
    ├── 3e060f173280c71093478e77869112ddfae01b66.nq.gz
    ├── 3e4acb9ea9f38e18cd9097536f69c67858448596.nq.gz
    ├── 3e77283b8cd6b41c0ab0b0096b77623a71cb7288.nq.gz
    ├── 40fce18e443d7b406f0147fc3acc0b16f27c9460.nq.gz
    ├── 411ffdcc11d42b5daf61a0d309f37e40bb9524c4.nq.gz
    ├── 4137ad5bb07d239eec05fbfd9b7b6305d4c5429f.nq.gz
    ├── 413e7ad5e90f4f8366a0d1803c0cfd9343cba20a.nq.gz
    ├── 4168d1944ee225febea432805484c368f77811dd.nq.gz
    ├── 417995410fe3e04209d457ee0ed1b15e775b1a13.nq.gz
    ├── 419fda8f99721f1a7bef9b71b9c67325115f091f.nq.gz
    ├── 42aec0f889f9566f630f6959340a18812fc6b92c.nq.gz
    ├── 435bc57d7524a4c8c1d738c9f61947cc3f7eb6d4.nq.gz
    ├── 43da5db3368df7b00c622894ad584d780a21e47f.nq.gz
    ├── 43f28b2b94c79540aafff05f6f33478d72c359a8.nq.gz
    ├── 440e1f72645b1b7fb022c1bdf9d6352ab8a3c08f.nq.gz
    ├── 44a0630041c57f110793e1e7734c3e816de7615a.nq.gz
    ├── 44ff92731a6ea6c0f5458a3692caf0ff5b5b9cb9.nq.gz
    ├── 4516f56a5b4deaf4621daeb81ad9d3acfd72d530.nq.gz
    ├── 45f73550456ac958c58b9f9eed18817431bddefa.nq.gz
    ├── 4719e96d3d96ca6214a8283146b76513031afb29.nq.gz
    ├── 4769aa067c923519978229dbb0771966d07d1b31.nq.gz
    ├── 4776ed9090e1ce6428d29811d7ef87104792c310.nq.gz
    ├── 48c5968d5baca3147902e905a350edb824a36d64.nq.gz
    ├── 493ce30469399f00cd7e5b2c69f8c211eb089455.nq.gz
    ├── 498a44b5b25911bfb74b98e59dd1d658fda67714.nq.gz
    ├── 49ccfd32e8ed035a5532355efc48911fbce674ed.nq.gz
    ├── 49db356d50a719f07a841cab9db818aaaa0da90f.nq.gz
    ├── 4a07d219b44dc08a6160069681d14993a3285ccd.nq.gz
    ├── 4a1abe9f57666555372018d9f589693396f94a50.nq.gz
    ├── 4b0d1544a0a23bd387f97900ff3ef24f96e8352a.nq.gz
    ├── 4b727cb99373ab17489576520b9f1dcb5981b1f0.nq.gz
    ├── 4d0ff8d8c8d838ad9a518f9132cd0a4bb378d17a.nq.gz
    ├── 4d57321a425020f01dd172156b019a2b860a458b.nq.gz
    ├── 4d886d983a5b36c5dd12744e80e5b9bef2aae707.nq.gz
    ├── 4daa18b1063f7774695c1b92818e97e0660d48b0.nq.gz
    ├── 4dd7b085ee47e0a822ee27bdf83e95a7c439b24e.nq.gz
    ├── 4e4a590ac0e68389c04b7a3857c3e53437f8772c.nq.gz
    ├── 4eb33fb5a192f40d005e42e142164f9ff3c92d9a.nq.gz
    ├── 4ee1cbb43e746d5fe9c6c9b8421fd048f0b1abaf.nq.gz
    ├── 4f1d6a705c659c0889d4977e065ab318f9e0ece4.nq.gz
    ├── 4f59659b1cca4871354b383f8e9ffb7abe3e2a36.nq.gz
    ├── 4fbf10b960ef780b748861e6a616a4d88b00b50a.nq.gz
    ├── 4fc3a3920376fda42108dc7d89446585ddc5daf2.nq.gz
    ├── 4fdb3b5144349fe901151557a7f10304f737d7cc.nq.gz
    ├── 5129fb4980756d97640c2e95a34677ea9a03af80.nq.gz
    ├── 5154385726da1b3697a939698053c7a7b6641c31.nq.gz
    ├── 51848ae6276f2c28ae5dde84d607bc2a0b4853d0.nq.gz
    ├── 51955160e671e03062562c3ff1d7876a5f86e817.nq.gz
    ├── 51968b8494e8b0410a4c485763dad86f51ad7831.nq.gz
    ├── 52477f5dd469bee12863dada718fb6124900ab68.nq.gz
    ├── 528e7a80963d2aa0404acda364b9034541bf2c4d.nq.gz
    ├── 5441cc46f4587e144371f320d3ff067ad8316d50.nq.gz
    ├── 5443f7ff335ebd5d604e86a8a816c5ed246a5289.nq.gz
    ├── 54649f4a740e4ec2531efd76f98d6df87c677a65.nq.gz
    ├── 55b464d9622e454fb7473ef94cdf70c663d1fea1.nq.gz
    ├── 55c5cf6fb12a57b34dfd6394e12121fe24034628.nq.gz
    ├── 55d303a38574a61f2529b1549b02295970d0d806.nq.gz
    ├── 576be82e373be892ee55cb041fa3ed5e1679f30f.nq.gz
    ├── 57eae4026dd2fc12ab1fa6eee82b40982ce0e476.nq.gz
    ├── 58baf442f4c7f956af59b9dcbbe9614e8f17048d.nq.gz
    ├── 593efbada8de49279e382034bd620d62d2db11e8.nq.gz
    ├── 5950f4a01d04c72e3e4df699771679992783c7cb.nq.gz
    ├── 5971bd7de443f71519d3bd0c41593c20a9aa6cdd.nq.gz
    ├── 5975c0789d7cf1cc918034ba31a8f102e06e93b9.nq.gz
    ├── 5a20504716c31e8314709231e0268848c5b5f76b.nq.gz
    ├── 5a4b7579e4a73cf97dc691f7ee95d45bcbe818cb.nq.gz
    ├── 5a756f9feb2e516ea6b7b02b4606e0a15a7d0d44.nq.gz
    ├── 5b78d6ba2accae6e4bb984232786b7331ae06768.nq.gz
    ├── 5c4b43fac1dafc5056b046c68d1f49ede34def23.nq.gz
    └── 5cfc018f4ae320ff942e44810117c1d170d5a5da.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/coplan](https://github.com/block/coplan)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
