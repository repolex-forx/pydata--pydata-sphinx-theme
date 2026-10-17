# Repolex Knowledge Graph of pydata/pydata-sphinx-theme

RDF knowledge graph data for [pydata/pydata-sphinx-theme](https://github.com/pydata/pydata-sphinx-theme), parsed by [repolex](https://repolex.ai).

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
rlex download pydata/pydata-sphinx-theme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24aa6558b7a66bd0473234c7031ad53f45181d64
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24aa6558b7a66bd0473234c7031ad53f45181d64
│           └── chunk-001.nq.gz
└── blob
    ├── 00627b38f0560f577c9d8131b15f9c4dc79095ea.nq.gz
    ├── 01388384facbc24b608f253ace93be1233eb7204.nq.gz
    ├── 02ebc606b5c5a6770985475a3c893a34b920dd0a.nq.gz
    ├── 038d2edf15c981494665539d36c781d90639bb9c.nq.gz
    ├── 03effa8ae458a33f065c7b16b433d1fb792c4b27.nq.gz
    ├── 05f2e413af2b6a5528d8204ea24bfa3a53d06184.nq.gz
    ├── 06bf2c2d13566c553d9bfb38678779beb3c2e0c8.nq.gz
    ├── 06dd09e08605bbd0431cce8399b3a911993d4572.nq.gz
    ├── 07325a4931b4e82f77eff35b0f50fc0f7b838f42.nq.gz
    ├── 075c0001bf616a340952620fddfe1be094777517.nq.gz
    ├── 085bcdde86642980734b8a8b05337ebb15fd4864.nq.gz
    ├── 0b0b76690cbcee91b379824079635879f435bcef.nq.gz
    ├── 0c71b4bf38718ceacd765b28a8672dd8ca7a0b6c.nq.gz
    ├── 0d23a3685cd42aa8ab3458c49383fdb846b104ac.nq.gz
    ├── 0fb635d7b7b14c5be6bd487461fd20f1903f0ae4.nq.gz
    ├── 10540067402724a172ec652cc2a817ff936b216e.nq.gz
    ├── 110733a55a83769b13a839358240aef792154db6.nq.gz
    ├── 118837ca3815991f11e685199b8c23520e8de013.nq.gz
    ├── 157b734db061d293eff92884bb1a452a0c47b32f.nq.gz
    ├── 15afb8b1bcdd7e61c95d668d59f4d6ccb3081a95.nq.gz
    ├── 15babc1327b63771a81c7a23820373c83a90f8a5.nq.gz
    ├── 181546a3b231a9f26d702f7bc64a35e1e5514bab.nq.gz
    ├── 18929855fb6d9a4dfe137340b2c4b612c636c2a6.nq.gz
    ├── 18b82b6ad91fc176cef1aa57e575aeeb3b60f9e6.nq.gz
    ├── 18e15e84f02ef9f652e37eecb56217199931d06b.nq.gz
    ├── 19797b8e587858a0c420c92fa2e165da53bb011d.nq.gz
    ├── 19881d489ea8d96194e1e1d6da2b51110a36fe11.nq.gz
    ├── 1a14834ca3b88ba7cb6c225fc9314d4583f8c676.nq.gz
    ├── 1ab6d69d039f8956bb742f92f1212d2819410cbd.nq.gz
    ├── 1bbf87751408e562141eb535cae3ec8c7e084b2b.nq.gz
    ├── 1c3c1a41ed017841d8f097e9245cf070d0b75229.nq.gz
    ├── 1c703cb7cf799a4fd3f589e1ce94687d08370855.nq.gz
    ├── 1d0ccfc590eb09b3147283de3b283de612729d80.nq.gz
    ├── 1f3d308c9bcebe34bb284c6fc4b96b13381a16d4.nq.gz
    ├── 20b43b2547746af3f2d0f57695a214dd7d4048d1.nq.gz
    ├── 20c605559668e2000e7ea94827c2c42162757b69.nq.gz
    ├── 2225b8271d5ff59bbc6cb9a329e552291de67427.nq.gz
    ├── 2383b7c456c970690e616590d6ba53aa5be8b6ee.nq.gz
    ├── 2460c42c05baccfc258df6f0fe243714f7b37481.nq.gz
    ├── 24d5022226bdd03154cccd728834c95a4cf11b51.nq.gz
    ├── 268b2ba41adfa5748c49c533b231e9980c422ae1.nq.gz
    ├── 27c89bcff39ed3f019a8bb7ff20ee012469719a5.nq.gz
    ├── 283602e15b129009a54d336a30a2aa3accd4ab62.nq.gz
    ├── 29d0755db35b49696d97bfddc50632ea4b2f74ee.nq.gz
    ├── 29dad001c418e398d6cdc714c22eeb83413d4863.nq.gz
    ├── 2a316e2d5cedd0b1b2ea513c297ef8a61cb02ada.nq.gz
    ├── 2a4b2b410a082a56d31ae7e7c21209e7bdcf073a.nq.gz
    ├── 2b8320b85d8a3fcb282a6781b0f91817f8f5d454.nq.gz
    ├── 2bff1a6676e807bbdd8ed205ab70d6ee2eab2156.nq.gz
    ├── 2d5ca3e5afffe71a0db6606fea07d66387ca7bda.nq.gz
    ├── 2e9979c13f1e84a8bd1bcfd6ef890fe41c2dfd68.nq.gz
    ├── 2f1a9c103b6acd446f551ca1de1c384d57372ffc.nq.gz
    ├── 2f66431702b76ce7e85fff6dbfff1a2c259bd723.nq.gz
    ├── 2f6a4089d29e8c7dce16aa1fc38e4e3607304b4e.nq.gz
    ├── 2f9b7284cdae6b64650df46c37d0d0f6c46c0c60.nq.gz
    ├── 32d4017a2c860092f79aeeb7b3018d2824e74996.nq.gz
    ├── 33eebb71d0c2f939ba460126e8fc0e1e2e2eeb9d.nq.gz
    ├── 3605765dea7592d7aee3b56edd93bdba30df6552.nq.gz
    ├── 36509b42fcab3083d939c3b6ee200a16ed7007c3.nq.gz
    ├── 3662832029982761dfbcaec4e6ffa5226259e20a.nq.gz
    ├── 3777dfdd7e3eb20a694f1c60b019f8b135438cd9.nq.gz
    ├── 387fd8f8ea14a4ac3cc895309dd13cb1a20678de.nq.gz
    ├── 388c654933c0ef650024513e8d0bd6c313043091.nq.gz
    ├── 3890a0dd6931c114e01c93530b081884f6af524e.nq.gz
    ├── 3910a3249f1a1e2178ae8021514ee96ba99da44a.nq.gz
    ├── 3991c9d6eca7033fa9bb0bdc14793734d3d897ba.nq.gz
    ├── 3997d83e7cbffc58e6548b7ab97c2430df73a915.nq.gz
    ├── 39b4ccb8524f900e53abd1f7545af41150d1443d.nq.gz
    ├── 3a1c0bdcd8111e9dba2a1ad6ccfb09df0eac9576.nq.gz
    ├── 3bd7a82df53308975ab11c82a5729b6f9090087d.nq.gz
    ├── 3bfdc0f885a27c2bbd792cb94d6dacc79059d8b0.nq.gz
    ├── 3ce0dbd8bf1bf0b21d8be2e40860ba6e9abfcd02.nq.gz
    ├── 3d261d7542c103a8331bb6bf3b4ef688e9d53186.nq.gz
    ├── 3e9bf0cc33e58b73c0c77e88d16b248ff173c760.nq.gz
    ├── 3f02aaa3f1415051e296e64b0fb7ad36591c914a.nq.gz
    ├── 3f7893ddc26e51137a9b16cc2df11229fa1a4fb7.nq.gz
    ├── 3ffc9f4ff8e184a613b17a9a08f32d8c1606c15a.nq.gz
    ├── 41b2b502e9f96e965e23305950eb30625e2a8041.nq.gz
    ├── 424baf2b4d788c2eb7e705f43a5df04a8a8ca24d.nq.gz
    ├── 42505e3beabff876ebbb877e9ef540a58219754c.nq.gz
    ├── 4270cccd1c2048016d68f0b211f9437929b3ea8b.nq.gz
    ├── 42bfeb93e8ff398c8835dd1fcaf53b3e5d7cc969.nq.gz
    ├── 43c275dfe906b00ec3671ebbae9abe6b41e335bb.nq.gz
    ├── 44047b2b3f9ff64940fafa645e5c540330e2db5b.nq.gz
    ├── 445bd2fe64ef76dae633a2c304dc58f072d82421.nq.gz
    ├── 446af483334e0cec5d9faf5a30604a8f42a16621.nq.gz
    ├── 44cdbf7e419d42e9f9a26f2cd41c1c5e44ad07fb.nq.gz
    ├── 4519dd912022cddad2547bdcc92aea2e546882b5.nq.gz
    ├── 464d11719d210646c2415bf23ddc9c48dfa4a224.nq.gz
    ├── 4673ca547af935143e5a212461ea6ea1f4f69cf8.nq.gz
    ├── 46aaf12ccd39856b2849d4e9df07aceac4b5aa29.nq.gz
    ├── 47813d011a0d89cc3243e8a63557230e418797f4.nq.gz
    ├── 47cd24c8c6e524b670fa0648101676bb6b412bdc.nq.gz
    ├── 487156bcbbcb96b80c3a9ae9d5fd357b8bf7f06a.nq.gz
    ├── 487573e9653b607e123f8cef2e9c98e1e1d0a25b.nq.gz
    ├── 49c3b1a1b9c660ad9a119dc47e5e73e89bf599b8.nq.gz
    ├── 4c0639c3d0e7933871454cb6d9eca76cc0863406.nq.gz
    ├── 4c991c7863fe80e5015b4405e3c3344f9aaf9cfc.nq.gz
    ├── 4ca90a8bf7f663de1f0a06154662cfce84341943.nq.gz
    ├── 4cb32a4aa5687a773d61f2cf912bb96dcbb7df83.nq.gz
    ├── 4d6fbc813aa2c611bf0e61edf858db06e7dc3aef.nq.gz
    ├── 4dabb31a287c0bd734f72e89c32bae73c0a85182.nq.gz
    ├── 4e91eb6d2d15af04f066ccbed60025c2c16dcd50.nq.gz
    ├── 4f00e9c3fc7e6932c72b129e4ebfb6382f508612.nq.gz
    ├── 5001d1bef2fcc36cfb7792f596288025016b6bc1.nq.gz
    ├── 50784a9d410f77af7861b9f6652414e398ed1e26.nq.gz
    ├── 508eeff3451383bf6d786719a88237d22b3350f7.nq.gz
    ├── 515b9dff415e0e2a77d1ccfa796d27bd3cfd88b4.nq.gz
    ├── 523dc2b8b868fa53e3b960d7017908dae486eecb.nq.gz
    ├── 52f9e5415f8510cd6b35bb48f93b318d1f5dd982.nq.gz
    ├── 53aa6aef0486c9154724385de210043e5a141328.nq.gz
    ├── 55cd5df8721d98176ec13bf6c09b67efa153b0d1.nq.gz
    ├── 55df855620714efdfe7c83846e060d6d5fbcd85b.nq.gz
    ├── 56b4b47510cebba40ec428d50570608f2a8d3c6f.nq.gz
    ├── 56ee5fbf422fc66818abdf2fa0b823643878d17e.nq.gz
    ├── 5786a858f072961c92cd33e987a05e4d1ae3902e.nq.gz
    ├── 5793c1781f3b405504bfbc79acf1eed46784b8c7.nq.gz
    ├── 59bd3c3dc2da3f4bc6f924e382ce1aed7902edd5.nq.gz
    ├── 59d69290e921f8759a818170b7dc71df9cd1c88d.nq.gz
    ├── 5a6dcf08c265180a4f9f995224f8456d4ac00818.nq.gz
    ├── 5b2bb8d6e22d6fd1b0435ad1ce904b16d4cdb369.nq.gz
    ├── 5b3f1d3401516be9cff90d1e72f7273c68ae7459.nq.gz
    ├── 5d0ca25b829041c375134b1c5d0572e2aab46d79.nq.gz
    ├── 5d82f3a142fa65c126ef57bf9a6606a015f8c4e0.nq.gz
    ├── 5e96d66f208431ecf9fea28096ee92b4610d5622.nq.gz
    ├── 5fd2266736fb580bfc5f033d2e724652e39d589d.nq.gz
    ├── 60ed2bd3e9a1a15123338fed25547d3ba2da0eb1.nq.gz
    ├── 619fb7f4108e2a28c28d00bb8ae7a4ea59a20ef1.nq.gz
    ├── 6535ff63160fe0e8ac609b54983b19fad7811f75.nq.gz
    ├── 65c6b88ff6fc5315b882da581e12dcbb74eff40c.nq.gz
    ├── 65ebacbd527c4413f50065d0118a953ed0ae7e3a.nq.gz
    ├── 667c31a30d210b78c667139de917566aa5b415e3.nq.gz
    ├── 67a837e60c3b9c64028e2cf5c0ec47a762601f2c.nq.gz
    ├── 67b9fc9ca45933978209987ed20685b9a80713f9.nq.gz
    ├── 6826378053a24bd33b0cbf4dd63828a56cecfa67.nq.gz
    ├── 688eddb88230c03b539bb93acdd8dd56eed57f94.nq.gz
    ├── 691dd0f91fe4f6c31a276b9d41aefa1dac8bf535.nq.gz
    ├── 6997260758aa49e9aaf5435c139e32d39e464ddd.nq.gz
    ├── 6af0ca271706caad91f5dfac9dc0d133a8925186.nq.gz
    ├── 6c3b7aa3446eda32ffe0621aed381fe34032825c.nq.gz
    ├── 6d0b22d100f7bee11ba98645debc84d231d07ecc.nq.gz
    ├── 6dd7754b1f4c1988161b03e4ed175f8c85a4b8eb.nq.gz
    ├── 711b273bdb3fa099f718f0948b908efe7035e386.nq.gz
    ├── 71d90df86fab41e74f2e24ae247e3070f4d43d41.nq.gz
    ├── 71fc733b7284f7ea283e737506898b2461c08d4c.nq.gz
    ├── 7253a5ceee98e9a69d5e36d9d2e02969757bf239.nq.gz
    ├── 72cc50437eeff9d5e949237365ebb23f5b057285.nq.gz
    ├── 7366474a0fc512fe0c4a9be558e5d15168cadc5f.nq.gz
    ├── 73f137b2c9562e3ed74565a2ffc60e1d04a9560c.nq.gz
    ├── 75af2aa6c86e90f8bb842d15ec14a3ca1915f9b0.nq.gz
    ├── 7624620be798ed01508f3f7cfd7e5145088961d8.nq.gz
    ├── 763878497035f9e88a3a808fe76d74a25e218726.nq.gz
    ├── 766e5073c6071fea20a4c34c772e030c5f90d421.nq.gz
    ├── 774e45fb78c5b4841ee3963d508717c4c84ffe13.nq.gz
    ├── 77b5f509c05ae6a36031c7ad94a453d67fc55b3f.nq.gz
    ├── 781fff2b82d5aacbf94d2407d9a07a4152810450.nq.gz
    ├── 788a4ce9a15272410fec54cb473fbd78e6076f81.nq.gz
    ├── 788ff4cb2dec828ff90d94d4adfc414a1efb1001.nq.gz
    ├── 79aeb3019abe688096228fd3b95fb5b67a444809.nq.gz
    ├── 7b6a655dddab3f71b32d91760912c9fde7075068.nq.gz
    ├── 7e74909637453dc7f619c52dad8f4237c4c49b7e.nq.gz
    ├── 7fa2c41f063d15f24d4d28aa9910b7620d1fac89.nq.gz
    ├── 804acd9faf52af68403c0c73b047b45fae7d3178.nq.gz
    ├── 8052a1e908d35f44119f0746a0bf423dd4106fed.nq.gz
    ├── 80ad57333e3c35983b4db19438270f8745f4b222.nq.gz
    ├── 8156dd8328a25176689b8b983ae6172bb066df88.nq.gz
    ├── 8183ca4b0cd2a3c52df64391914ef27927fa9bea.nq.gz
    ├── 818ef8aa63131b9fb0c7a62584280f5fbe3a715d.nq.gz
    ├── 82bc9a723c839baa803ed0d250ecae8843e6af34.nq.gz
    ├── 83421f23c279c8398d1bc5acf7a046488f613b16.nq.gz
    ├── 83f925c8c12d138f6ea7b953b8a53a5fa0ddf36f.nq.gz
    ├── 84ec695f5c65b3c8dc0f69fdcc8ae16c5712001b.nq.gz
    ├── 85910486aad1a7affa2425e7f076c65cd6faf74e.nq.gz
    ├── 85cc134d7d8c5ab6b23befa3802347fda22ab03e.nq.gz
    ├── 85fc8385fdf41fd0b67f7a6bdd07bf442ee9edf7.nq.gz
    ├── 86484733c0cd9696aa10ebea3886390d15153d04.nq.gz
    ├── 866e36f9b95d1c67afa28fc3bda25dc062d3d243.nq.gz
    ├── 8770e26c9e67d932cddd798fec1f44a59a9d7512.nq.gz
    ├── 8898fc7322a5f5bd44457f0261c9bce824eed66a.nq.gz
    ├── 89588a16fde6b24f968121e882ba8d1392408ce0.nq.gz
    ├── 89a9b368168acb7f23c455a293c285ac81e09237.nq.gz
    ├── 8a03c22f52dbcda63364e88a4e8240bb8ba6190e.nq.gz
    ├── 8ad9c0eb27040675855f01840ff935ae5a762b3f.nq.gz
    ├── 8b0694ac24158dfdcf7b4f7982e9778268c4f525.nq.gz
    ├── 8c008d2b77e74865f3b7aefe60953cf5fbe830ea.nq.gz
    ├── 8fff8277a662120863f8c02c209e17dc56aea39b.nq.gz
    ├── 9139c23d8a6f822f83a275d0ab7f5a98526a75da.nq.gz
    ├── 9198bad0212317da5039ac619b40cf7cb0b01816.nq.gz
    ├── 91f2bfcd296504e56d6ffd2e70713c172e9a645d.nq.gz
    ├── 9291751aed0dd46c4de2cb6000d00989aa8e1b66.nq.gz
    ├── 92928c1a0381858db0b2d92ef7a247e042792512.nq.gz
    ├── 92d0b99999ca16ee9c45b5c1f324ce6df03f4bf5.nq.gz
    ├── 9318bceef2cc956792892e948ee4554a4e7754f5.nq.gz
    ├── 93fcea9e5ad45681558a3ed4d14e741556764ed9.nq.gz
    ├── 93fdc6c10dddbfcbcd740005c96d41cecc4414e5.nq.gz
    ├── 9444e7c8c0e0d13ec4505aa49132ef70b4fa1ac2.nq.gz
    ├── 948ea60acfd9934a498ef72765f3100e11afd284.nq.gz
    └── 9521a33b6fbcba68992d82d9fa1a5d6cc0edac45.nq.gz

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

[pydata/pydata-sphinx-theme](https://github.com/pydata/pydata-sphinx-theme)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
