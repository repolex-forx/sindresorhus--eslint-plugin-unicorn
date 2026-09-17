# Repolex Knowledge Graph of sindresorhus/eslint-plugin-unicorn

RDF knowledge graph data for [sindresorhus/eslint-plugin-unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn), parsed by [repolex](https://repolex.ai).

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
lexq download sindresorhus/eslint-plugin-unicorn
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a3a10c4469907be047107cd31fd8a162f783a95
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9a3a10c4469907be047107cd31fd8a162f783a95.nq.gz
│   └── repolex
│       └── 9a3a10c4469907be047107cd31fd8a162f783a95
│           └── chunk-001.nq.gz
└── blob
    ├── 0039e41501514e618656d21ed65069ad83c81159.nq.gz
    ├── 00471800aae10a9bd271969e0267e39e264df8fb.nq.gz
    ├── 006404b69240f696d59f1e5fcff556ab099c595d.nq.gz
    ├── 007fc358c20fe9a865eb4124fe1e8f782cdfd9d7.nq.gz
    ├── 0099b93970e09ef0a6324bf091e5c08b5dad08ad.nq.gz
    ├── 01007acb592c964c28e0ae4bb856e06c31cebb1f.nq.gz
    ├── 0125dda37b5839adf7214a9ce036c33659bc4abd.nq.gz
    ├── 012ff7a65c4b11b0954886e85810dd91558d795f.nq.gz
    ├── 01d4a348918fe2844750bb9b754c5728269ba0d1.nq.gz
    ├── 02052715e6d3cc3348a68b0bc263f1556bbe8ddb.nq.gz
    ├── 022bd3d5884759a03f955156af34e0b753d36545.nq.gz
    ├── 026f6190f459055e85fd4989d0ee882cf0e60f42.nq.gz
    ├── 02ab0343b17dccbe7b2410a7e898d511351cad95.nq.gz
    ├── 02ccf708d12c138135923b63a2f86c170719feb2.nq.gz
    ├── 03212bf02ea771a8391f9434283eb8546b0e592f.nq.gz
    ├── 036338a495ecd44ff2fdd4f4dd376ca75702843c.nq.gz
    ├── 03f2d3a27fa83093cab0784945fd49b8825120f2.nq.gz
    ├── 03f4a516bf8143e482be58be3a4212b29fe9aa8c.nq.gz
    ├── 0409d868b131a05c93e37ac9ce540c670f1e3ff7.nq.gz
    ├── 047e0bd61efcffa2a6c571226ef28ad67852f41d.nq.gz
    ├── 0482d0d8fedb66fe7d292ced86e54b3ef480ecdc.nq.gz
    ├── 04dbd98ff17863840786799d891918a3970a2476.nq.gz
    ├── 04f7db3a03ec9f67d4f845ba4e6102cc22d17f2c.nq.gz
    ├── 0506ea2b48c61a1c2e8a13d15d1169228032ccab.nq.gz
    ├── 0588275e9fa4bae1acfa8b28aca097f69141a6e8.nq.gz
    ├── 0664aaf8d31669c15e3363ce8655789efff5b84f.nq.gz
    ├── 068e804c292412f37c6d6b4bc1e645641c9acf7f.nq.gz
    ├── 07082ac322321046b82b46a944740371419d8ed9.nq.gz
    ├── 0729412bc5040f4e0dacc49b46a4e79c935ea538.nq.gz
    ├── 076896d1ec2d9541932e2e465ada55c11cf5012f.nq.gz
    ├── 081e9496246a5b7b5403cc4bb5ecfbf240cfebb1.nq.gz
    ├── 088bdc58d1248150c58dc97885d2db48ea7d6b60.nq.gz
    ├── 08d7b6539ed10f9f08eddfad5308d8e7075c6304.nq.gz
    ├── 0901903edf78d42e6a3e4ae16a2b3b1e62250b14.nq.gz
    ├── 093b1a8ec44c72598e8d245145b2351dcb3e15ab.nq.gz
    ├── 09a4050220793faa454ff7bb48749e0c0c6b08d0.nq.gz
    ├── 09f7737fa8e1439779d2adb2a61891440ba9443b.nq.gz
    ├── 0a018714419c5335dc624ece81bb21787d6e43db.nq.gz
    ├── 0a2cb995e4e0cf5602502b2eec1c3d9746945850.nq.gz
    ├── 0ae9b22592f95dde661ce1c250c2076517ef485d.nq.gz
    ├── 0b00ebb9e4811ad4a52f166748b8371909a21fdd.nq.gz
    ├── 0c49838c3fc01e9b80ad6af94746a8fba75c2d35.nq.gz
    ├── 0c53b1431e02d9f958c0e579a698fcb15f74a9b5.nq.gz
    ├── 0d0d2bb6ae11ac916e7a6f5a00091e910a773da0.nq.gz
    ├── 0d1985addd8dc46ca672cc42009524a91e40a2cb.nq.gz
    ├── 0d8bf347855c49b6a6cb88dd7d1531c5cf168d22.nq.gz
    ├── 0d9721ecde581a42aca264d60277358f36c14150.nq.gz
    ├── 0db0d64ddad07b0859eb9821d2b192058bddbbd9.nq.gz
    ├── 0dd59fe657f9aa447e169bf26c0b084d1c905664.nq.gz
    ├── 0de8c51de941ca4bf94b61c974ce456bbd6d8772.nq.gz
    ├── 0e0bb9608592948d43f0a003dd3235aa36339447.nq.gz
    ├── 0e3ceec39bb0a14e8a611cd6e61fdc09bce54390.nq.gz
    ├── 0eaa100b5be18254e78bf7b943a7f380a410de6a.nq.gz
    ├── 0ec779e472d460762869c4b6f247d047a5b7cb33.nq.gz
    ├── 0edb16d77afc831ec23abd46d51d2944d0b8fc2f.nq.gz
    ├── 0fe97e7c5f36be5666c7c0c56127ac1810defeed.nq.gz
    ├── 10013075f95f6f1844593a28c2ef09c12c328ca5.nq.gz
    ├── 107649dfa7fbf081078956e3a8f71781308b7dd9.nq.gz
    ├── 109ccb6f9dcdc1838531776dbdd99a41fcda2b1a.nq.gz
    ├── 10ac92db457d8a3a7636ebaf743d8c702c09d83b.nq.gz
    ├── 10e09e1a15dbc48ae1cb8328d34e95b48c5d8a89.nq.gz
    ├── 10e5333e6dd22e808a6aaeb9c80e5e0fe5a1e37a.nq.gz
    ├── 10eacff42f4d0aa890daa5f5860111fac775c0aa.nq.gz
    ├── 10fa2a5dcd7ce8cea8e902e4656be7bd9196ce3b.nq.gz
    ├── 112c5a48262f8e4bd59f44ceefeff3136bc8311b.nq.gz
    ├── 1172f0dc3108714f76f421877b67ea025ceb1f05.nq.gz
    ├── 118d9f226fe7c9ad02f2021a538f1bebab9ebc4b.nq.gz
    ├── 11d6fe94dc169ba14f6d5f8927067bb966cec639.nq.gz
    ├── 125552f8cd3379e78bea14a676c2956937994aee.nq.gz
    ├── 127aecb7dc277b34441cb07a8c9b35e79ecad732.nq.gz
    ├── 129d546ce52c83f31a7c8c7924bf195bf0ba74a9.nq.gz
    ├── 12e06a44ccdef1cc35ef526343a4daaef226f16c.nq.gz
    ├── 1307d47755c0b4174e6c33d59d5e20b1725ea694.nq.gz
    ├── 13f5476298dd1316c833310d6774e4d071fa14e2.nq.gz
    ├── 1422cf4d167622978b9e97b1b1578966233beda9.nq.gz
    ├── 145d81b668357608f49e0b02a98fd1f71dedd85b.nq.gz
    ├── 14dbe63e1268d70b3f29178c2a5c57adf69835f4.nq.gz
    ├── 15621a8a42fa463ad972415a676bf7c51a292dcf.nq.gz
    ├── 158e334a7730eb68d124e76a98d66922de4cfa81.nq.gz
    ├── 1590cbe9ac95ebeecb6a27c18271ce9091970b02.nq.gz
    ├── 16018a2637da910cecb72cbc5e7b3d1305b708d0.nq.gz
    ├── 166ab1482cc07f8845de20f5cbe4d5c75ff1970a.nq.gz
    ├── 171888df2e0c70452c32ad679206bf121c78b7bc.nq.gz
    ├── 175facc82778e0c8fc5fb553a0d794fe854b4b57.nq.gz
    ├── 17612a0fa39d568bfa231be8e5e7f13e03d81ec9.nq.gz
    ├── 17a13a382c76eaa56db5c9998def769f67584b8b.nq.gz
    ├── 17d515a0e937e2db26b7f410d0c31c4babe8ede3.nq.gz
    ├── 183f095984e0a13b4bec7dd6f2f19d3b9cff0191.nq.gz
    ├── 1856cb48a00e486052a377da8a3a6196259fa6f5.nq.gz
    ├── 186f6347937d4fc6b48a2bef25b9a92956605a80.nq.gz
    ├── 18aadcd69fc22f00ae507b237c0ebe27efe8b559.nq.gz
    ├── 18c187a31febe3dcf2ec574ed09881d615527fa3.nq.gz
    ├── 18d331f9caeed8d24652cf92ee65103cb4666421.nq.gz
    ├── 192665c96a5176013708bb62956bcd0b71d7bd95.nq.gz
    ├── 197d1cdf88caef22da11499e515c1bf819e6fc87.nq.gz
    ├── 19b3d5df0e12fa82eb66524dfd3875b3afef7cf2.nq.gz
    ├── 19bb2c9ee3d890793056d317375277d2fcbf03f4.nq.gz
    ├── 19eab374404faa2b96265ab79f7319205e86db26.nq.gz
    ├── 1a00db83d2c15063c362df7cf91e180261af0cdf.nq.gz
    ├── 1a0f8e221743b3bf7d8e0d10fec9e014833cdbab.nq.gz
    ├── 1a1627131940e1ce6208715f1161fd559672c5bf.nq.gz
    ├── 1a5c73b3a90749915c1053f5c88cd270b817ce23.nq.gz
    ├── 1aa035b61f15eae299e691eb03750aa3c12fc41f.nq.gz
    ├── 1ab7aaffbcff56ce368253d8665f926b89de5bab.nq.gz
    ├── 1ae41ef13240d0574a726d899b14fe3d0f5400ec.nq.gz
    ├── 1b0e28f96d77e34210f6070895ed3f01a3a58de2.nq.gz
    ├── 1b5ae3b4cbdc7a8d7ac25edc6e757740074ff0af.nq.gz
    ├── 1b69f469accb8bb80d72621d0a662389e361201c.nq.gz
    ├── 1be885f8a3f736a1d8c44005361a4b1bd8e4dfb5.nq.gz
    ├── 1c29a01549b678f34e2b9e91b51c2b1e5699a034.nq.gz
    ├── 1c345ba270728e0b687ea45ee201d36b8f3096a1.nq.gz
    ├── 1c6314a31833395fd5ff016a6506bdd51860657c.nq.gz
    ├── 1cca49768fafcefa6056e9c056b03b7206e5795d.nq.gz
    ├── 1d77fb8abc82fc59e9c01b688d692c0c44bd3427.nq.gz
    ├── 1de2bf7bc3f1ac95f3e925e57ce5ccd8226b02b9.nq.gz
    ├── 1dfc898fac35b3fd6b553a2b5d24803b05c554bd.nq.gz
    ├── 1e19c112bd05766436114346a07bda22c144bd18.nq.gz
    ├── 1eddfcb61a4f954c8c53fa6b87a54ad26622c108.nq.gz
    ├── 1f8b5ce1eb8ac8a3f6d78b8bd55a54aca98bf80f.nq.gz
    ├── 1f98f1e6606fdc8ae4906a6b4b0f696d4d351b0f.nq.gz
    ├── 1fa944e43340b79872af269645fd9b2cc0d8fdfc.nq.gz
    ├── 201ebb0c13094ad7cfd2854092447b1a60b0f865.nq.gz
    ├── 208ab8b5e5336ef5d56f03743e5af675409737e0.nq.gz
    ├── 211c625e57b01c0559eeb86178b8cd64cf765c7a.nq.gz
    ├── 216f75eee44a32dc94c1e23d12121e4142e0845e.nq.gz
    ├── 2258f404271a0157dc19a9176fd994ef3d81f6f9.nq.gz
    ├── 2267c2ca3fc5eb14a78c39823f3bfaab3509670e.nq.gz
    ├── 22d87990e18cd03f15d04d6bcdb788f16c6a95bc.nq.gz
    ├── 23097f411064cf2ad5d73d3ccc8c1aa70568922a.nq.gz
    ├── 23c2bc18a7a46f86f820a2778e68dd5000f1b227.nq.gz
    ├── 245563f42ebebe7e780535ba57b3ee02482f5ad4.nq.gz
    ├── 24701ff173fd5a6b917119ea0dfea46b22147c56.nq.gz
    ├── 247707a90683ecf68b9368dcbd643b350fdafbe2.nq.gz
    ├── 24bf8b6b286d17f809bc1cfe4f9edb486be716db.nq.gz
    ├── 24c1acdd5d38de49f1ac79089508e5d6d2d77d67.nq.gz
    ├── 24ca85851f823c42c490ba1c9c185576bce1804a.nq.gz
    ├── 25380760d3fad7950a3045413bda36ea2dc7d723.nq.gz
    ├── 2567756b707a4f0b830f1cbd973779b6265a2c51.nq.gz
    ├── 258175232025cf9c26f024e4ae9409d5a459d968.nq.gz
    ├── 25a590d04263ec85a586c42a55997ba69c5983e4.nq.gz
    ├── 25b960d2d8f0da8f50212a7eb3d7778826b496b5.nq.gz
    ├── 25c527cfb013432fb200bfa40978a8486182ef19.nq.gz
    ├── 262df262a27caeb9ae68694333731379663891f8.nq.gz
    ├── 26c58a5ee6dee078d04f3ac1e01d1419fdfe5ad6.nq.gz
    ├── 2752fac66049f6427fa4ee1e9c4e29f06de693b4.nq.gz
    ├── 2781656fcd7963b0f06dbc74e961c3f6e156c158.nq.gz
    ├── 27b5acf25c861ca5145effc4f56ab2098a231034.nq.gz
    ├── 27c8012f1aaa6ee267d703f749d732f16cdd898b.nq.gz
    ├── 27fd8a28538d63c39e00177220103af53c1bfffb.nq.gz
    ├── 280378d2da44220a350404c946929047dfdce72c.nq.gz
    ├── 2822cfef98930d22775415a1f6308ff9879b3aa4.nq.gz
    ├── 28ea777fc0a27d2fea61b04c5e572f6e5bdbc3a3.nq.gz
    ├── 28f51a16884f5faf05f353f22cef900b25dda63a.nq.gz
    ├── 291ef6a859dc0a16adae6e2ae39aa2f382c23bdc.nq.gz
    ├── 292196e9852a1e488579fbd85f8105785cfbf52b.nq.gz
    ├── 296311ee0bde416f516d54587eb0ab2e042f862b.nq.gz
    ├── 29c98df9218d7eb0503a674e58fa4adea7dd1e10.nq.gz
    ├── 29e81364d40638d9a83e5565f196e7fce5099304.nq.gz
    ├── 29f2880a12cb434aa4f1c51d8737f8093457eacd.nq.gz
    ├── 29f5cff9effd9dc0361dd9488d383e60919916ac.nq.gz
    ├── 2a1ec835226cc61538067fdc7cddf3ca02c3a4dc.nq.gz
    ├── 2a4ba6185fb38b2258e97213b5070416de6f74de.nq.gz
    ├── 2aac6ebb244d0b8e1883298d267a2245433f88ad.nq.gz
    ├── 2abde902090b72cd4e5de1a112b96fc295df23ca.nq.gz
    ├── 2aef4fe2e5527d1e904d3445cda3ce654a7f59d6.nq.gz
    ├── 2b4c5a88faf3b73044a900e495ca36b733cb878a.nq.gz
    ├── 2b858ea396bb5e459cf173910cf0dab3ec8938b3.nq.gz
    ├── 2ba13580eb50786b0decede2bbb9e04728799af1.nq.gz
    ├── 2ce7e151112b0648d328f5069fdef3c75632cff0.nq.gz
    ├── 2d0dcedf8b8412193f003722bdc05208c3eb6c1c.nq.gz
    ├── 2dbd0cb8e4b650b2c5aef90d2bcecb950869d0a8.nq.gz
    ├── 2e5911400c26f94040a9f4adf9d97a9cf2040b08.nq.gz
    ├── 2e7db46d3bf2c0976f469b26345cb7084c145a6b.nq.gz
    ├── 2e8faf9e84883a85f036357440a8820bfa570915.nq.gz
    ├── 2eff17680b888d668ba7114f543200aeaaa41295.nq.gz
    ├── 2f1b2664a082001501f819e6ad537fffc1f07ae9.nq.gz
    ├── 2f353da79a49bf35adc390cfe75a906759fed603.nq.gz
    ├── 2f9c06f9da7ce44fa985308e92e413df25eccd94.nq.gz
    ├── 2fc41395db81d8be24a6bdd1f8e4f4c13cd1297f.nq.gz
    ├── 2fe4ede184d6dc11023d6315d72fc6e7d76c1b7e.nq.gz
    ├── 2ff1b84518c55b910b2643d9096bf2fa38dbe8f4.nq.gz
    ├── 2ff4e8b567b3682adafe46d12ca0a595977e4b9e.nq.gz
    ├── 301101dcf5f72d51a3bcd289861f62c4694f5a95.nq.gz
    ├── 302db4ad90dde4c614347d79cabfe735dcc32104.nq.gz
    ├── 30b45110a1d8eff9c2b42f06ecd366ae648ce00a.nq.gz
    ├── 314212be1957e4c9f0b40d026e0496eadafe4485.nq.gz
    ├── 315b5affd3c217369434b07dc0bf5d3ec9b5eb02.nq.gz
    ├── 31dad2b84d53bb07ec5d49daf217e52341342e39.nq.gz
    ├── 32904fa9c7685d79a7be656db09c40f183c8aea9.nq.gz
    ├── 32f225c35294b4bea658806e854c9e413e08c3f8.nq.gz
    ├── 331a9bec14cc8f14ec95fdf26ce075bba666ed28.nq.gz
    ├── 334ce53ba511e32358f97a1afff2624835029478.nq.gz
    ├── 338e3dbde89c1d624c5694d5757d27254fd6353e.nq.gz
    ├── 33b0c8df95beed9df562c82ddb458e6da3443a3d.nq.gz
    ├── 341394b76aa49da63b04b50caa048181d4bac4f6.nq.gz
    ├── 3442408513c54cfc2f6cd12853aebb6696aa44e2.nq.gz
    └── 34d2d74ece092d5ebedf96661edcf406f721b600.nq.gz

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

[sindresorhus/eslint-plugin-unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
