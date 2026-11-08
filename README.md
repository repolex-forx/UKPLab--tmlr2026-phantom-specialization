# Repolex Knowledge Graph of UKPLab/tmlr2026-phantom-specialization

RDF knowledge graph data for [UKPLab/tmlr2026-phantom-specialization](https://github.com/UKPLab/tmlr2026-phantom-specialization), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/tmlr2026-phantom-specialization
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1db9d331b02a7bc30fd9d5cfd3bf446f28a3d58f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1db9d331b02a7bc30fd9d5cfd3bf446f28a3d58f
│           └── chunk-001.nq.gz
└── blob
    ├── 0024c2a05bae08aec181fa899f71c51f8ca6653e.nq.gz
    ├── 0145d1ee5068976c0ca51eb251f13ce45635ffc0.nq.gz
    ├── 02594e8fddcbbc2be49696e1a8990f5f736e4b7f.nq.gz
    ├── 0300b667cb007187af24e849c36da7437a7f0ff7.nq.gz
    ├── 038176d43cb1f5be2ccdcbc543464b51fa85627a.nq.gz
    ├── 044af22a2a2ddc4db8fb4b475a82dcefb2618a1d.nq.gz
    ├── 056af4c9f26ed6328bb73730d3109f371e8a6b07.nq.gz
    ├── 06f1c4b0a221c65587b5d6b15f51cdce72ae27c0.nq.gz
    ├── 0780f6756f2ba762b626bf5308783a672cfe70c3.nq.gz
    ├── 07ca412df33f376128a981fbd7e47f58dc3a9ba7.nq.gz
    ├── 07f09b1534fb3f06c03335038e2946c218d53efe.nq.gz
    ├── 091c671b5ac2de3030f8e0e2377499eeba46a471.nq.gz
    ├── 09fd1867a17dfbae4bf9aa58865d4690597ff3b6.nq.gz
    ├── 0a3ef66991aa86dfb373e83cc6926be692485572.nq.gz
    ├── 0a69690275ad209557eb72b084370674f6178c77.nq.gz
    ├── 0a988684c1da9c0859f95e6f837212d68d4f4e86.nq.gz
    ├── 0ae11610e5ec306db5922de32f29e5ff5bc3f812.nq.gz
    ├── 0b610a5b93f61c0c8b99fe65252954c9eee38894.nq.gz
    ├── 0c92a7a03d55a46323be116fd92e6a661b7e4d8d.nq.gz
    ├── 0d500b49d58dfe21aadd8a7311a1be6c5fe68fb4.nq.gz
    ├── 0dbab329da25ef5db8a4738883023b81a2710e2d.nq.gz
    ├── 0e36aeea07df4d581fdb7bc540ef322517aec230.nq.gz
    ├── 0e737fc6950599479fdc38755e723043db7dac0b.nq.gz
    ├── 0e8a583b09c49696aa9198ec494c2d20a01dffd2.nq.gz
    ├── 0eb19d8d78d1150a60e2a0ac682aa4bbeaf593e7.nq.gz
    ├── 0f22d3c2045d7d241a4ebdcbe1aa88066f97b7c5.nq.gz
    ├── 10088723a25b57f92335294abc8e3a13fee900ab.nq.gz
    ├── 113b501a57a0d6e70a8ac01c5b123e98b52cf251.nq.gz
    ├── 1164ef3bb0c68f2faaca05396a3c6f008a251882.nq.gz
    ├── 11be2017fc29ceef0273593aad8cda3efdb077b6.nq.gz
    ├── 11dbf0f549022d6cc95447f2a85be7b5eeaaeec3.nq.gz
    ├── 11ea8e8e01aa5d8b35d8c345d617bf693df82ee8.nq.gz
    ├── 11f520dd240d018d1ac292010fa3b0c97f91be54.nq.gz
    ├── 122d858c6eee08b65566bba471c0f0559086a78b.nq.gz
    ├── 12bddf360b409ef783bf2b0ca90e49d4966b6d1b.nq.gz
    ├── 13d519034e1064be789e0274f37024b399db1e07.nq.gz
    ├── 13f9caf2e087d27aa4d1ae507f743bac952fef92.nq.gz
    ├── 14107afa9f9065fe2cee8d0b8cf895df6527e7df.nq.gz
    ├── 14aba0b30ec8b22ba9c49c15215229fc398cf56a.nq.gz
    ├── 156a676c02ad24da067ad7ec869596ed717b59f4.nq.gz
    ├── 156e54a760468b5ce95ec23a0e629a30376cedfc.nq.gz
    ├── 15b63f8260b1ea54184649ae51f778d8686af5f9.nq.gz
    ├── 15c48c451b0f096c202e637aa004ade42c7b18dd.nq.gz
    ├── 15f7b5889af08c342f13ccb9d5d8cbdd2765a603.nq.gz
    ├── 1612a775b0ee58b382754d786b8f33b53bd9a568.nq.gz
    ├── 169e589a6e2dd6ce2dbeb7e13ef3ba4041ebf7ea.nq.gz
    ├── 17f3267bb931f5ad9ebf8c4827d7adc8f66e13f4.nq.gz
    ├── 18ccec488ce13783467aac5811dfff58a7e818a8.nq.gz
    ├── 19b2ca36a1148145636b0d21bdb40e4d36a35747.nq.gz
    ├── 19f0f35d86857999b64ebb1da2c746e179630c9f.nq.gz
    ├── 1a438dc9d18863a2fda8f42b6cc8b24af12dcff2.nq.gz
    ├── 1ac57ce6e483c658253548fd242ccd323b851dee.nq.gz
    ├── 1cc8dd623bb8cbe536c604aa3a6eaf74a209fc14.nq.gz
    ├── 1dd4cfeab5299ce38b122edcf6d0780e5523a626.nq.gz
    ├── 1ef4c40fb8bf6a598357f1cb65acf349f5faa21e.nq.gz
    ├── 1efe6bcda2ea731efb6955fac207ee19a8f04942.nq.gz
    ├── 20b252d520a69ed82b74be5ce38c788e1ba1e6a4.nq.gz
    ├── 217ab06556bf76025c7e73ac0d4500b0930d3c47.nq.gz
    ├── 222d802f811ecab4a3dbde213c98e4bc91e12d8a.nq.gz
    ├── 2265e763544e31db4b8aaf3d9a474f89cf6c13f3.nq.gz
    ├── 2296d1af91af250a9303854f30484ee075f8ca07.nq.gz
    ├── 22d150ddc1ab80756f240c4f98e31809ff67b803.nq.gz
    ├── 22e2938af21b971a7eb9b67b05d75f12949054a6.nq.gz
    ├── 233a04921db170363dadddcbe25fb642326467e0.nq.gz
    ├── 23954778145aa532f986bbbcd1110bcc705d9de7.nq.gz
    ├── 2479fd209a54a33a589f0d61b4f1f5de0866f7e9.nq.gz
    ├── 2488e6085494127b806be370ee39ef1e06c8570b.nq.gz
    ├── 248e6e027c511cabc608a9746a201019ec5873a0.nq.gz
    ├── 24fd8582420306b5f815e6e9abe9e3416241b90e.nq.gz
    ├── 25588489797fee29d802a8802e9e8fc0851d471a.nq.gz
    ├── 25c820c5235dcbc8ceb7032fa8aedf21e0633bc1.nq.gz
    ├── 25d51251214a2637a6e62448203b31b144e9ad2d.nq.gz
    ├── 260eca52776514b90e37441ee9a7c6d44b0fb6e5.nq.gz
    ├── 264223a85af82908fab80e0f1ed0561df60b65f5.nq.gz
    ├── 2753ee1df6f6759bf8d720c9c0f2bc2a8694541a.nq.gz
    ├── 2759ea973538014e32b249fdcf5e9b181d0dac82.nq.gz
    ├── 27df277adf09a7b7e7537b8b4bbaaaf2969d3e30.nq.gz
    ├── 28188402af3c7cf05ad4458cec6f637cb3290bcb.nq.gz
    ├── 2853ac04c46f6b9f84b90a58331307e1b9e6b2d4.nq.gz
    ├── 28a734fc3a63f66afacdc0b733aa0165cd7dd0cf.nq.gz
    ├── 28f808e40e0468e5d1607bf1480a4099ade9e701.nq.gz
    ├── 2a0854899312dd8b190e1f813eb5e2cf56db7631.nq.gz
    ├── 2a253f7f801b9eb496a166ba91afa66c171ec806.nq.gz
    ├── 2ace2c72d37aed4c2bfced382d5e0cc0c902c57c.nq.gz
    ├── 2b439b3cfdf5677296650976bd63c73edcc2424d.nq.gz
    ├── 2bcabd5f80651ac17c20e394137d8525dd1c1cc3.nq.gz
    ├── 2cc1cc4552d4554ea23d06a30d4dac3e6315a219.nq.gz
    ├── 2ce6e256c27b97d95b4c7c67c05ed3cbdda61bdb.nq.gz
    ├── 2d7f415523637eaee4fdababc549eff1d5868819.nq.gz
    ├── 2d8821bc0663ba5406c3074019c5ca2a34918baf.nq.gz
    ├── 2e5af66eafeae60f1ab99e86f0bc703bad003f23.nq.gz
    ├── 2fc5e337e4bdc77e7b500abd139d1c9dc1286630.nq.gz
    ├── 2fe918f1d5587394aef9633f9eabb907b61718f0.nq.gz
    ├── 3037e550888604ce9e7dc8640b1eeb8cced670a9.nq.gz
    ├── 306bf6fb4baece95f94d2f86a2460f691f5efed0.nq.gz
    ├── 307e0a0d1136e658e7680ef2ae3a7c429ed59228.nq.gz
    ├── 3098bd6766f51d3e4162ef093389e5c9ecfaae56.nq.gz
    ├── 30c1b64e3db9a4f95176197669a6a3eee9e8977c.nq.gz
    ├── 30e4f9e9e3b34c55f0061b957612c11a4e71ebbf.nq.gz
    ├── 3126a5f6b7687d73c33ffd60488adac0f993ac13.nq.gz
    ├── 3191cc25864b1c0beb7c5db4eb935f6fc4b9f7f2.nq.gz
    ├── 3196a067eef4c513f80dcaf799e45ec4176d8454.nq.gz
    ├── 31b1fb892c4d6964ccb940481b24a0cd54d8c26d.nq.gz
    ├── 3281312e15d8c09dfec886159788678a06f51ce1.nq.gz
    ├── 3290812071371d2b98ced10c6f22e37d661ddd4e.nq.gz
    ├── 32967a96c7332fac5ed4cc25be7df3b93bcc788a.nq.gz
    ├── 32b3cc3dd5bbac0ebdaa8a4bd0dfbc6e316c9742.nq.gz
    ├── 337536bf65d40a9cd8c83e4474e4baa43ddf0ced.nq.gz
    ├── 33a25f501fd880d958a27d39bf177c8c301d4687.nq.gz
    ├── 348b41ffd9c035cea7497ce7456881cfde77a594.nq.gz
    ├── 348d73538cb56d07d5a232599f049b42e39dd3d2.nq.gz
    ├── 34e22aa222f6b1577b5d2251d9e1991d3ba3dd60.nq.gz
    ├── 3527c981a24e5749e8ffa07d4634e40b950bc19c.nq.gz
    ├── 35645c991dd32e8abbefed76e14177be776a5f87.nq.gz
    ├── 367d84faf2ad9463a3de17e33e2793550d308021.nq.gz
    ├── 3756c677a75dae2b201aacd5c9325f1e4de76303.nq.gz
    ├── 382dd0af6bde8bb5c7b08a4c93f204dfbd820934.nq.gz
    ├── 387f97de127e7aae762b84be8b44a4e7baa7df0a.nq.gz
    ├── 398d0624c88cca6f2148240ef41a032993025906.nq.gz
    ├── 39e4712053ca1081c73cd4b649574e5b900bceb4.nq.gz
    ├── 3a9e5f9959f49e85271a91cdeeb1bb1177584a42.nq.gz
    ├── 3aa394300b57920bf106fed3d8a6435971574f88.nq.gz
    ├── 3b0f2e1c0b17b1181da2675dd75c768a02bb4566.nq.gz
    ├── 3bd16e317642f7efafd70d77da4ae8fed34976ca.nq.gz
    ├── 3c2552e40755d2715b940620a991af6783c96f09.nq.gz
    ├── 3ca4db7363a856fab266644aa78415e639cc6438.nq.gz
    ├── 3e11421528ebdca9d7a2838a921ac0eb8745f721.nq.gz
    ├── 3e8a625a213e9d4f9539c98ec896a8b1b583b36b.nq.gz
    ├── 3ee7684927bb00bbfe2b79b14ccff5f0cac32e17.nq.gz
    ├── 3f2f2d92644c35eed253142d74f32961b3e2579f.nq.gz
    ├── 40b6b0aae9e9eee69da71a13040a9d338240ced2.nq.gz
    ├── 410265f3a23842231fc24f3d5afffd994e4495d8.nq.gz
    ├── 41632ff7a5d3cabafc1075edb2f7f25bb2f15b20.nq.gz
    ├── 4190df652315300ee9e28cc15561cae940708cad.nq.gz
    ├── 41b925e6c21898f7452c71666102d27834221d46.nq.gz
    ├── 41bff8f2a77551668befe906e1d9103c862f9b99.nq.gz
    ├── 41d691c7ded08291516339455c4e78dce7579007.nq.gz
    ├── 423dc7522096c0b272a946a720802dcb0f7419b1.nq.gz
    ├── 42dfeba16a9c5c7ddc6683522a55fa33917bea6e.nq.gz
    ├── 42f207ef7d6819242464449b645fa488d0c12598.nq.gz
    ├── 42f8061060699e4be0f0b4f149e3362d2ec2da2b.nq.gz
    ├── 430f721984dd452cfc462ae6dba1a52e4f6900fc.nq.gz
    ├── 43b30452b8657636e000eae02c22e5f02c9d9ccd.nq.gz
    ├── 441d77facd909bda564abab73bd3a2861525e5a6.nq.gz
    ├── 45c76d1aa98051939687eaaad03cb9bfd459f8cd.nq.gz
    ├── 45d288b48cfbc9f4c7aeae7377c6177e024d7a3e.nq.gz
    ├── 471c4bac16556e0e5b5a7fbdd2ae09cdb92fb5ce.nq.gz
    ├── 48b1d3cbf5c4eeeb7e4a325634cdb83935655303.nq.gz
    ├── 491576a9f53b40fd2d1b10004488760583216b8c.nq.gz
    ├── 497c870d90f7d9b4c29972eb6f6389daa3a70a7e.nq.gz
    ├── 49d0d567e1680825ba48a158ed88e6c6cb3fee48.nq.gz
    ├── 49ecd76add2557039d72d6a5369a3dd02fc59da8.nq.gz
    ├── 4ae8aa69342e7920ce984016aab651928b93a107.nq.gz
    ├── 4b1dea1ce01dc7eabf5dfc20587274a9c80b4685.nq.gz
    ├── 4b294ce65df593f3aa6241026d5d66669b41fbc7.nq.gz
    ├── 4b5bd0119110e837512533e0c21e6aeea8c179a8.nq.gz
    ├── 4b6b11f1e6e676ed0cee0f79757ecad1a9358d7d.nq.gz
    ├── 4b90ccc4001ffe726558ab1eeb70e8d7477c260c.nq.gz
    ├── 4bc4ea652470a0531ea91a09dacd180c97d0a98d.nq.gz
    ├── 4bc9d7493509527146bccab3acfc16b9c5242f4b.nq.gz
    ├── 4bd1421613065ee5de42399ed28c8956088f36a8.nq.gz
    ├── 4c56eb79d057474501c7e26a461535891af794da.nq.gz
    ├── 4c6efeb7d69fe2f61633495f7201c360c437197c.nq.gz
    ├── 4cdb1fdb1833ec73ee5a389bf22b0d8755719563.nq.gz
    ├── 4d74c54abcf787a5031891bbaa0bcc49a8cdfc91.nq.gz
    ├── 4db16f9a2c453fcea7a3d497bae16dc67dc60e24.nq.gz
    ├── 4df54904800a6e5099c236f329f8561000af5526.nq.gz
    ├── 4dfeb9c92c5e10678ef1c297ae27afc17d34cfd2.nq.gz
    ├── 4e2d0782928c48b8c2345e4b87737ab91240d83e.nq.gz
    ├── 4e843b8095683b9dfe21cba10267c6437af20bbe.nq.gz
    ├── 4f30e82853a3017d8e667249c664898a96106c4c.nq.gz
    ├── 4fe2fae35cf8dc79309c27f45de022ab5a4bb05e.nq.gz
    ├── 505418825605459c37fa13cd601fe4eecd259abc.nq.gz
    ├── 519f5cc353a2e2b948b0e89c2c6fb4c85a386d1e.nq.gz
    ├── 528b0064430a82e30cb134573ee05e8a2986481c.nq.gz
    ├── 52afe2197bd5228859ddde16f0ffb3a29445ce46.nq.gz
    ├── 52b0a2f890414f5ed5f78bf958c493692fb6e924.nq.gz
    ├── 52d708f8976e627eb3a3398d34a109ea7d138f35.nq.gz
    ├── 53650e8d1a9659dbee64c4018679997085cb9a25.nq.gz
    ├── 54268406b27ec7f9cd2a326201b9e5087f6f1651.nq.gz
    ├── 544225c73df3aeeb110814deabffdc9deef27a9c.nq.gz
    ├── 549f858a6746b92a19ebd3a65d7225c9a5498330.nq.gz
    ├── 55536824110ae13f9caf216147f908bbb2b582e8.nq.gz
    ├── 55d3d3f910ba96b3ee0a9406828697d8acd10d99.nq.gz
    ├── 56bf0c214c3e82129c713b1f6c4c6db619db3ec9.nq.gz
    ├── 579067ffa7a2df7b4f97cf26cc55655cbf882615.nq.gz
    ├── 5900ab495f21dcefe60e648070b428c2b0ddfb27.nq.gz
    ├── 5a5d18e73dcd867177ee97604ca645c354cf71cc.nq.gz
    ├── 5b07c1bb3a8c66703911d2d1fcf4a31753f823a8.nq.gz
    ├── 5b7e83c87a85a3aaf7ccb0957e1871f738c36b09.nq.gz
    ├── 5d4d8076f6bc5f9c56dd7eb2570bd91f9d9afb24.nq.gz
    ├── 5e192b69daf2d1fae90ce9a0ad7d480818775437.nq.gz
    ├── 5e357306c3a5760fec5c4f2e310cbfd03109f8b0.nq.gz
    ├── 5f24c673637bcfdb78958db165f563b0487467ee.nq.gz
    ├── 5faced43d737621902ceb8f874bd7948b62ff841.nq.gz
    ├── 5fb71637baae9fe7d18a435125db7009052e4f1c.nq.gz
    ├── 605197db9fb62bba3f7534398b55ad241d9d2a69.nq.gz
    └── 617f6d012c9fcc6c144352d244456fc6f7578640.nq.gz

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

[UKPLab/tmlr2026-phantom-specialization](https://github.com/UKPLab/tmlr2026-phantom-specialization)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
