# Repolex Knowledge Graph of allenai/curobo

RDF knowledge graph data for [allenai/curobo](https://github.com/allenai/curobo), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/curobo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 87e857d46fa5398f268c7f31d26566351be8671d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 87e857d46fa5398f268c7f31d26566351be8671d
│           └── chunk-001.nq.gz
└── blob
    ├── 004cf8a2bacd4c7f595351fb7b8fe09bedb5f586.nq.gz
    ├── 005f655ebdc42bf7edfe958ca65c63f760cdaaf8.nq.gz
    ├── 007daac94246ab82139c59b670f98d6ab2319327.nq.gz
    ├── 017f72662070fb3f00451257ba97838d88602428.nq.gz
    ├── 024fea75a051d6f3f55450380cba1628e6f9a8d8.nq.gz
    ├── 0302122d1dbd3b58146c498fcefcafb7fadbda3b.nq.gz
    ├── 03138533a55513484a02b8fe1c81a2a279f13af7.nq.gz
    ├── 034886d265387c672ab1a337f110aa44b3ee4933.nq.gz
    ├── 037f0df876baea266d70b7cfe69049ad9cd42303.nq.gz
    ├── 03d4f6d126d24f9a36d33261cfc2196a7cb8e59f.nq.gz
    ├── 03f0ee0f1a9376998f6a78750d1887e4c342c058.nq.gz
    ├── 0575b9c1445746c9db784d2eaffc70a1cf00231c.nq.gz
    ├── 0666faff73d81ea07fbb7658533a57acbd65332f.nq.gz
    ├── 071674986e9266a82bea064d7b88dc1a85bb8ca2.nq.gz
    ├── 07381e29aecd02b35a1077ed023eb8faf1a68aa1.nq.gz
    ├── 07d901d149d35c92090581f07a478c26c71608fb.nq.gz
    ├── 081448d10570cb8fc9bfa724e090c996a3d81b20.nq.gz
    ├── 08b7db4465097571d8c78385c8e30d3fff44dff4.nq.gz
    ├── 0926bbf786bfc2fe301d9be89fd67ac98ab769e6.nq.gz
    ├── 0a35a8ae68fa0b8d24507f2cd2a142a59b8fc91e.nq.gz
    ├── 0b594233980038e26f2e6ef708418c01586b5218.nq.gz
    ├── 0bb6c1105eafa2bae9c8224edd3e2c21fe4f4ee2.nq.gz
    ├── 0c4814d9ba893ff5ab4828b35dc42d422fc02a35.nq.gz
    ├── 0d8e1bcf055e86f815d5e6bf598ec4eca0e61f4d.nq.gz
    ├── 0db6472dfa5bd8c6ac0ec31240636a4cceea1edb.nq.gz
    ├── 0e5e441a387f5c067bd572dd8f935a2db5b8ed49.nq.gz
    ├── 0f2e28803ed54e81d5a73c9fa4d947811d6a9432.nq.gz
    ├── 0f35baff3b33ba37ab98e32d306b62de0d9aad44.nq.gz
    ├── 0fa9b8a01e1551e7732bab4588597e4e671b042f.nq.gz
    ├── 0fc865d2a4d7d6badfe290d56c1a86b86dcdcf18.nq.gz
    ├── 0fddc2476287ddf2333bac3e7c2793a99606961b.nq.gz
    ├── 10559dfb952d1e5013bfe660190cdb9ce13b2189.nq.gz
    ├── 117c75444ed3227f72526715f2c749fb805e6037.nq.gz
    ├── 12310d3bac79393e06d3072c6251683948cff2f6.nq.gz
    ├── 125502c0ea7cf0aa503b23d6beef7b48bf7a75a9.nq.gz
    ├── 136ff7ad099f2b4bcf85259bc45d4e463d20e7b7.nq.gz
    ├── 1375e4e8f379978449da10ccbb14dd6555074b67.nq.gz
    ├── 146b69b50b2fd61546c3dc7a4860a037874f084e.nq.gz
    ├── 14abaa1781050cfc541be50c7ff3af72fb499a45.nq.gz
    ├── 14bbff58f2f200dd1e1b97ba5226da3f768b69e4.nq.gz
    ├── 1544c3bdad0fb69fe98c4f833736732e3d5634bb.nq.gz
    ├── 15846e60f8fea2b02848fa6ea872e33763be7fa3.nq.gz
    ├── 161699310ce904e4c80db8cc2007d0ce544cda61.nq.gz
    ├── 16637dfdbe3bb08fdd575e75f8abf7469d190bbc.nq.gz
    ├── 16d288d0b07fd8cb25a67062c2d387eb81fe051c.nq.gz
    ├── 17532f8b2337d284b57814b0b04df1cad492e7f1.nq.gz
    ├── 18aaefa73c7753645fcf0cd26524fcad23be2500.nq.gz
    ├── 196a3ac3be6e70647b737a13cc4a807e1f22ec46.nq.gz
    ├── 19973e176bc1d250bdab40982c6164d43094eb08.nq.gz
    ├── 19a9a5b3105740e3f7bdc6a081488bb59388eff6.nq.gz
    ├── 19d2bfb3527ac45c26a563990770e1a5089cb499.nq.gz
    ├── 1ad6ad137079194e135e3960a6e5883eeea4f3e1.nq.gz
    ├── 1bc38d9ac76b54e4518d8606a1d37ca36678709a.nq.gz
    ├── 1bd99df143a6809d4ae9d5cdf1a5342ce2fbac99.nq.gz
    ├── 1ca27b5261c8b0389ff9f81fd3fc14efc7590a6f.nq.gz
    ├── 1caa346f8ce62bdb2b725812bd1d9e55f9f1ab33.nq.gz
    ├── 1d1e9d247a563a18dd9912f22e5c6635628385fe.nq.gz
    ├── 1d903ea195a15048bf0384a0c73a0c153ad93e8b.nq.gz
    ├── 1df304c0eb9e8630f3be09b39154c1955ad0771b.nq.gz
    ├── 1e13c2cc731cd9d3b32be7de916dcadf2f316349.nq.gz
    ├── 1e15515ef499f0b0db4818b9bb76d363e4a5df46.nq.gz
    ├── 1e7e7105c59e5ebca83ed0b0b8eda61cffe12f32.nq.gz
    ├── 2047756ec662f051af90fe61266998bf16e655fe.nq.gz
    ├── 2069dc04341023727c17f8dc8f59933ee45345d6.nq.gz
    ├── 211a78fff78500f119bcdd1d916159534a9be88a.nq.gz
    ├── 21714adf7d05bacd1b26c9e66909de9ab5ee86c8.nq.gz
    ├── 22be5735a01ed462634573b86fac071de36c2606.nq.gz
    ├── 23453eae1a30c7a908b5f2c91fbe06113c15d8c9.nq.gz
    ├── 23b8a1603ec570bbfc5410daab786abfae869014.nq.gz
    ├── 23eb948c1b8f810d15c808264ee87e7ce0dddde9.nq.gz
    ├── 2483da94c077d3cb5a078906a71730bda836e628.nq.gz
    ├── 259bc711a3cfe08c3f1ee118b0d85c9a9dd91a39.nq.gz
    ├── 262ba1649e31fa5891a76259d83459c9dd3c35fb.nq.gz
    ├── 2651a66d988da79d1c30bb5655fdd85e95e54a94.nq.gz
    ├── 266488615dab71a096221eaa1aefb73e22708454.nq.gz
    ├── 277444e009f8be0a67d8c28134599a5db6b2e567.nq.gz
    ├── 279662554828b615d79c6124b8c30cd04dc3f300.nq.gz
    ├── 27eb8f50713e075b4704013234ff6d3a604b023f.nq.gz
    ├── 28517a338be35aa75bccab6dcf2347b8f3b13d3f.nq.gz
    ├── 29a457b7e183f3170e5258220c21f7533b437167.nq.gz
    ├── 29de0091bdedaa5111ecb4a5ff1806540d5b6627.nq.gz
    ├── 2a70577fe9643d21db62981d9ffe4a25fe89084d.nq.gz
    ├── 2a816121f54dffee64fdb49dd2885f1088c59759.nq.gz
    ├── 2a83f8a2b790dcd192fe193f0921bd515848bf75.nq.gz
    ├── 2af2d568a53700214beada4358fc086844d32335.nq.gz
    ├── 2af83aac020ec77e46d734422729f2e54811b67f.nq.gz
    ├── 2afa86568142f0b614e766e149fd19b5ca23ff43.nq.gz
    ├── 2b841b3a0b6b1c0409a6f1cda7f6eedfcf4bdd02.nq.gz
    ├── 2b9979fe6a577660e11b5250a0e06141d0820826.nq.gz
    ├── 2ba2de1fe30db401b3970af41eee313daa283880.nq.gz
    ├── 2d03a4667ddb5933c401d2da9fe7c5f0ee51a43a.nq.gz
    ├── 2d461351e60def06c2415200ae2d77c98e00781f.nq.gz
    ├── 2db25af90ecf3a43388f22482dd8344c34380df5.nq.gz
    ├── 2e7b05ae60ddaab2480bbb89f9320f690b9cd7ab.nq.gz
    ├── 2ed80deb41f330c30348c4fd2f2439e8bfcfef83.nq.gz
    ├── 2edd8a4b13619e6162d05b01ae2623d73470afd0.nq.gz
    ├── 2f78e3bf9bf77f0f473a7983955fa5de46e41e9e.nq.gz
    ├── 2fa8f30681bfb95536a392206964c144c407b489.nq.gz
    ├── 302e9fdafb9bea77b328d01ac443eb6ae2a6883f.nq.gz
    ├── 303d976159f4a0f43a5a833e654629b879f55763.nq.gz
    ├── 307ea40b6de25b3a5aa66d70e1b950e3c2c064b1.nq.gz
    ├── 30cd586c693990c179b25bc6511120b8235e4264.nq.gz
    ├── 312311c4fd037ada6e8fe8c3bdeca590db079d47.nq.gz
    ├── 316f6108116d472f86ffc970cd6c050b79076351.nq.gz
    ├── 326b1d797fe0725450391d05fbd46f1cdcd8a8ca.nq.gz
    ├── 33365cf8627bf74af9ffd6d09241ec770f5cc2ce.nq.gz
    ├── 3470f039a258f129d9dcf8c47fb15295cafa9b8c.nq.gz
    ├── 34881002a4e11f7cacf3e177edad923337eb7cae.nq.gz
    ├── 351bbd05fb4a051bcd55f60e6660b70be0d64a2b.nq.gz
    ├── 36212884dca2cacc2722dde4fa62a3da8c77810f.nq.gz
    ├── 3799f503d9f3208b085a0e1010edd2460fcd9a05.nq.gz
    ├── 38edad10d5917028c3aeb2d4884d688cbaa11a59.nq.gz
    ├── 392a21d5323b9e53a937e852c8d85bafe76b97c0.nq.gz
    ├── 393582859bf2e39e3972591485d8c688722e9dec.nq.gz
    ├── 393d4894eae3d91c9cc2530e044a0df10f8001b3.nq.gz
    ├── 394b0387818ffa5181a368180eeaca64d87c2941.nq.gz
    ├── 3aee2ed232cdffa0d3331157e3c5c7cfbdeeedca.nq.gz
    ├── 3bbf04a6de017405f402d8b95c3b22d441389a57.nq.gz
    ├── 3d5e6001f2176460131eb1c24cfc8e1d33254c93.nq.gz
    ├── 3deac3d92f4902681d2372f3319a587047aaf81b.nq.gz
    ├── 3e648322d6bce4fb089f146eb96bb442e7ff5da9.nq.gz
    ├── 3e96972f37c2beacd51ca1d3d1efcf39d9d61411.nq.gz
    ├── 3ee4bf0dd929b56682b42b1e9a85a91d2e829248.nq.gz
    ├── 3ef56dcf17eb02fa9870e22f411d2543de2f49ff.nq.gz
    ├── 3f9b1bbf924d26241b2072af7db7f5722218d394.nq.gz
    ├── 3fcc99d706a03822ab2d906f048eeedbe68eb166.nq.gz
    ├── 416da766a8a5e44d78e4519f28af41868f04b017.nq.gz
    ├── 41fb39f89ec100126b54a4c9c55142a72fe13076.nq.gz
    ├── 41fd767d285dbbc9c73985ffee3ac4b54247f6c1.nq.gz
    ├── 42ff7baa0b06561054ee03a5da08aba8886df441.nq.gz
    ├── 44ce896e6b5194de0a569779e5dd2e8766552685.nq.gz
    ├── 44d3fc1d1807fbba9d9be3a1141bf163b9db20ca.nq.gz
    ├── 460ad03e69a5860db6fbd9062fa511f8d91e8430.nq.gz
    ├── 462aca288b34b8aba99bd8278d739afc185953a1.nq.gz
    ├── 466562b73fa90db3ae1ebeeb2c3ac514c5b3d6cf.nq.gz
    ├── 466c18a2369a6c641a97360745403c723e26c3f1.nq.gz
    ├── 476e6e9252a3ddeb294bad2f0747cfcb97e28d6e.nq.gz
    ├── 47dd567b4a47440102b29a31b0de29862107286a.nq.gz
    ├── 47f73143cb694fac21af7035cd36b97455d7ac6c.nq.gz
    ├── 480491954b09aee56379f1829c5f21a6a96a2d80.nq.gz
    ├── 49012b6184503be5c812b2f7ea644c64f476ef66.nq.gz
    ├── 4927c9c3cdb9409d030b06064088569430faf514.nq.gz
    ├── 4964b80bcee67ee726d8532ca786bd3e4e925b48.nq.gz
    ├── 4a2457eb25c573552da03f2b80d88f091f0d8768.nq.gz
    ├── 4a91d5b7bd2c2709dc0ddbc0a8391327570fbcc7.nq.gz
    ├── 4ba6cc23ec2aeb2f7e9b8b05ae2a972ed73c1d2d.nq.gz
    ├── 4c07c3ba90b95aadfb88676ebe4f13aee4fe856a.nq.gz
    ├── 4c2a9f4c01e8178bdd3d1d924486f4322b3c71c7.nq.gz
    ├── 4d0cf78681afd94ea14387737cdae4c377e52a8b.nq.gz
    ├── 4d3448011f0c145e1f4d284f60a7a585627d0505.nq.gz
    ├── 4d466b28d3861fedc2a0ebd9735c1779501d35f4.nq.gz
    ├── 4de461a09a97156c83f665ec6e84a532e7da3d8e.nq.gz
    ├── 4e3af8548de5f6e48f722fad35d3e2182c81e0d6.nq.gz
    ├── 4e85c7d9b790d380cbd7c8f1fb4d6bfbb0fde3f1.nq.gz
    ├── 4eaa7dba1291817b44551da862aadb5c7d4823ba.nq.gz
    ├── 4eb1a12a4829082abba813e2e6a832cce25f6555.nq.gz
    ├── 4f19c840371f5e5ece42bde7876de650e9ac15cc.nq.gz
    ├── 4f933321f13861dc07aee7b97c9f52049209ef8a.nq.gz
    ├── 4fa3eeb9ed53b2b3511a1a5301d6bfdafb1e082a.nq.gz
    ├── 51538f42487fa05871507d2754dcef72d3a7a8eb.nq.gz
    ├── 52473e0cadcdcb58fd07fe2b2447ac14f8824222.nq.gz
    ├── 526b550300dd4512b90a181fc769a0204f2812ea.nq.gz
    ├── 548dfe889cd4d4a5d0ff3fcdf199f5353347c434.nq.gz
    ├── 5635fe7a411c582579a68ec597630a5f77fa799d.nq.gz
    ├── 5648941c146594062c0f9b2e43fc50f6524b471a.nq.gz
    ├── 56dbabdf2b6e0652d70e23f4412800d6d3ebf137.nq.gz
    ├── 57c13f1b803c3fe67abb2089992deef729dfd7c5.nq.gz
    ├── 57d15dec96fbd73864f6a0a52313f8d0132f08e5.nq.gz
    ├── 58fd74c6116f4fe5d655684bf2406deee1acbd41.nq.gz
    ├── 595edb1afac1ac4423b66e153fe0784474481f47.nq.gz
    ├── 5ad08e67b8b13ce4e8900020755df6539210a704.nq.gz
    ├── 5af1ca4d549537eee4567d188f6c37a12dd335c8.nq.gz
    ├── 5af3dea8b5fd5d41de6a5fa41d50b87a998dbb01.nq.gz
    ├── 5c6319336ab72b67b82743f59ebc365155d03e15.nq.gz
    ├── 5cbbf50613b6759afbb21fad233bde3515c1fae8.nq.gz
    ├── 5d3888390f07ff6793842a472278ccc029ce67d1.nq.gz
    ├── 5e51d9705698385775a3b6e66d45c7f3f647030f.nq.gz
    ├── 5e61e4ca11d0f3b07d96f8b5c4dc5311f5eb2a3f.nq.gz
    ├── 5e6a4b87b842b1846ee5a9b285a9141972aac489.nq.gz
    ├── 5eaf5c8ec2155135ab9297d51e3dae6e5e280675.nq.gz
    ├── 5ff80571ce1a479a60686b131b63dc0da9c026bd.nq.gz
    ├── 600553cdd74784e88ef64973c806b10b67417a7b.nq.gz
    ├── 612058c6f589a7213d0da8cf21e25d85877a562e.nq.gz
    ├── 612fcfe3620231a5e69a564bc63b3a55039ab4a4.nq.gz
    ├── 62a4f52e7e8f351c2069dd20cf65b33a40bc8038.nq.gz
    ├── 62e1cb96d0ac21a0455cca2a1f1518b6b087c716.nq.gz
    ├── 62f317f1106bb6fd50b5756faf7632eb8bf39e3d.nq.gz
    ├── 646004ce11cacbc3007d9cc2ae176a8f201e1050.nq.gz
    ├── 6464df77967f4478e5d07e1d09c52362a9281586.nq.gz
    ├── 64945a12415afad4fa983cdd7afbf0ad5759f974.nq.gz
    ├── 64bff3127b80ad599fb667c6c712da288e898b80.nq.gz
    ├── 6589ab426586308d79b3d53df09d59b48eb568e5.nq.gz
    ├── 661f3d8c38716ac17a702746f0779648f169eb41.nq.gz
    ├── 67054fdd41b06226b701de915ffbdff5ca0f5b1d.nq.gz
    ├── 67928fdada90e364cbf0f2671e4cf80cb799e403.nq.gz
    ├── 6971c552822829e7ee69ea90d56e28dd55ed5e4b.nq.gz
    ├── 69ecb7695c73980fa9e76563d5a66fca373db44a.nq.gz
    └── 6a00bc5900a48c0ddb8f76302adda1acf52264cb.nq.gz

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

[allenai/curobo](https://github.com/allenai/curobo)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
