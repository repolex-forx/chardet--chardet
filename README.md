# Repolex Knowledge Graph of chardet/chardet

RDF knowledge graph data for [chardet/chardet](https://github.com/chardet/chardet), parsed by [repolex](https://repolex.ai).

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
lexq download chardet/chardet
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f1d4e150be7070adfbbdca164328d69723e096ec
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f1d4e150be7070adfbbdca164328d69723e096ec.nq.gz
│   └── repolex
│       └── f1d4e150be7070adfbbdca164328d69723e096ec
│           └── chunk-001.nq.gz
└── blob
    ├── 00242c0d08cbb77fcc916648a0a5424f599eb8c4.nq.gz
    ├── 0063935ce65a9adb52e1504f0783366f355c0b85.nq.gz
    ├── 00877e55ba2b8eac916cd16eb0b6081d0d0a6d2c.nq.gz
    ├── 00a22f0a3c608b2b5889286200bba45e47358db4.nq.gz
    ├── 016f82766a049abaa2adc8dcff9207331b17debe.nq.gz
    ├── 0258745985dbe20128379e2fe640f2631931cbdf.nq.gz
    ├── 027353926fcd5b8cbd037655b9573092f8dbedc3.nq.gz
    ├── 0319c194f22685e06eb8eed9c4fc8425cc05ee44.nq.gz
    ├── 038d64bf8d89c9c92f1a3739b13f501ee6a235b4.nq.gz
    ├── 03953f23f8e1af2986b9d06ac58dbdba0788288e.nq.gz
    ├── 0546c2ac95d86c76b2bfdc9038d465b68b89c30e.nq.gz
    ├── 05f6a2c14c2d2838abac7df279213336d8a9563d.nq.gz
    ├── 06123407d05b0f4e5a557c0785b922224f458369.nq.gz
    ├── 064345b0867d4d23ef17a4d7d11663dcf3cf4adf.nq.gz
    ├── 069ad28279434103673ff9fda5000da4fb5be3ad.nq.gz
    ├── 077e5ca402d23d125a5d78f94ea1627af4aa49e6.nq.gz
    ├── 07f9ff8eecb83eca982167301069ff74b0d35a3a.nq.gz
    ├── 08eb08527d0cda7f8782cd20dd5ec4b8bea7812f.nq.gz
    ├── 0927a0c12ab1f6f36452838c2d1ea5f3fc68e24f.nq.gz
    ├── 093d169797893b7bbbe7280df873caf18e5ebc6b.nq.gz
    ├── 0a051feebe03eb4d52c9bd3a2ea99df84a12dac3.nq.gz
    ├── 0a08f159537239c9dff51a468c01b2ca6b536188.nq.gz
    ├── 0aa10c86e8d8c535c90d2e1e4c006319d28d332c.nq.gz
    ├── 0b645b57b5e67ef36ccc63301c9cf79950e088f8.nq.gz
    ├── 0c8b3cb5168af24d3e8133bf7a8325bb0255d21e.nq.gz
    ├── 0cf137dfd4c1968b32831586b2861317310bcfc7.nq.gz
    ├── 0d852239f09dc960d81975540625adec602f372a.nq.gz
    ├── 0feb3420e839348c060f76490d88a1930e013a55.nq.gz
    ├── 1156146ca25ef5f2d484411087a79271ce46c6fe.nq.gz
    ├── 11a911cc75f069e1b2647d5e10caa3978c91ae72.nq.gz
    ├── 11b1e39220076c9808ac6ec273277db9103caafc.nq.gz
    ├── 121a02542d897da830ec8673f29345b366a9f441.nq.gz
    ├── 1238f510fc6afe2739f3f7a44359cfe471c154a3.nq.gz
    ├── 13f60552d8ae5c1afbb5b602456ba56858501302.nq.gz
    ├── 15e338fc1117b6cbd88fd09bd1759fb806973e3d.nq.gz
    ├── 17a14c116d0fa16f4efa4cf783137b34b0b2c37b.nq.gz
    ├── 17cb59d8469bb1ee1c2e4ccdaf9fb98248ddff19.nq.gz
    ├── 182a7922186fdf48931c2451f046009f4ee88e28.nq.gz
    ├── 18b0c0007507e60dcfa115c842fe1263b9b40d0f.nq.gz
    ├── 196e08d4fb285b762455376a7b73f527541adf90.nq.gz
    ├── 19c86b0c0f1ded87fab0e9ffb359068aab89fd10.nq.gz
    ├── 19e161688261e92f2f0ee77ceb9ae97304f92758.nq.gz
    ├── 19f65dc9d49b90dc056b0631924b29a6a02a9464.nq.gz
    ├── 1a902bfba60d159ea73def2b308f71eba3d04d9a.nq.gz
    ├── 1b20c5ac6d351eb22c66bdb88d46ced5eb1dc045.nq.gz
    ├── 1bda9ff1620fe71ad78425112af48e21a14f52ef.nq.gz
    ├── 1cf3aa6db6d938b571af5f4ca6cb397fcc73dace.nq.gz
    ├── 1deeefb636715dec6b33015e24cf873c816bb9b6.nq.gz
    ├── 1df6d3d743396fdb21aac956b93e12146b0ad2ee.nq.gz
    ├── 1dfcc39eac8e24c985a9853ef8e3cd2e412200ea.nq.gz
    ├── 1e516ff266f4c9c89312531b4615a694724b54bd.nq.gz
    ├── 1ed89b8b36d1683a542ab594e205706bb24515a5.nq.gz
    ├── 1eee253c047ec52c4eb6b473a4f3e3e816a034cf.nq.gz
    ├── 1fe5f3c782bf1bf9013108f454915b3839b63696.nq.gz
    ├── 20b2b98b7ac2cb9fb3883a8261c667d88e7efff2.nq.gz
    ├── 234018ae0195813105405abc74e749d9aba7f336.nq.gz
    ├── 239c66a95024ad8734245ca449de681f5f903ac7.nq.gz
    ├── 249065f4be1327c3fcabd6abbb0c7218722cbb72.nq.gz
    ├── 24cdf78f96ad9d04079d8328dc124925dedaf9d7.nq.gz
    ├── 2530e4b7d5c4509532e3524f1a84ce40fa03f5c4.nq.gz
    ├── 255108dba9034d7120e97f34cad025888a8e62c9.nq.gz
    ├── 25876ab2f0cde425bf7da5277a0223263b7e4be7.nq.gz
    ├── 26f15831917ca1528c74ed17ea6e6eec4af7f91d.nq.gz
    ├── 275bdde4ab6d88fe763c56b082da12af000fd1f8.nq.gz
    ├── 285cb4f86e13a8ba91414faf8300ef4ac040db40.nq.gz
    ├── 29596547489c1c413459127ca91d32bd238e65d0.nq.gz
    ├── 2a047208b087b5f02ae6f9abaa380e01cfaa1268.nq.gz
    ├── 2a14a18f250c003bbd7d554339b8067d181fd547.nq.gz
    ├── 2a47313736ec069b61d010fe5100c29bc1787b35.nq.gz
    ├── 2a689575cdaba919d0cdd7f0f1301a071839f7fd.nq.gz
    ├── 2b136b041a83191a8c8f896fbbb628fa21409ac1.nq.gz
    ├── 2c3b26890138f72bf660b922b999e46640e3cb2a.nq.gz
    ├── 2c89fc67ea69c9b8367805ad1a9b7595fb4fbf30.nq.gz
    ├── 2d6a4381375f9cd101b9312b46ef2457a232f275.nq.gz
    ├── 2da1f46d0319f1a62c2896f09b334c9854be86cf.nq.gz
    ├── 2e119c3d407f068af8eec347c01822dfd2baa038.nq.gz
    ├── 2e421da3916e841c23410dfbacb41e58ec15108e.nq.gz
    ├── 2e4d310b2a7cdc3e915f6cad91b6b6ab7eacaf17.nq.gz
    ├── 2e735e575c0698e039d3da297cd2350d9c8fa1aa.nq.gz
    ├── 2ee425cd3a2d7460d75036866f5877659f9a10f8.nq.gz
    ├── 2f0557f1668bb8516108ed0d1ac33853a9cbf5e6.nq.gz
    ├── 313f2cd16472b5de87fc1b0321717a06685d91af.nq.gz
    ├── 319669066c8398c28f20ee16b0c1d6ba58329023.nq.gz
    ├── 326899e9dc5ab227f2a7b1ea5a6e6e572fe69aa3.nq.gz
    ├── 3311bebdc0525d6608ef5ea3c36839f3b48ae3db.nq.gz
    ├── 33e0156ccdf277e946ec1bc24988759bd6b9415c.nq.gz
    ├── 33e6767c13c1c08ddc11ae5d6c5a14563e97ccfd.nq.gz
    ├── 341dbbad484582b58b36b6eecefed6b8ccb5ffb8.nq.gz
    ├── 3421b7af862c02344059b384e531edba47370732.nq.gz
    ├── 34ac017a63a2b5c548039d3504da0270e2360a33.nq.gz
    ├── 35a031142b6d9b31d7f9646669e8f620f0c4ea3b.nq.gz
    ├── 35d7d5cdf87acf47788b0b79c74f03133bbd42fb.nq.gz
    ├── 3604a30463bfe95389a9d03ce8d943ef693e35be.nq.gz
    ├── 360523cd5eead34bbb7a2e9682b89f9238f7cf83.nq.gz
    ├── 36482f56d3dea3636c00e818ba7f39388492b3d0.nq.gz
    ├── 37038bc78eb6dce808c1d6570e6438c285362378.nq.gz
    ├── 3716a5b318715703da3a21f2dc5c5b3bc7bd9e58.nq.gz
    ├── 37bbac5fc8a063bc1c71204dc3b79fc724647a54.nq.gz
    ├── 37e5a461c4f384aa562c06a750960fe25997cacd.nq.gz
    ├── 383e0b8269fbfcea88f23dc8eccb52d020a083f7.nq.gz
    ├── 393b88ccfcc351507706dcfa3c9aff033c105084.nq.gz
    ├── 3950ce86af7b3b31b1a16cd4ca3b2d7e19626259.nq.gz
    ├── 39b6362824c808e91ae1ef34cda48ef2193a4a3d.nq.gz
    ├── 3a720c9a9af8ebdf437b706edd53ac18e1f6670d.nq.gz
    ├── 3ab07ef6f99e50cb66363448a5680a13a0037848.nq.gz
    ├── 3befae58700b707c2c633cb1e7b5e9c9d7a983a4.nq.gz
    ├── 3c2249a9f3109cb13b828b272c0f9ef9c963d6e3.nq.gz
    ├── 3c40b0d88d0702f249245527a23c1e5dd8b7ed69.nq.gz
    ├── 3cb1de6a7358096c99a4cc80ff36fb59174eb05a.nq.gz
    ├── 3cd546e458c1f409ab91e58647c05c3b745f27ab.nq.gz
    ├── 3d833770d733719153ad6c25ee9531aca0a0687f.nq.gz
    ├── 4319737c10a5a3f4aeff4bdd7995f1eb9bf0ca08.nq.gz
    ├── 448521c20b5aa3cea5e450972d74837d46965c22.nq.gz
    ├── 448b8234fb50ab76966e0a0e80149a8ff3f8adb0.nq.gz
    ├── 45641e57be5a86558b57391c6560a0f4e164ec5e.nq.gz
    ├── 46113d5c4ebc1b5252c75ae09f1aa4f4851704bd.nq.gz
    ├── 48368fa1489ad4a801a081129c52dd65bd39a876.nq.gz
    ├── 48fb15873fcdb6da0064d9dde4ee30d8dcf59a5c.nq.gz
    ├── 490aeb67cbf39de7498ad29790ff823a70118d6a.nq.gz
    ├── 4c09aa5cfe06e4e675e72e4fd15582ab73434e04.nq.gz
    ├── 4c411dea69db34cf344f1c3804f8a4fb31958e2e.nq.gz
    ├── 4c5c4ea0fac37adfd484870ffba31514e5586ef3.nq.gz
    ├── 4dd32c8481bdc2b1bf15b70ce80012466872b374.nq.gz
    ├── 4e7672274c9f8e7d3f452d98cab5ac153627c681.nq.gz
    ├── 4ecbb09485963abc7374b747216151d54ae8be21.nq.gz
    ├── 4f7fe88f46b034f94b75a59261c636f7d5b5616d.nq.gz
    ├── 4f8d35865a445daecc9c4c8b23c5f44e47b93e7e.nq.gz
    ├── 504ed2292afb8844d449bae6142b886998901edd.nq.gz
    ├── 50a82903775518db612274ff2f3696673316d1df.nq.gz
    ├── 513e4f71cadb7b8dcac7da3678dd84560e48c61c.nq.gz
    ├── 52244cb498657ed52585850f25e44f1bf32fea5e.nq.gz
    ├── 52c5aad79e0c08d1f0fcac5d2e8ee4ff49058da2.nq.gz
    ├── 54042d6bee601fa7c6d68d67d1fae6e23e6a8d67.nq.gz
    ├── 540a21584858d191f55e33f1299ad2910aeb3004.nq.gz
    ├── 544108fd28f1a3a5f750b188036269ba071cdf2e.nq.gz
    ├── 54b9a05442ea76db0365cc683d8e91f6f05a2da1.nq.gz
    ├── 54f47a809d33f2a1f69f5c94477d06ddb5f259a7.nq.gz
    ├── 54fa638c3b40fa3b69ea660ed01c019ddcc72b62.nq.gz
    ├── 55a3b9b28a0b04d658d38228fc039a780aedadf9.nq.gz
    ├── 55e0c12ea557e97e3f25b996ad6c1ee6f6c385d2.nq.gz
    ├── 562cd3b4bd8bbd8972ee62f18696523c00373e05.nq.gz
    ├── 5661a56ce493284fb1a1817b7d8257bfb8c33055.nq.gz
    ├── 5661d9ea5cbf8f8c88c610778428f490d419a021.nq.gz
    ├── 56e41e0c119e92c340191ed4df8a9540c3627f0a.nq.gz
    ├── 56f8d5e218785d08e94fb0ec5485bce93db3886d.nq.gz
    ├── 576e7504dca6178504756182934f5bcad58c5cbe.nq.gz
    ├── 57830669f9e87263359328d19b23d636f8fdd4aa.nq.gz
    ├── 580b6ef042de6e0eb0994e6ef30ce5e7b43afb1d.nq.gz
    ├── 58955ef60196fdfb6d41d427222b7c188695e074.nq.gz
    ├── 59eae897412968cfb8029ad65d23e673f1af07b5.nq.gz
    ├── 59f8bb92265299e86d90ea709f87b4bd1db285d2.nq.gz
    ├── 5a5e77c0bc9cbad39c58f8559c0622fc33cff4ba.nq.gz
    ├── 5bb086a66898f2c602741eff58817f72c64e5fb7.nq.gz
    ├── 5c352abec2275f62662bf1a9575b32adcbd95064.nq.gz
    ├── 5d09257226222fbc072650fcf5bcad04724342ed.nq.gz
    ├── 5d1226610ebc319462a230d4095e259cab68bcc5.nq.gz
    ├── 5d370637aad1eab35f883303fbd9f5a8fba5c691.nq.gz
    ├── 5dab46364057fa72902a8f84c672489eb58ec86f.nq.gz
    ├── 5df44e220caa011f4ac1b5ba01eb6a5da13cd2fc.nq.gz
    ├── 5e3bb259d7a2f165f24816d12a914482f0fe7fe4.nq.gz
    ├── 5f7ab0191c1eca9db6de03c48d8029517338b875.nq.gz
    ├── 5f8bb7eb55b27655bbed0d889d5753f29a1218aa.nq.gz
    ├── 5fad97080a648355520c6f945800a98e62d194e7.nq.gz
    ├── 5faf1eb3ec1b5ff490f1ca7688f4087ed88a1fce.nq.gz
    ├── 605841849ae4cd3690afaa7be05f3a6222083bc3.nq.gz
    ├── 613ef6e98e6ab889646e467ae074f26c7f83fb80.nq.gz
    ├── 6175bfbc33483fdb5d008154d0a41a9c79afeb52.nq.gz
    ├── 625c1016a78ae4711f4dcf5bc41f020335de14df.nq.gz
    ├── 63cbc36b2eebef6426f012130162a597e9d2fffc.nq.gz
    ├── 643fe2519e74bb638e382f7ae2416e234b8c5796.nq.gz
    ├── 646bab5be82d21fbe708cd6cd81a1e02af8daeb1.nq.gz
    ├── 64c0567e229f21073ea6a8f19a33c7f0e38b5b3a.nq.gz
    ├── 65bffc04b0d948522d4ebdf6be154aca27ccd9b0.nq.gz
    ├── 67635390d42590677748aedf4c55ac9136c82d95.nq.gz
    ├── 686b6438424f1a1d04648cae987c74dbe0aa7a06.nq.gz
    ├── 6a10cc045679d5d1ffef47baffec85c970306239.nq.gz
    ├── 6ae0f0f48ffac7649ee2bdc4e10c1c7a735f51ca.nq.gz
    ├── 6b812eade506a82d0af3807ddcfb853fa63d21de.nq.gz
    ├── 6ba265570400af28741f6cc52528c1f45c7be306.nq.gz
    ├── 6beda0973730d8bd95a8fbd59e226bb5f536154a.nq.gz
    ├── 6d4c8712caf71b7681497ccd776a453926a03e9b.nq.gz
    ├── 6e1818bc7a6b58b10a37fb1eb3060fde87ed4e49.nq.gz
    ├── 6f0a20472002815ee17bb3455547a7d4c17cc0b8.nq.gz
    ├── 6f1a3e1deebd39e24b3d230550362c90747d4a5f.nq.gz
    ├── 6f52b81b563d6317f97ed5c09b3e0d865870752b.nq.gz
    ├── 6f59c61260293458d968b061c107c96325d0003d.nq.gz
    ├── 6f632b1905d33e436134d045b5f8e9071178cc6c.nq.gz
    ├── 6fddc0dd44c20bdefd43afb442dd48e4c3593f1a.nq.gz
    ├── 71f41320a3ca0ff859c71d881b8c1e2f7288fe64.nq.gz
    ├── 72b8d7598d5c0f9d849f465351118906c4cda04b.nq.gz
    ├── 72c787a8808978e2e0ffd21b266374ccc4d914f4.nq.gz
    ├── 72c8d3d6a9b45b2ec7679dbcf2a694f4443814fd.nq.gz
    ├── 72eb2e7987617bfc3317b3d740a32b4f072e870e.nq.gz
    ├── 7337c94cd05ea37c3388d63c7a8b9b334967d0e9.nq.gz
    ├── 737c99a1205db1979d8694058429387f36dd0f84.nq.gz
    ├── 7382f7c5d497d6333463ebd55f0e87d3bb69e47c.nq.gz
    └── 73e8c359385ae3c6ee2c6f49d7fc7307ad29aff1.nq.gz

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

[chardet/chardet](https://github.com/chardet/chardet)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
