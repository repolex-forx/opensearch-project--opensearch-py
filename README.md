# Repolex Knowledge Graph of opensearch-project/opensearch-py

RDF knowledge graph data for [opensearch-project/opensearch-py](https://github.com/opensearch-project/opensearch-py), parsed by [repolex](https://repolex.ai).

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
rlex download opensearch-project/opensearch-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f09f8b04e82191e911c7a1097e338036d089cc6d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f09f8b04e82191e911c7a1097e338036d089cc6d
│           └── chunk-001.nq.gz
└── blob
    ├── 0057681671de3a95e09f758653923384cdf31a0e.nq.gz
    ├── 00e77c2085b34b25a71cb8ad445ccda69a7a005b.nq.gz
    ├── 01ed6240ac2e18d627fa834f1ed1fb96870ea382.nq.gz
    ├── 02013f58a9512c6c6dc80be56804c0c6e30ee445.nq.gz
    ├── 0337b3d463edbf8ba117c19724b9baa82e9c90a7.nq.gz
    ├── 0393d9009fc008bcafa6f7ca098c458260da6ce5.nq.gz
    ├── 04192f125901f60889b82062c43c16c78c5e6e44.nq.gz
    ├── 04a59c63108bd62e78c5ef89658b365fcdb667ba.nq.gz
    ├── 05264985d63fd69c1eb1389ac4ae585c1d628056.nq.gz
    ├── 053563c1990c1036be47be42f980819c3e5f780a.nq.gz
    ├── 05c40d048b277f51ac39528314a389687d6b54ca.nq.gz
    ├── 061f32f91b96f05f8fa2b52b2edcdcc19aa33d50.nq.gz
    ├── 0630fc948db39e22a5b53ebe05d926118af835d0.nq.gz
    ├── 07d592c7f95c4b0ffc518745701099ec4ee2346d.nq.gz
    ├── 0984fba247a72b9304c2433a64da72cf02bff2d6.nq.gz
    ├── 0a4ac336f84636f8abbe1995a445e2a09f2b1346.nq.gz
    ├── 0a74a9e18568efbb0cb4c02b2d52e7bb246e617f.nq.gz
    ├── 0af499259ed0675029dfbf287b167c84e9b82de2.nq.gz
    ├── 0c894b5038765054e89b378b38a05b11e303e317.nq.gz
    ├── 0caae97a072363cce8b4f379295ce7a310bf2968.nq.gz
    ├── 0da2eeb30d59b0f5ac0afc3303681d9102f10e49.nq.gz
    ├── 0db78ea1a4308479a9407e0f019909f438fbaba4.nq.gz
    ├── 0eb0c91823e6aab7d60dcc712cc1f67f8d52f19b.nq.gz
    ├── 0fd023788b3c175eea745e5be2473c07921b66fa.nq.gz
    ├── 1092a43e5ad7c0d617e9a7321bdc2701fb5f3768.nq.gz
    ├── 1092cbdf26268e5df7ea165ecdc2442745657098.nq.gz
    ├── 116af409f0099f6fcf216b5c1ab52a63f6c857fd.nq.gz
    ├── 137872736b898c2e0e6454da0e061c31643c5561.nq.gz
    ├── 143cd010ca0778461a2eddc138e2628337d53a86.nq.gz
    ├── 144ee4adac6d9adb0afae14c922f2aa01dcfacb6.nq.gz
    ├── 145cbb6d7d50629d11dec1a2426bde6f3e28321e.nq.gz
    ├── 153eea243c09bfda69e0ee9d8e9dd35f6f064b45.nq.gz
    ├── 171ae83b7c198c3988d17976e1e63bf38fb4c55a.nq.gz
    ├── 177a7beebd579f41e855d9b6da48e8af780f1454.nq.gz
    ├── 17f464dfad24cdbafaa61f03c77fd3a797620339.nq.gz
    ├── 1830d0d12e53d5d9b9234a17f6eeb2dba1b58e68.nq.gz
    ├── 18fbe2b5b54f35e686da3821c7e89596cedc538e.nq.gz
    ├── 19c6222c4ee249c75ede50a9549431d48c1f3f63.nq.gz
    ├── 19f6b897ed38091ed779f5bfcc2cb14a5d231f8d.nq.gz
    ├── 1a721b588fd9307f75154a80b77585ec988749b1.nq.gz
    ├── 1b0968511c78e2140067964e602a95edadd62d6a.nq.gz
    ├── 1b725624a244e38b730b3e34274ee8cf4c771bef.nq.gz
    ├── 1bf6df943d8f5d0e96d992aa60d1854d5651273a.nq.gz
    ├── 1c0d62432d8d0854edff3880a4e9a29e67d5e82f.nq.gz
    ├── 1d0f9981ea3499140ab8adb6d1f7e3e828188b54.nq.gz
    ├── 1d21d851adb6ae490fdeadfd5e01765279e12d20.nq.gz
    ├── 1d57ae3adf2812d5c8f1e8fee2db05bb894eca14.nq.gz
    ├── 1db056faa0336c98fbe7bb18be06f1963078bbac.nq.gz
    ├── 1dc26bf9478ed0a938448109091ff54197213317.nq.gz
    ├── 1deefdcac743dafc507bc50f2edf4e657ca5a6f9.nq.gz
    ├── 1e3051c494c003c2acc1f374ab5b90969a99071b.nq.gz
    ├── 1ee4d17bafe8f838082550e4600cd618a21d802e.nq.gz
    ├── 20b43608468091ceb16c6b49a3988661b1a9b7ab.nq.gz
    ├── 2115333e28fc23c23e2e8de975a59d649d748723.nq.gz
    ├── 211e17441467fce1f56d74dd55485a666ea0bf93.nq.gz
    ├── 2163a490c956d71bdf129306d375a4c6f08ff5ce.nq.gz
    ├── 2290add60dbab5eaa552b2fc1c2d3cf64ddc6fff.nq.gz
    ├── 22e08d103b6965bf09b2dbf8782d06090f39fb77.nq.gz
    ├── 239175e1854cc1c2706fe7edf80b5b0750bf76cd.nq.gz
    ├── 23b582fd776cec835a6c75e7f6c8d856875c99bf.nq.gz
    ├── 23cb583f45b545c8fb0a66465964e873bb5fb7b9.nq.gz
    ├── 243143e420573e054f93d1403cfec38c366eb006.nq.gz
    ├── 25e8c3a44bac1048ee33b91ddffb942c10ac4f11.nq.gz
    ├── 262cf3f2f7be88e8c100745f45f11637a1341b8f.nq.gz
    ├── 273359fea8f54bc94ed782fb4727a3c42c784e54.nq.gz
    ├── 27d599cbfe7330fff019b2a0073f7e4596392742.nq.gz
    ├── 27ffa9e6206d1b0b4ecff672d6045aef88e8ea94.nq.gz
    ├── 2a228278db00466a0274a9ca139f3decfcb3ba08.nq.gz
    ├── 2a861851027d6554b326e558d5f67225ef88e068.nq.gz
    ├── 2b4f9aebb68f7575a1b046c3c92f2494d6d532c8.nq.gz
    ├── 2cd8ee822f4f900c9bdce789f3646442c0b82593.nq.gz
    ├── 2cdb6a4a897386d9b45ea2c406d4bd1fb2b2801f.nq.gz
    ├── 2d0e0d11c6f718cd3ad0c3c2aeb31517b0bde5a4.nq.gz
    ├── 2d3551abb044c5c18169570234d62f18a3404b5a.nq.gz
    ├── 2d39a9caf5352a48fa76877165883b9ce3d4b2d4.nq.gz
    ├── 2ec7f0d0b7a152528c44d8586cac3061d6ffe8ce.nq.gz
    ├── 2f46cec1fff7c9139879dd34337b2c6d4529774d.nq.gz
    ├── 30a4b41eaa6869c861c949b930805409813ab854.nq.gz
    ├── 30adb879f7cfcca39bdcf8c30df57d8d87489141.nq.gz
    ├── 319cf8192850dca7eae93630eec7a84315b708f3.nq.gz
    ├── 325e362cd92b210a44799e000e4e4cf4dab30c44.nq.gz
    ├── 3324e6a284a87604a94ddf4daaba64650c39abe1.nq.gz
    ├── 34ae41b4e837ebab8af2fdf80a39f6accb28c9db.nq.gz
    ├── 34fd8bfd25f3187ad233495819199c35b70162c9.nq.gz
    ├── 351691d3774e09d06f52196be7e5448b12b21cf2.nq.gz
    ├── 35dfeed3703cb1010b50ff432fdc2414151d5786.nq.gz
    ├── 35ef2bad38ba0d96628aadd97a54f2569cad4412.nq.gz
    ├── 361d002d1c2dd16be5893b6388b7fef4aaa23e3d.nq.gz
    ├── 3651aeafe14936af5cefca43dce84e436065a96b.nq.gz
    ├── 3741cbcb5488b43e8ed2202969cda02583271181.nq.gz
    ├── 376dd14fbe58170e2ba37a72032a0086a37f60a5.nq.gz
    ├── 38758d354514cd315eb20a6500250a40dc41af42.nq.gz
    ├── 3895641c38d86e1bcc9d3f3bdedc51a1b0514f74.nq.gz
    ├── 39227bf0f1139d8f7b1d59d968adf762d0ba910c.nq.gz
    ├── 394de182fc4b750e007a4e5f1f1d841dd454c84f.nq.gz
    ├── 3951f4c9ac0c058443de787565b7265c94569035.nq.gz
    ├── 39a3265980ba7e9810000b0fc5956092c809bdc7.nq.gz
    ├── 3a6ea4b0818ec051006076f95b2409b9591054e9.nq.gz
    ├── 3afdd1dc735f1c5344e871045fc0d6aec195d77f.nq.gz
    ├── 3bf5300d01dbb7d501ab78191f049d622b7c16c5.nq.gz
    ├── 3c2f8ab008664d5481aa015dbd3b196a68bd8905.nq.gz
    ├── 3ca618a4c689286012ac33b5ab2a43abc5f372b7.nq.gz
    ├── 3d2abfa414df0533412007c0bf953cf955a8d80b.nq.gz
    ├── 3d33343cf3eebed04d1fa14cfc24bf46ffc7575f.nq.gz
    ├── 3e406d3fb7a8f7521833c0a84683618560ae6550.nq.gz
    ├── 3e684c489adb221e6db2c1226a1732a491a7da63.nq.gz
    ├── 3ffdd52ff7f782ecc95a216b5c07e2dc18894048.nq.gz
    ├── 408073602662a46266d150a9df5d6922b0a70b2e.nq.gz
    ├── 40f278712f1f7492628eb5112a4d88f12d9b4504.nq.gz
    ├── 41469a52b0cdefe779a301552f3e3cec7763f69d.nq.gz
    ├── 419feadc134a45a8ec624449f6020c8fe5ddf1ff.nq.gz
    ├── 42b2c3f1f0652b2e479dc295959ba3380d8d0709.nq.gz
    ├── 42deb3cc0994d0d3cd8804218d4dccaf80d28113.nq.gz
    ├── 43f2d60e3abf2032330cbdc2caba58e27cb00bf6.nq.gz
    ├── 4409c446400f57c3df159cdbe40f0a02affb1d14.nq.gz
    ├── 4439b232d16f942508a180d0a01f0e44eb409e8d.nq.gz
    ├── 4449eef54ae000e5e165f669b54a95d3e53b0d20.nq.gz
    ├── 454369703f5df9e8f0de01e395727876732bfd25.nq.gz
    ├── 4569138fa5abfad149b687dcdde5abaa1de34cf4.nq.gz
    ├── 45930f03ce3c0befeae484375c16dfb60c425e45.nq.gz
    ├── 45abca6be11379b7786c4feaffe2b98d7e281583.nq.gz
    ├── 467c64a3cc57495f008bc38132cd2b1bc21bf581.nq.gz
    ├── 472590333af811372b06e307a75cb4afc77b275a.nq.gz
    ├── 474b7e40d350bc6315d010ae9fedd78d41aa3bc6.nq.gz
    ├── 483f4040494fbbe67466ccb88cf377c14aa368e7.nq.gz
    ├── 48459a6934b0edb5d3724930afd41549f6c5233d.nq.gz
    ├── 48b9675ae48747fe07d86f45e999ccd09ff5d951.nq.gz
    ├── 498569819c68d9d3c54fce615f654ca70faf8402.nq.gz
    ├── 49d666b5245e83be03156e00a3eb312f543ceb94.nq.gz
    ├── 4a31bcbf59b6d1a05fe0928b4e3815fbc82f16da.nq.gz
    ├── 4ba06d3cd8f3b72bcc90a9176b44ef677a7f15ea.nq.gz
    ├── 4bb6cdb57e255de0464ad4994e7ec53da2b9f88b.nq.gz
    ├── 4c0845df3cc94ce2511a8a04979b1026500c1a92.nq.gz
    ├── 4c51e2e5c4e7d3b05c7cb001f1b6665390b80ab0.nq.gz
    ├── 4c59e0482baa709b2873c966d35307db13209b18.nq.gz
    ├── 4fd34112fba58d9236988eeea9c7f1fb60f94e40.nq.gz
    ├── 509cd1735fa55479eab0b61a77ac6b260d0ca0bf.nq.gz
    ├── 50f5391f8edda945dfc66e9ec58c49804c144292.nq.gz
    ├── 510e1cdce4d95ddc7df043bed9585f71678c4e0a.nq.gz
    ├── 5151c4a1d72c172344d1f36b20ccc988f19c6e5a.nq.gz
    ├── 51be201ee565dfdc2136da5337f0b32b5848c67a.nq.gz
    ├── 51fb5f30faf32b5270a801385a0467bb5c7d2e53.nq.gz
    ├── 53a9435075c7719e07ed332a088f4a23d139a7e4.nq.gz
    ├── 53ae9af25c04a3d9912dfe8bdf01c45522f47911.nq.gz
    ├── 54432eb6cdf9f0a84e7e86d5ca427f4bbeb975de.nq.gz
    ├── 559d038738d039e3dc379c44c354966a3d530d90.nq.gz
    ├── 564dd691ec1a7942256a7c3522fb804ccfb22433.nq.gz
    ├── 567c35b1595b5a6d0bdd10b68d602d478dfc7722.nq.gz
    ├── 56a518271e6b3ab667acfd0f3034fcf6dd2c1bf3.nq.gz
    ├── 577644c0767189f34888520d27b4cdf6298eb415.nq.gz
    ├── 57ca1d68174ab947074dcbca275a0a0d9e2f123c.nq.gz
    ├── 5945795dc73ab83d309f553c7104e4f7ab0608cf.nq.gz
    ├── 5a57e1ac55efa2e0deda35ecb6849fdf9c746fec.nq.gz
    ├── 5afa8913c38a008c5289288ba30aa9d90beb5bda.nq.gz
    ├── 5b72a062f123f19261c5f9f3886d9e1dffde5a5e.nq.gz
    ├── 5b9267f22913374b42ee306c39a43b23b03e619c.nq.gz
    ├── 5badce18eed861fcefc03e5d1605e72cbde39da3.nq.gz
    ├── 5c7dd29ecebbb4c99d057e6bbb8726489a39af1f.nq.gz
    ├── 5d6974ab5dee837b543eaa2bd8142a2065189181.nq.gz
    ├── 5d7030658109705c784219592bab22a8364dbeb9.nq.gz
    ├── 5d9108a4f791ab308ac303db7aa433ba9725a577.nq.gz
    ├── 5fa29afc97e16ec3ac0bc359dc60bf631b344797.nq.gz
    ├── 5fd194610905d897d6485e4d2aa90c719ae71dab.nq.gz
    ├── 6042859ed10acd62b21f12d6bb964f23a3722609.nq.gz
    ├── 605458dbf164088be52147517ff4ae55ce337419.nq.gz
    ├── 60c34c84791c399e7f5d1d47f7725c8b5fde759d.nq.gz
    ├── 60df8ae93838f727bf76a20f97e676331cf1bc3f.nq.gz
    ├── 61323bd76a04dcf8757cdf7556e4307013cc21b8.nq.gz
    ├── 61a70cca84c51317e862deae64d40da0869df486.nq.gz
    ├── 63b43e4e3bf4680cf0ce9a22de0f19fc19cfc351.nq.gz
    ├── 648f4c72fbdd1edff4739dec09aeae44307e69c6.nq.gz
    ├── 6523554cc1cd3e7e763bfce365cc72279e08766d.nq.gz
    ├── 655458f62d54ecfb4dc3ec79daf6a224c929a4b4.nq.gz
    ├── 65db51b83bc711d37fa993ec3d1e02f44996676f.nq.gz
    ├── 6661408d5956365a5fdb91fadf7a319277cd06c4.nq.gz
    ├── 669deec8754b4916649cae0410337898b056938d.nq.gz
    ├── 66ea7a73e9affb940df54c21130ccbc9435981ca.nq.gz
    ├── 66fc3ddcbae95bf10044041e18833106174d9e4d.nq.gz
    ├── 6725849adb73c2351fb7cc1a43d3e7deed6709da.nq.gz
    ├── 675856c26899ecc937d0b800efad2dd7781bf3ff.nq.gz
    ├── 6826b83e0a0184cb1a402c71355df194a6fd089d.nq.gz
    ├── 688832dfbff755f3bb60bbd54c5463bdfd316741.nq.gz
    ├── 68b6434aa6959a7331b970193ff3bbbea2ea7a3c.nq.gz
    ├── 68da053339c13c466ccef57ef51520089cba2f36.nq.gz
    ├── 6992fd1f1458ebd7dbde077fcddc23e0e1eac1b2.nq.gz
    ├── 6b367c144e3114374ebfcef47e66f6d870dbe091.nq.gz
    ├── 6c0097cd1bba1023af97c4e4e1fa578e685b130b.nq.gz
    ├── 6d12c8ef02c83c7b561dd3b1cbff0e603c71ac42.nq.gz
    ├── 6d3d320dacf5906fb4c41f423e2ec98b3310ee77.nq.gz
    ├── 6d99abf1cedc1b29121d1abfded43829a20e17e8.nq.gz
    ├── 6da892934adaf5969a7f64cfbbcb6577cb72f800.nq.gz
    ├── 6de69c85367b1ce3b16544ffea5a478e6508e92d.nq.gz
    ├── 6e34949751d5c2a33f6fc7e7fb5cef4bb74aa85b.nq.gz
    ├── 6e4af16347b0c7070d3009ae5916bf76c41da6ef.nq.gz
    ├── 6e5b9261c24fbf248edb957cf3a38da7056a9319.nq.gz
    ├── 6e9e9715e9d26eeddfd1792800a3c0d321725af8.nq.gz
    ├── 6f1aa79e35e32357161f7bae44c30bd7e4095ade.nq.gz
    └── 6fc0e17811478c939193f8f162a1200a4169d649.nq.gz

7 directories, 200 files
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

[opensearch-project/opensearch-py](https://github.com/opensearch-project/opensearch-py)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
