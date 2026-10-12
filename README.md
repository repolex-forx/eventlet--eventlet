# Repolex Knowledge Graph of eventlet/eventlet

RDF knowledge graph data for [eventlet/eventlet](https://github.com/eventlet/eventlet), parsed by [repolex](https://repolex.ai).

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
rlex download eventlet/eventlet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d0111a51ce7e9f035bd3a793219d0ba9a07cdba3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d0111a51ce7e9f035bd3a793219d0ba9a07cdba3
│           └── chunk-001.nq.gz
└── blob
    ├── 013e77de00736f91ad6e47602bfac296110286c6.nq.gz
    ├── 0317d50ad5f19a607337c69e023c1bfc687e2bae.nq.gz
    ├── 0394ca5d534616bd866c94df0d37b8110bbc9bb5.nq.gz
    ├── 03c2ddcc738065f270ddf99ef43081816d12ef96.nq.gz
    ├── 043ba83b5b405c64c269f0cfcbcf7314f355ddf3.nq.gz
    ├── 051cc0f3baa3fa48bdf4ed7746d054d5e8960fbc.nq.gz
    ├── 05668a41bdc17759b63d301f520764f342d15415.nq.gz
    ├── 05b39e3f5ac88d20b545842f11be60c06b3b864b.nq.gz
    ├── 066fc393b13af7944faf486a0530e15a4f98102b.nq.gz
    ├── 074614941d49f2f07400429c6b4d64861e78c900.nq.gz
    ├── 076e6a2ac58c4bbac9ae877d045fd99fb32f4c8e.nq.gz
    ├── 0787ca8e704f7f86e68af7fc6cca1548613b9313.nq.gz
    ├── 0802243ca8c221af5417be11d9fb976f7d02ba09.nq.gz
    ├── 098421424598dc5414a3e6501a68b26fef8a7592.nq.gz
    ├── 0a57f6fe77ce2393e5a8b9c3aa9686c63c332ff4.nq.gz
    ├── 0a974f34c8a031953261d8b355ad23d249341718.nq.gz
    ├── 0ae0cc76f82f50f8b46e54d3759ddd8a998f486a.nq.gz
    ├── 0bc19c10ade8bbf770f963d9b8bbb901ec5ef72a.nq.gz
    ├── 0bf031f178ae5a3089aa3acfe89a8a02c68f8a9e.nq.gz
    ├── 0e08e922dcf6d9b588112a77379f352030351c1a.nq.gz
    ├── 0f595c2502798be61e331ac6d90ae820c010bc49.nq.gz
    ├── 0fbe30ec83ced1b8f503c7a299862e946502fe4d.nq.gz
    ├── 10fe275759e52285bfead0999a211fbfc8ca23b7.nq.gz
    ├── 1108adaf689094fc894bb1aa83ff0b76c69bc6ce.nq.gz
    ├── 122bd5dd859933442af3c2b3751841c850ee45e4.nq.gz
    ├── 124d0728d40f9f18b37d38ea4a2f733e47fb3e52.nq.gz
    ├── 13cbacf52ead0b54f5e1ba408ac8dba2f0363bd8.nq.gz
    ├── 13dcea97ed0939dd10a10058624f4850a588e158.nq.gz
    ├── 140ad5c705337b96ebb646540d65b94063dcfd04.nq.gz
    ├── 14e74fd9e793019f450d4ba9d9e43cba1eb0db7d.nq.gz
    ├── 156040c686be75fc6ae15ff98f5ffa6ae122ea5b.nq.gz
    ├── 16a7ec588655e8d50fac783de73c014ba9b9489f.nq.gz
    ├── 17077f6529a9c6d1ddff2e306263685254b13e40.nq.gz
    ├── 17c709e92c2a25b5445930f1a2a55f05c734fa61.nq.gz
    ├── 17ce8ef18edda22b0a72bd4d4b5c16641f55d686.nq.gz
    ├── 1821b80e792de989322d369ab3c750fbbf7bb7e7.nq.gz
    ├── 190bdb9ee260377f3b2249eca57058112c6cba75.nq.gz
    ├── 19dbc3adf0075835729c7addf313d141240a9c8f.nq.gz
    ├── 1a3f412401dc190075210b16cb85ea5aa766ef1f.nq.gz
    ├── 1b250097102a808f6e938226405341b924bb2678.nq.gz
    ├── 1bfa725f7025f6c67665f225e384706e693fb629.nq.gz
    ├── 1e09f09b60869e65a50e42123aafef36082363d0.nq.gz
    ├── 1f17d89c4027d15a2e16239787d68e00cd01263b.nq.gz
    ├── 2051ca95056d698cd205e3099fad636b08736d81.nq.gz
    ├── 210e17b181f895dc2da067e1b48b7850d943bd8b.nq.gz
    ├── 22daca6bfdf50bc7f9d10263a2e05fb75886f23d.nq.gz
    ├── 24fdaddd41647f6213857b3dfb6753153e745a69.nq.gz
    ├── 25446a4c812b37de152ba164271c514291114727.nq.gz
    ├── 27d298d455e2cd617bda02b36b27ef544a84a874.nq.gz
    ├── 27ee71ce9d00b8efbbf41f69ac19c7e2f46f54e3.nq.gz
    ├── 28191bcfca202f0c6f7d35e3167e2bcb71ce8388.nq.gz
    ├── 285b50cb55f9696ef935a6e4a831fdad65c5548c.nq.gz
    ├── 2a05a71b343976ea58f0d58ca92228ca3be02ce4.nq.gz
    ├── 2a7671f2351eb7976ba3d6eec8f06a72776458bd.nq.gz
    ├── 2a9eb5ba2ce6084596ec7ebf14e76e46ad6c24ca.nq.gz
    ├── 2bcd7d48006c8e562e8381f8b486d42a196bde6c.nq.gz
    ├── 2d0d49ce26b1718deb121963be2bef9f114e1d58.nq.gz
    ├── 2d428c40f02dca5af4a82aa4cf9b01642fcbb5b7.nq.gz
    ├── 2ddd0d99ca231597158e04216571a1d944305e14.nq.gz
    ├── 2e3fd95ce505346617fde2898ac8083967853fa0.nq.gz
    ├── 2f4034a4adabdcaec32bca43a420320f6e39d9b3.nq.gz
    ├── 2fe55bd2d3ced39d852853c1e0ee43983f80a517.nq.gz
    ├── 30ac6012e4bbaa38bfe85453f3a1c796067d5751.nq.gz
    ├── 31ffd973397f03b10664e0bcac75a5e496f0fb40.nq.gz
    ├── 3594dbe662de234e794575eed99c711077c0a0a5.nq.gz
    ├── 365664f247d0398bbcb75517d66d2ac6843b2cc7.nq.gz
    ├── 37e12d69f504df445e2c4d39637626204484b5f9.nq.gz
    ├── 37e9b7fee05c5d85cf900c58959f898485b49f52.nq.gz
    ├── 3866674f60a6eca4a896fd5afd7621fd28513e3d.nq.gz
    ├── 3b2b49de51f1e75a973a1babe3ecdc45ebb23709.nq.gz
    ├── 3bb7d02f7758eeefa84d6cb4e0ef84d50986855d.nq.gz
    ├── 3c70b75f33dcb45b5ff1b8b2e84090018a537f73.nq.gz
    ├── 3d50f703f932db5b6fd2dc29000758e835f4ce89.nq.gz
    ├── 3dd74f3beafced36e310a6c3be1bcbd8543233f3.nq.gz
    ├── 3e04f77667a08157a27cc26e67938b8373519ac0.nq.gz
    ├── 3e4527dc73887e87e1f94c7e23ef58aa81e4374b.nq.gz
    ├── 3f3887fce1753046fd63f910bfd532cccb09e687.nq.gz
    ├── 3fcf1f9918de89eacabfc950243ec63d1f0a3917.nq.gz
    ├── 402d1428dc264936c4f3e657e0b8614880f9a5ca.nq.gz
    ├── 417da386b434be69e430729d6daeabbfaf2f0c76.nq.gz
    ├── 418911fbd05f65a941fd68a912f141a72ebce53d.nq.gz
    ├── 43c198e7cb6e2d663599c8e4a5a167d302d4de2b.nq.gz
    ├── 44335dd1fc93875428b77f367513529d460db4e0.nq.gz
    ├── 450920838705457d7a264a314d6727a1c05a1aa7.nq.gz
    ├── 45e7cc47a1f475d3c48c58c7a5b49439d3e3868c.nq.gz
    ├── 468295001502356fc271c2ba251bd7e16cc3be7e.nq.gz
    ├── 46d013a402b85d4a0e35f0623bb89a8bcb47f82a.nq.gz
    ├── 47109ef1fcb112e03048831b359a1d1c4c8897fc.nq.gz
    ├── 47b6f75cbffdd608cb0190909346b42ee911275c.nq.gz
    ├── 47d13a8230678b70e0a592b4016268f4bdcecfa0.nq.gz
    ├── 48f293820b2b922bc0c6d7f42b16e949ad0f82d0.nq.gz
    ├── 4ab893eef6287ba8bcac871c6c9c348fc063a57e.nq.gz
    ├── 4b21e0b4558b7fe76e85d7c344a6d8883fd7524e.nq.gz
    ├── 4cc4324c2ae7397cf712e4dcdd64060b620ce642.nq.gz
    ├── 4d286aa8641624123c0ed4c1d91b47c84d6737a8.nq.gz
    ├── 4d4d634e2ccdceb06d1ce763dcfc086e0a5467bb.nq.gz
    ├── 4e84745ca5442b8745ba938ae6a49a94e6363b6f.nq.gz
    ├── 5025061d997cd8d9ef86db6c16406a97ce5d9244.nq.gz
    ├── 513c4a565786b7837da7dc10c35d681d2f3795d3.nq.gz
    ├── 53441dd52d1997eca774b493508c015925db8d5e.nq.gz
    ├── 54920c03e8f2d9bfcfc88f52cbd1d24d9a2c5533.nq.gz
    ├── 5942f368728bc5261aa93f8b9abd45a42c36255f.nq.gz
    ├── 5c33a2a57f48c393fddf24768731393e7e1c7cf7.nq.gz
    ├── 5d5528317221ffe00a417de1756d4727b8b12870.nq.gz
    ├── 5e353ad57c8582a610f90f432c3e4686fa8ed283.nq.gz
    ├── 5ff98603e359ac3733a551d45f1da2ffc55c5c9b.nq.gz
    ├── 601f12a4d8ea282eb2f05e8211dcb741700e9303.nq.gz
    ├── 628f9c746b8bf77410490e0eb98f97a4f09d7d8a.nq.gz
    ├── 63903312efbc83ac7bccb9d3025716961466ad57.nq.gz
    ├── 65eee359f983894c5098f9351c1af36757d8a9ef.nq.gz
    ├── 66fb9552cae2eebaedfad7ee8987441fdf91b021.nq.gz
    ├── 6774671c34ba2046d579e97f785302d84d3a81bf.nq.gz
    ├── 6877a5ad383860800eac599f51e129f365cff04d.nq.gz
    ├── 68e262892f9a1a13fcf57474b9aee71c6123e07c.nq.gz
    ├── 69138137231aa8a52b385b4c3855cd8811fd0e5a.nq.gz
    ├── 6a39caf258b2a611025e83f94996f6a0b0b33d14.nq.gz
    ├── 6c5c1d1493e3427c29824b19435ec84859cbadbe.nq.gz
    ├── 6cdf781edb3067fa466274977ac0dc6e76572db4.nq.gz
    ├── 6d87961fe1d5e6fe914d06a981a49f56ce734d21.nq.gz
    ├── 6e4542f3b84da3194725618482d96465e62bcb11.nq.gz
    ├── 7020792381f50d1eeb0a5e5339ef8a82b4e12693.nq.gz
    ├── 71465712c9643f79f81dafb810bce73d81694c99.nq.gz
    ├── 71b14fa91a1a996d9c671d87e622b34795478427.nq.gz
    ├── 72e58febe8d264dff537507ba3689b53dd02d03c.nq.gz
    ├── 73b10b63271151c05fa47bad0b9ba4b68604bc9f.nq.gz
    ├── 755ed2e79d44eafb95eb0b9c625c1031e5402e7c.nq.gz
    ├── 770c18d1f00b69eabe9ffbcc8ee3b2f7d9f3f53a.nq.gz
    ├── 771dfbe4d638d9be5b8835836969b394ba19a64b.nq.gz
    ├── 78759e810c3616c7064f6cb4eab7c17b634d3849.nq.gz
    ├── 788232d61b5f0051bbbd6a9b370dcc8e3ee878f0.nq.gz
    ├── 7b486b81ec07d10db052de638c7e30ea5e0fc9bc.nq.gz
    ├── 7bb9cbd0c9a4a745be27343f97c6651f56c620ce.nq.gz
    ├── 7c4756026ef07ee7abafd24dd04559b07e02e5f1.nq.gz
    ├── 7ceb3c70c86c41b7d6c2a9f247023cb7019e250a.nq.gz
    ├── 7d02074114fcc76b16cedcfc3c839d3abdbc3e9c.nq.gz
    ├── 7d6caf060b361bf6415d1d9b647b5cd0e3586628.nq.gz
    ├── 7dca20a34bee6059366b5741f8e13c5ef41c786f.nq.gz
    ├── 7deb99378c3a98f659a542bc541c596ab638bda9.nq.gz
    ├── 7e91db627cc6358fae7ba5f0f622f5268f5d763f.nq.gz
    ├── 7f7a0497e4266e593414a8a3dba43c1ab42722fd.nq.gz
    ├── 8096ba898aee896fa77d41d35e63b3f61b7cd1a9.nq.gz
    ├── 81fc8628cfba38883772435956a39acca69c1b5f.nq.gz
    ├── 8263d3acfdd12f2cbc2b64aa99d53a41015fa981.nq.gz
    ├── 82c02d4bf92785290f98615989d287fd9fd19a40.nq.gz
    ├── 83674020211c2252ed50113c3b10fbde9b4e670d.nq.gz
    ├── 849b63aefcf9c3b1f1f510a9ecd7a07ddde0f0a0.nq.gz
    ├── 865ee13caf20ab1a836e621dbffdbdf30df287b6.nq.gz
    ├── 8be78c7bafc90dd49ce136e35238c6a5f6a865b6.nq.gz
    ├── 8c1a6d53835ff6a7527ffe588028f32bf2fe609e.nq.gz
    ├── 8d28646988d2e686f5ce46e5c5ef4ebea0c0acbc.nq.gz
    ├── 8e54832e022556cae54dbc8457b7a92f743852f3.nq.gz
    ├── 8e7d8ada47d3ec570d7be04496025e9120f25e4a.nq.gz
    ├── 8edde5c61a5643025c302c20dd326ba5e1a2a7c6.nq.gz
    ├── 8ff486506106b601f3f85a288e7a23b406e2c1d2.nq.gz
    ├── 9037c0df1ac71f8255f3665aa85cd04cb47c23ba.nq.gz
    ├── 9040919b22ba1f25365e73c88b64499d9e9436db.nq.gz
    ├── 9117b1010d35cf1107c11f7202aee46ee2bbe5ca.nq.gz
    ├── 91a3a050fc762d1883314473866d32912d2c3395.nq.gz
    ├── 91b3c9851e2f82c12cc685f57bf0584b3757ccd1.nq.gz
    ├── 922f8578f83e69572450096b3382422290fc56bd.nq.gz
    ├── 92e625ba1168eac68c9f733e781714d4087b7fe7.nq.gz
    ├── 947d43a7f870b18dc6ef674f3d3007136c5393a4.nq.gz
    ├── 95025764e63453f4b6eb275242b3f3607d4a0e9a.nq.gz
    ├── 96389de4b48812b880a4cbbad7ae15165df858a3.nq.gz
    ├── 96a5fc487b538ea2b17c016edcbd6fd639aacb83.nq.gz
    ├── 973e0eb698aaf4a27aba4dfa047da40971ce0c2a.nq.gz
    ├── 985ab42bee3592d4ac940b2b05a735f68e07ee77.nq.gz
    ├── 989444a98ca5f49e7ccc9f8869cb05e6c8e514dd.nq.gz
    ├── 98baf22f71521e9c378472bb220129eb7ba58d6a.nq.gz
    ├── 98f0c08fe87353441c19637f2b7ca8a64271d803.nq.gz
    ├── 9924c231675c69273c5de6316b00fb63a7c5326d.nq.gz
    ├── 99351dcb551866bbeb9faa8a11924c3e6b9850c7.nq.gz
    ├── 9980530a54ec76389f6a5fb1976d1432561ed1f9.nq.gz
    ├── 9a2d90d5f2836e754aee92f741ce622d31dae7f8.nq.gz
    ├── 9a737309bf30cc5c75778c0a31df2998390c613f.nq.gz
    ├── 9a94fda4d3db8f7660dbb7d5bcdb8078059cae62.nq.gz
    ├── 9b377979bbff5870bf381462f5990bf7b4569df5.nq.gz
    ├── 9b3951e59256db7f5bef4464db9c545b9408a889.nq.gz
    ├── 9c3a9335b9e0ce472705b4d2ba9d015415788d9b.nq.gz
    ├── 9c70730447f50b5b1a94b9e1dc35ea34d2ffa8c9.nq.gz
    ├── 9e051e056556c34c0d52685ea4c282d1d5d577c1.nq.gz
    ├── a03b507a6f08e848247d66a02c18d70f73aa23f6.nq.gz
    ├── a09c147988f4cae41bee3176617f0f0e08b90612.nq.gz
    ├── a0a473c8afd3b8eb50c3d1c18b5e0120c298cc66.nq.gz
    ├── a0bb6add5805fdf4a91f9074d1cd9da3a8729138.nq.gz
    ├── a0eee8be09bba1ef8c7002d5c3c3d42e2b4677d5.nq.gz
    ├── a1c3987f22a27e5f13919140f4fd1cf13d37e1f8.nq.gz
    ├── a28a0205bc85866663484b5f0ff087d643367b42.nq.gz
    ├── a34a9c7ca1b9171a58a239745f9252e75b2ffc1c.nq.gz
    ├── a495c6db5670253ac0fe9e939b20f049ccef3da0.nq.gz
    ├── a65f17453fc2fd6fc5a2aa65343d5f0991a4dda9.nq.gz
    ├── a87d10db7aea87e6cd6a4148851f7dc86f87196b.nq.gz
    ├── a9769076eaecc1229fbcf546e985c84cbb714f70.nq.gz
    ├── ab27d19c6a1c5a8f1aad43211ce193802e26e7eb.nq.gz
    ├── abeee6c9f4dcf5742624188a563285c091c5854b.nq.gz
    ├── ac3b041c0980289754c623dbcb499e22d9fa7fdf.nq.gz
    ├── ad15d14d84423ce15c8332662fa2fbe16b5e4e38.nq.gz
    └── ad2fe9ca5423cf3ea5b3edee90ecb92fb0c9aafd.nq.gz

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

[eventlet/eventlet](https://github.com/eventlet/eventlet)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
