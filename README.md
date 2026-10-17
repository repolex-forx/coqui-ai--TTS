# Repolex Knowledge Graph of coqui-ai/TTS

RDF knowledge graph data for [coqui-ai/TTS](https://github.com/coqui-ai/TTS), parsed by [repolex](https://repolex.ai).

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
rlex download coqui-ai/TTS
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dbf1a08a0d4e47fdad6172e433eeb34bc6b13b4e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dbf1a08a0d4e47fdad6172e433eeb34bc6b13b4e
│           └── chunk-001.nq.gz
└── blob
    ├── 00597a0f88038e97ace965234703f43fad872d0f.nq.gz
    ├── 00f13397fa2509e2cbe57c2365462606bc6aad0f.nq.gz
    ├── 018679f573020075fa77cd0b917fbbe75e4627c0.nq.gz
    ├── 01c447198f1bc0ebd4f330299d3387c9911fd344.nq.gz
    ├── 0243735dde4c1b87434087ddc01ad6b80e53cc27.nq.gz
    ├── 0376e2e3926e65254c3a81d085d48c97df033958.nq.gz
    ├── 051118236f1429aa12b41c6ebaa62d2a9e3d592c.nq.gz
    ├── 053444b0c1010d5a93970cc26b2c225e305279a9.nq.gz
    ├── 055526b1bcea41c646e841baa556b71a71da7487.nq.gz
    ├── 05ca7db6bd1c24907a0aeeb95d9ecec5271e7351.nq.gz
    ├── 05dba7084ff5533b68779d46238530f4988db934.nq.gz
    ├── 05f357a580a4ab842b663430eeea2b9ab084d9c0.nq.gz
    ├── 0631ba98c00029e9871c965e4c7f465aa32bc406.nq.gz
    ├── 069f565137b86d69735ddfb60eee74b123340674.nq.gz
    ├── 08acc48cd34296c4549931ce440fda8d1882ba66.nq.gz
    ├── 091fcc3a50a51f3d3fee47a70825260757e6d885.nq.gz
    ├── 09582cea7c7962b098efcde5754a02573d18264a.nq.gz
    ├── 0975d5edcb12f32e2cdc4ae99730ad9144cac303.nq.gz
    ├── 09e270eae566d0c05c8c285af6504711d8f12cba.nq.gz
    ├── 09e5f4765dce8743db2a3ed879e7811d2b9d23d6.nq.gz
    ├── 0ec5f167b469a3b60d7208c12feb3195d005bff0.nq.gz
    ├── 0efcf03e990303d57b794ffa741a8d09072ad1c1.nq.gz
    ├── 0f580a85b6405d35df5e14c384412a6331981755.nq.gz
    ├── 10015de5a9075c34875dcbab6e3e893e30b6d583.nq.gz
    ├── 104dc7b94e17b1d7f828103d2396d6c5115b628a.nq.gz
    ├── 1303f584eaccdab48b2c0f57e08586c658ad348f.nq.gz
    ├── 13f47a938baff80f290af65fff78a4d792f7c3a8.nq.gz
    ├── 14e2f777f6c395e7e04ab4aa306bbcc4b0c1120e.nq.gz
    ├── 151334f66075e016c55fd93e9dab5be6fefac276.nq.gz
    ├── 15cffd544f2203ba85040fa21710f42d33187547.nq.gz
    ├── 164568477009004443b61e648a341309610ce76e.nq.gz
    ├── 16f10451ba51b4ae90a5ef15f0eac9283a34fc6f.nq.gz
    ├── 17eab1379de991c36897c2ce701802ef76849c0d.nq.gz
    ├── 186cea02e75e156c40923de91086c369a9ea02ee.nq.gz
    ├── 18c48d0bd181830fe096852dfdfe30cba1bc47b4.nq.gz
    ├── 1922577e5b479980a8e11ac3ae15549cfeb178db.nq.gz
    ├── 19f2761bbc42051a2f03d1170c011955dcdd28cb.nq.gz
    ├── 19fb25bef88375c99b5aeb7f608843b15393263e.nq.gz
    ├── 1a8e9ca8e9b554657a0ed200b99a5d47d01c459b.nq.gz
    ├── 1abdf45d8759de249eafdd479c5e96b7f5f59b33.nq.gz
    ├── 1bf7a8822e16aaf290967fffa9264b9b9e3d4c9d.nq.gz
    ├── 1dd97c48929795717597fb9a4c55f43b85c62533.nq.gz
    ├── 1e1836b32ce2010ad55a0253849f2e59c61dad82.nq.gz
    ├── 1eb3f77269c0e7b718d350217796ec704543c681.nq.gz
    ├── 1f15159b42e8bf3d5077b1efbf81518b0dd13688.nq.gz
    ├── 1f94c5332df1e2774955eb263c3b688c5ad6e827.nq.gz
    ├── 1fb37fbf71480918ea5f69fc07db7c0daf31fedf.nq.gz
    ├── 2041352d64417c304ba738455316c97a4eb193b0.nq.gz
    ├── 2157409059873c80aa93884ecb847639add77b7a.nq.gz
    ├── 2181ffa7ec4e1f54d86cc5865a8fa7f6b6e362af.nq.gz
    ├── 21a6727d8bffb9a16c9b053aaae1aab25c1805fa.nq.gz
    ├── 21f6f08fd6b10e5ad9fe36e452f46d488cad3503.nq.gz
    ├── 22e46b683adfc7f6c7c8a57fb5b697e422cd915c.nq.gz
    ├── 22ec6e410ada8306940712c29272ce97c0d124ba.nq.gz
    ├── 233533b7968a053c0868f9db2446749e9c0effd1.nq.gz
    ├── 23bb440a0af77b443e847b1c80620887bef485bb.nq.gz
    ├── 24e9e51a9428022cbc60750dcf1f6216a018a247.nq.gz
    ├── 25c3798e6b8f5fbc66224af66c9955e245b94097.nq.gz
    ├── 25d6590659cf5863176eb6609c7609b0e1b28d12.nq.gz
    ├── 25d9aa8148aff95a75aad823eb8d7bff13f09e12.nq.gz
    ├── 270656c4e39dc11636efbb1ba51eba7c9b4a8f04.nq.gz
    ├── 27809ce50741e4491338f1cf04cbff52df1e26d9.nq.gz
    ├── 27b723bc0fe56388674d33e2c8839b7fda68c776.nq.gz
    ├── 27bb15206f1b06db9f2f14451caa7f5f43bdb7f1.nq.gz
    ├── 28418f7163361120914f277446f76ac9f0363254.nq.gz
    ├── 2944e6faceb87602edb6b09f106e824ea4653a59.nq.gz
    ├── 2951b1495a78fa7f0ded9dbd4201af88206267cf.nq.gz
    ├── 2a723f105f56e25fee096831719f78155180ee89.nq.gz
    ├── 2bbcf3cd70fa5cc4fc6cfa1935a1bd8b1b4e840d.nq.gz
    ├── 2bd2e5f0875a84633e707702cd7d628409b12057.nq.gz
    ├── 2c536ae16cf8134d66c83aaf978ed01fc396b680.nq.gz
    ├── 2c69217c403d491de2d78c8253c8eca9ce83bef5.nq.gz
    ├── 2dcbf214935a1fde832a32139145ce87fa752598.nq.gz
    ├── 2f78f762b340c2fa66546c368dbf935290a4f98b.nq.gz
    ├── 2f958cb5a5a66e1b7714887f1784a549200e479b.nq.gz
    ├── 3070241f1cc1ac95867f2d4173495b9a7047a15e.nq.gz
    ├── 30e5fa7a3754bc4ec5e11e46d18254134ea465bb.nq.gz
    ├── 30fb79a8e4f64fbefbd6c19427f38d3003409733.nq.gz
    ├── 3107ba661babc57bb67f6b06c84a00f5a468b132.nq.gz
    ├── 3146ac1c116cb807a81889b7a9ab223b9a051036.nq.gz
    ├── 317a01af53ce26914d83610a913eb44b5836dac2.nq.gz
    ├── 321d3999c185a326a9d300451a3e732e4225f2e6.nq.gz
    ├── 328e52f369e641f92d6c550a9ccebf60dbff9a26.nq.gz
    ├── 32b26fc6fc38beb79303522f265b7f638bca4df3.nq.gz
    ├── 32cfd9967fa55a3bd60992f7bb409d6d388efa1b.nq.gz
    ├── 32ecd7bdc3652b3683be846bdd9518e937aee904.nq.gz
    ├── 330109c3bc1c99134587537a0e8165ce63ca8103.nq.gz
    ├── 3329ddb448ed3bfff911bb90110defcc72e14bc2.nq.gz
    ├── 337e24259f0ffa39d4d77b57749988b64763c2f1.nq.gz
    ├── 33aa8ba1635037ce328e3617cec5ab757db4826b.nq.gz
    ├── 34cde7e8448cf817dc00bdc3a116e64fed079284.nq.gz
    ├── 350b5ea99633569d6977851875d5d8d83175ac36.nq.gz
    ├── 35bda597d532455bc21422d35bce9732f47de0c1.nq.gz
    ├── 36c467d08335ea24ad1c0e6705e0c351f7fb8d65.nq.gz
    ├── 371ad9e41e584c41564dbcd7b9ff9548c61aac75.nq.gz
    ├── 37c1a6e8774cdfd439baa38a8a7ad55fd79ebf7c.nq.gz
    ├── 39fc4190acff0267c220895db29c49eb2a2903a3.nq.gz
    ├── 3a527f46099ce79cc08a70ccb1aa22aaf0f7c429.nq.gz
    ├── 3ab7ea7a3b10ec3cc23d8a744c7bdc79de52dbf2.nq.gz
    ├── 3b43e527f5e9ca2bd0880bf204e04a1526bc8dfb.nq.gz
    ├── 3cac1b8d6d12fe98123ca554899978782cf3b4c5.nq.gz
    ├── 3d1e3f8c4d43669afe82810b46cd7b6babe59eef.nq.gz
    ├── 3d8eec2b4ee0d7b0c79e368616d4b75fb2e551d4.nq.gz
    ├── 3db7ff7afe7770ed6489650f24db5567eaaadb4f.nq.gz
    ├── 3e740b2ff400ab8f8815d3958bae9d6664c49142.nq.gz
    ├── 3e7d0f6c914fa3a4e706a5e28bbd745afcaa4d67.nq.gz
    ├── 3ec0eeb34048a689a54e1c264a823df3477de634.nq.gz
    ├── 3ef0dbaa8b631f8fc0e5e4d38422dcead94799eb.nq.gz
    ├── 3f06b578248441d9951bf0ee62e2764ffd9ff9d7.nq.gz
    ├── 40107070e1f19fbb8cf4e259b6a232c6d892357e.nq.gz
    ├── 402fbca4596055690e0822332e087a0a0d68ad52.nq.gz
    ├── 411553c121b9e4667e522f5dbd9b0491fb41fa81.nq.gz
    ├── 4125d10bddfc55d9ae40bf32d81e51db5f7bf1cb.nq.gz
    ├── 41598a10f10531eb51e706bfbf660ac377f25cc2.nq.gz
    ├── 41dfbe14e96347f90b942a4d2612e199a8ae8467.nq.gz
    ├── 423aeed377e3ba2d22b574418aa45714c322f670.nq.gz
    ├── 423b79b9ce5d5d7e7ddb20317b48fa711fad8f92.nq.gz
    ├── 43b5f08042f1139e536aae2d57cd85675dce49e7.nq.gz
    ├── 43e72417c200493c6392b3acb131a43738dad2bd.nq.gz
    ├── 44b15c5ad554fabfa240f74557f4064b998e6840.nq.gz
    ├── 4524b4b5c591f9790f68999b4920abc50f32c9cd.nq.gz
    ├── 45a6d4ce10a31a66657223ef742e40d9cb1c5b40.nq.gz
    ├── 45b6252136de1388b7946dde924ef05cb34265ab.nq.gz
    ├── 461435c2a1ffa3f6c9e2cd219bab58c6ee0c59cd.nq.gz
    ├── 47456cc5ac41b7ed9522fe543affc8482218730c.nq.gz
    ├── 474ec4641d0a569fc1938442ab9f7ce4bb980119.nq.gz
    ├── 4787ea61007656819eb57d52d5865b38c7afa915.nq.gz
    ├── 4855886efdd2298875ef038dcfdb918b5c912d62.nq.gz
    ├── 497d67ac76d0cb797db92bba3f9ad24ab5293a64.nq.gz
    ├── 49b6c09c3848a224dfb39a1f653aa1b289a4b6e5.nq.gz
    ├── 4a7eea5ded0ce2e89a13882864ab9dea226239fd.nq.gz
    ├── 4b2d2b2a3a46d820a614295b651c92b2a013374d.nq.gz
    ├── 4ba7f7bc822bee93df7d7bce9a80c49871534559.nq.gz
    ├── 4baab88a915b74b047237afacf2ddb2cf5411fd9.nq.gz
    ├── 4bc199294164da0e8c480e292dd5a478e72f4daf.nq.gz
    ├── 4bd7a78eef2c4850bca9369def55d68336cd53aa.nq.gz
    ├── 4beda291aa15398024b5b16cd6bf12b88898a0a9.nq.gz
    ├── 4cd7ae88068cfaffe179f2e61354cc7eb760268c.nq.gz
    ├── 4d1cd1374afe8d5f0b9e87ed81db25d7e4032af9.nq.gz
    ├── 4dfa037dae2e2bbb25e5e29b6c200d52fdcd0511.nq.gz
    ├── 4e25c3a4c91cddd0bf0e5d6e273262e3dbd3a2dd.nq.gz
    ├── 4fa4741ab79686123605fa84f1f9d3863b340e44.nq.gz
    ├── 4fc79874159aad40ce27f34671907a25d7e39a94.nq.gz
    ├── 503b4e2483b447a01b0cb4abb02bc6cf34c80b90.nq.gz
    ├── 5074cded6d0b7ffab940261cd904b5d2da586480.nq.gz
    ├── 50c38c4deb8fd861f7cef8144df3098c3558aeb4.nq.gz
    ├── 50c7707fbfaec6fc67c3a1d12119321b17ecba82.nq.gz
    ├── 50f72847ed3e1c7089915ef8fd77ae5775c5b260.nq.gz
    ├── 51142e5eceb20564585635a9040a24bc8eb3b6e3.nq.gz
    ├── 511d215c656f1ce3ed31484963db64fae4dc77d4.nq.gz
    ├── 513093819e0589ca6fad520d90cc4f1377846002.nq.gz
    ├── 51852b5b820d181824b0db1a205cd5d7bd4fb20d.nq.gz
    ├── 522b7bb17ca59ee62d2b1de7245a3eab91339417.nq.gz
    ├── 52f6fd0893a1e67270ccd6af4a50d1370a8fa5c4.nq.gz
    ├── 530781ef887d17a290b65810d0f3c5760217c920.nq.gz
    ├── 54766d906f02303ba274f705d94f1853becd60b7.nq.gz
    ├── 547e7899a8b3e37120291c12a0568b4d2aeb5306.nq.gz
    ├── 56725cce10cc9e73be58ee938507570e5855ee0b.nq.gz
    ├── 56bccfb5b27972c92f051729cfc56516e5ffe00c.nq.gz
    ├── 584286814b78b452d66d2be174cdcad156f23b16.nq.gz
    ├── 58baee53e26ccc13e7bef90e1a8fc0038456955d.nq.gz
    ├── 593372dc7cb2fba240eb5f08e8e2cfae5a4b4e45.nq.gz
    ├── 5a09b4e53e2a4e40dd7c9d0d4c7e5b3c30f317a5.nq.gz
    ├── 5b1fa9d38a0026ecfc8cf257fb90168cf44a20b6.nq.gz
    ├── 5b5aa0fc48fe00aeedeff28ba48ed2af498ce582.nq.gz
    ├── 5d8626faa665f7195222be8e50c26c31b4af73cd.nq.gz
    ├── 5d86776a4dd406fee2cfb07f87ddf09431f075a0.nq.gz
    ├── 5e66b70df8c64cb64b300c337f782ea8b7235fc0.nq.gz
    ├── 5ec8ce7e59694563b85fa34c590acd421008cff0.nq.gz
    ├── 5eda2671be980abce4a0506a075387b601a1596c.nq.gz
    ├── 5f1bc3fd50bc3dfeabf4c4834d7492b11717dc43.nq.gz
    ├── 600b0db582880920be11cfc7773e4b2876127cb8.nq.gz
    ├── 6059d7f04f7c9fadd6df1d424e8e164e54a7310e.nq.gz
    ├── 61c5174ac5e67885288043885290c2906656c99c.nq.gz
    ├── 6245cc5a07d8f4629a8953b6c4537d46feff087a.nq.gz
    ├── 6253efbbefc32222464a97bee99707d46bcdcf8b.nq.gz
    ├── 6262db4bbfeb15ba298184ab0b7c7bf323f472df.nq.gz
    ├── 626917381a2a677efabb70d894ed623cd2ac08dc.nq.gz
    ├── 62a9c39322e051124d8c2d816cbc7d479df69dfe.nq.gz
    ├── 6378c07a6dee8d9d52e0f1341b0105b3ed119abe.nq.gz
    ├── 639b70c1bae56e32cb06db7c196af533108ffa39.nq.gz
    ├── 640f50921888f4fd4a33a32e725b280a639170b6.nq.gz
    ├── 640f708c13ffd653794455aa0730ed6c143f2fc9.nq.gz
    ├── 6519ee3fefea171c22dc4eb7da58e0322afda1ed.nq.gz
    ├── 65586b6c0a78682e8061833d1a2b86c73255fb52.nq.gz
    ├── 6575b86ec22818fe1dc0c1e6336a7fd255855330.nq.gz
    ├── 65901617b69d3ae708e09226c5e4ad903f89a929.nq.gz
    ├── 65d3f642c9dcaf109cd8697beb8672f53a81dd59.nq.gz
    ├── 65edf98ca4a5ac2028bd930b3ddfe54a60564d90.nq.gz
    ├── 662fcd02ece0fad387b6bfc4bad9316c7e2a0bad.nq.gz
    ├── 66b7ca959045dc4ae26db09a648e9be7303ad368.nq.gz
    ├── 67f324cfce5f701f0d7453beab81590bef6be114.nq.gz
    ├── 68303a1bd1148089eab7ee8be12d4f37ddf420e1.nq.gz
    ├── 68eebaf7e6dd503333f2bb8b85e0bd4115c2011f.nq.gz
    ├── 69800cf7b4e9b518a352191498ec50e44af86f90.nq.gz
    ├── 69b8c17c3fe71f55be12b728fa3c8f0e85cefb89.nq.gz
    ├── 6a1185c0966f9731a0e0f1878cc95a757d97107a.nq.gz
    └── 6ad188b8c03a170097c0393c6769996f03cf9054.nq.gz

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

[coqui-ai/TTS](https://github.com/coqui-ai/TTS)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
