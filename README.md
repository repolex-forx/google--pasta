# Repolex Knowledge Graph of google/pasta

RDF knowledge graph data for [google/pasta](https://github.com/google/pasta), parsed by [repolex](https://repolex.ai).

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
rlex download google/pasta
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f007c5394db77e8606a3feaafd1e09c724376550
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f007c5394db77e8606a3feaafd1e09c724376550
│           └── chunk-001.nq.gz
└── blob
    ├── 0720a9d86aa000eaa18a0d7152b34e6aea1f3e30.nq.gz
    ├── 0734c1f0e0c7f61ca7db4a458ae9f6bef747ca5c.nq.gz
    ├── 08eeacddae5ad2171437987c2b1f9ee25b854e8c.nq.gz
    ├── 0af20709f00c1ada3aed1b07960317fdcca70619.nq.gz
    ├── 0d6deda9ffee6fbac4a1c1d5d368160763298374.nq.gz
    ├── 0ed266ce6e73897a4789f34bf9b4fe0733d11e25.nq.gz
    ├── 0fc84c1ae231b976413068d9964f098f7d5d445d.nq.gz
    ├── 1092df19359abf456792b54ecf10bc3fbdc5aa73.nq.gz
    ├── 112204aedb741dc9c0c7a400633d35eb353577af.nq.gz
    ├── 11b19dc2c252c0132ec5ad73c5d340dca7cc9c14.nq.gz
    ├── 1215d5193938d857cc69685a0ff4d2bf738aa075.nq.gz
    ├── 1337c940e5cc002be59b04611cf195e18e7b2b97.nq.gz
    ├── 138d569534118aa964607d441e09e7597cbd6a66.nq.gz
    ├── 14ad211f6e0499c7f71c8bdf71cc62213b2dfbd1.nq.gz
    ├── 16ea3c75467953d5783785e4fb32f8f3328e601f.nq.gz
    ├── 17c6f9196f3f6b4a672540ea3070631e68743019.nq.gz
    ├── 1805eb75f06f3f6baa2b50451d739525ab50d73b.nq.gz
    ├── 1827c9f2f758b58cedce9e294ac1e1e47c40480e.nq.gz
    ├── 1a4097f31bde228e0bf40d01de608d9638a66527.nq.gz
    ├── 1a7700ddb32c591596a53226bd19420da9d434b6.nq.gz
    ├── 1af66c956a5befa864817e6ea6241f3387b36fb2.nq.gz
    ├── 1b25516d5519bacfd3f976528c7601c63e53b6a2.nq.gz
    ├── 1c7fe4bb1264abd3bbfbb1c9cf21e7f9c7cd9302.nq.gz
    ├── 1defe5e74c15d815f35ca2c661db7736eebbea8f.nq.gz
    ├── 1f03b22b2c8b5b9fcacab475e6330c3f86e97dfc.nq.gz
    ├── 204c7d8441a624cb1df62e26a3b6a917f8e949a2.nq.gz
    ├── 217ef9bfe8471528f7983000fd6d93c67b6ae016.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 269377d30576683af57620a8713f182e6461cee3.nq.gz
    ├── 26d22bcdf346caa59fbeb5d8ef405e70673df188.nq.gz
    ├── 2787e3a8a8962d7f1a0d3bd42b02251e827c42da.nq.gz
    ├── 294883436f4b101a0310bfb54ef1728b8a8e3472.nq.gz
    ├── 2b54d69390e9faeaccbd6ee0c653842d259ed88f.nq.gz
    ├── 2b885b99f333a236115afeaa33dfcf6b3679acce.nq.gz
    ├── 309e482d1e2bc5ec92bd446e6e3abe146f76a330.nq.gz
    ├── 350b61c52cac0915f116fc8ac3d269ef5bbe43cb.nq.gz
    ├── 35a715a66f63a5f5303e6641e0c6fd74c5be1dd9.nq.gz
    ├── 3741f42fcc8c25394c3b0eb16fcb9009d224ecfa.nq.gz
    ├── 381e4d9b1030c0f001785dbde08c30e17e4849e9.nq.gz
    ├── 38633147e8b86a174c422f6027e16dffe83bf025.nq.gz
    ├── 3b01e56f52323e519d1caa095243ce1268d8dc6f.nq.gz
    ├── 3b56722c8a060a42a6850e5845fa3c7fe2e6cdc7.nq.gz
    ├── 3da6f4947f7ed3d76e2e46d0fd5c6ef4a00624d0.nq.gz
    ├── 3ed0d7313397fe4cd1cc31487efa6cae6811655d.nq.gz
    ├── 3f778d8fe67da2873b437bff4bee2fcba3d504ae.nq.gz
    ├── 3f9a5823522fa0b181e283e6cfc53db1192347f9.nq.gz
    ├── 4058fe102e4bf84c1c27aa7768ed359abece856b.nq.gz
    ├── 417c462f0c56d95243f0b66e6bacb023ed78ef2f.nq.gz
    ├── 420e3d2091d8b9b22bce94d5f4479c3321caa032.nq.gz
    ├── 42a92dc77c9b4b15c2d543e424a5a19d9cfe71a5.nq.gz
    ├── 4492e9c15af8c7ab9d8528ad54d3219778e78c14.nq.gz
    ├── 44feee28d051b943ed1a18d42e34ee3801aa96ed.nq.gz
    ├── 45a24021fb386f268bca29ca35ab6a63495558a6.nq.gz
    ├── 45baf65a41b3c18e4c3a1aeeae422cbf2cad8a6f.nq.gz
    ├── 45daad979059d78ca02b4e5fb3fa834435b32a49.nq.gz
    ├── 46bb223b925db0c4bff8e846ee882e251c4e2cdf.nq.gz
    ├── 492241bda8c846f60df4527f332704d018f6b401.nq.gz
    ├── 4c82ae297c4d8d674bb993f8d7f719df564bb05d.nq.gz
    ├── 4dcc3687955774e70a081f4d547fb75a6d16f935.nq.gz
    ├── 5238373b6bef0de5749a02794924db5db1c2fca1.nq.gz
    ├── 52c267d04a87189a5bc07a04d3e86a262214d6ef.nq.gz
    ├── 52e9bb7d65999d978088ea8a430e1683b65e3d37.nq.gz
    ├── 53471006621666132c961000e3acc064d2ad6aea.nq.gz
    ├── 5353d29fb468e7b54e694ed0554e07fd9832e5fd.nq.gz
    ├── 535bddb2c2d4af622fd8b40ced9d7824b9c0d1a1.nq.gz
    ├── 53ba6fb5a17c663aed0f038082c289887fc42ba3.nq.gz
    ├── 55432c845cb804c7c655e03b9867066e7c879d02.nq.gz
    ├── 55d71436d6871b183320458214cb267a6f8fefad.nq.gz
    ├── 573599c4b839433e65cfa2c774323ac47cc06fb2.nq.gz
    ├── 574ef03e8023b4eb6093ca8ed5186ec908439384.nq.gz
    ├── 575b96ae30b3a106b989ceddc67a759c485b01b7.nq.gz
    ├── 5767b5c0cb9300c98ed9f1fa77e7d3985d2257e0.nq.gz
    ├── 585073aba14e8c347eab2d2a659602acbf4e7fe4.nq.gz
    ├── 5a83f85911b2d458051e64d08ba2713662c437bf.nq.gz
    ├── 5bc346d63c2d7149bdd2e5afd98da7618336be63.nq.gz
    ├── 5eef296a3fb246ba47754f1e4174c3b7e2a51c0b.nq.gz
    ├── 5f87cde7805f824d758447f974c1d884d19a537b.nq.gz
    ├── 5fe3d0acb5cec4acda67874b9bb95a928c874441.nq.gz
    ├── 6024148761b017d3b1fca5c031c138e1bfdab805.nq.gz
    ├── 606c9c61d73f469727972d695c8d166291dbdd0d.nq.gz
    ├── 627c7070453557bb812a1dc7738ee1b8b102ccd3.nq.gz
    ├── 632e495c6501546ccad14a64744801cca16b12b6.nq.gz
    ├── 6347490b480130239b4521b8478c27ac7c306105.nq.gz
    ├── 6494f18a40d08a55a7062fe87e80ce5e172cfabd.nq.gz
    ├── 65d0d5efac31e22361d9bb26c97c2d9e4f61c987.nq.gz
    ├── 67168ee93ecb42edd43b30b53f340d4a5cff46d5.nq.gz
    ├── 6905f2f5fe281fb28ca9a465ba73a032d4dc6874.nq.gz
    ├── 69ed8575d58c45892d71748deafefdaf4db8100c.nq.gz
    ├── 6ab4660245eee4fc3ed758dc9548ed4bfa232960.nq.gz
    ├── 6b91f9e7aada017b66059b5231b967e56daa1e42.nq.gz
    ├── 6f8023a1ea6b888e8435080ed95771fd1394bbf6.nq.gz
    ├── 6fe3f3978d517e549e84c6dc6210f9f4f342c387.nq.gz
    ├── 70838b079082932d2b45cacb69913eb39ba87a12.nq.gz
    ├── 716bb5023b4eceaa653a6b7a9a1f9528941ffe4e.nq.gz
    ├── 75884c258eda89d061f36d136a24d35b614f5ebd.nq.gz
    ├── 760a40b709344bac8ce32a0bd72f6337748ec867.nq.gz
    ├── 76b897fd6f10cd7cf95fadde8bb2009b02ed28a3.nq.gz
    ├── 7c61112de0302201fda9a95ced38fdf751bc18d9.nq.gz
    ├── 7d69222a99376531ec3628c3123698a40da16d6d.nq.gz
    ├── 7d6e15775ab673546704bcafd7c89430f1c755fd.nq.gz
    ├── 7ea2d9f67d941ba80e2980086932f49dcedfecba.nq.gz
    ├── 8171d08bab5c3d9a2ebffc6b8a9d88a13b67f258.nq.gz
    ├── 8251b49ab449abbec0b6de72605ec13bee6816de.nq.gz
    ├── 8299a5e9d809643614a8be0d4f9d911103ca1da7.nq.gz
    ├── 861eaf3b465d1d4f81c5cc9ca2160eecc72f0b1d.nq.gz
    ├── 86aa95db8d5a51b288bdf66cacff33d10c724f7e.nq.gz
    ├── 898850cd8c42fc4f96672ab7db1383f22516db7e.nq.gz
    ├── 8a91c838714621b9894ec74a50c21f39e8667a48.nq.gz
    ├── 8c22cf940e087f05394f8828ec12542215d54eba.nq.gz
    ├── 8ea489cfe6732a2feee10f015d8631f1bfb16f6a.nq.gz
    ├── 9028f0c15b715bde05aa2edd4a67f249164c2063.nq.gz
    ├── 902e4218be7e19fc1044188ffbe8491e2c81fa76.nq.gz
    ├── 90a21507f950684880e775d259fa5d91f74f0916.nq.gz
    ├── 91fe83d6f974c55f6a257d6ec2d0f0818759d790.nq.gz
    ├── 9563e76801e2e27fdc123d1264a6bba54ccf408c.nq.gz
    ├── 9719aa19ea84ec0bada4eb87706c0a88cfe012ee.nq.gz
    ├── 978d5e64f9a4199853f6e2ba2ba9afd1316e39f0.nq.gz
    ├── 98117d88bfb4c425fad4e90c48539fccc09b1579.nq.gz
    ├── 986954b5d3a2cc7519d897f9191ce2d5b5309220.nq.gz
    ├── 989637134a4af767442478fbe24e7330480a3662.nq.gz
    ├── 98e8f29d9e87b15ef087390ebc4b46feb3264cf8.nq.gz
    ├── 9963e127b757414a46d2b084f81c38063e163c68.nq.gz
    ├── 99b7f56805cb3930188fe0e7b3c9919edf3638df.nq.gz
    ├── 99bcd8bf2d1539fe55fd2d01d2d1b42f3338a3da.nq.gz
    ├── 99e2226d9e55ee1d6231974abe8eb7526767689b.nq.gz
    ├── 9a01ec7a327b7b2fa733038cd0b09918b18562f8.nq.gz
    ├── 9a9d1b494bbcc76732d887aebd7ccf94a568124c.nq.gz
    ├── 9ade4b59cd2984043c0405a4db2d1ecad5439752.nq.gz
    ├── 9aee25a66cc7dbc11d0d39446af3afc04c064d59.nq.gz
    ├── 9b3be17cc83c842917a2e5c623ed2d558981cfd8.nq.gz
    ├── 9e7f66c02776ac813c56875c456d6350f056b1c5.nq.gz
    ├── 9fa21027f821fece0090d4d3bb2b79f13e4bc05d.nq.gz
    ├── a24fac1cdb47b984b4d67eb4cf1b8867cb282085.nq.gz
    ├── a2f0532f50bff3828972f669df7058a0e6862b50.nq.gz
    ├── a376053cf9ddf46690e121204dd604b992ef1a10.nq.gz
    ├── a47ae540a23997774189ec70a3c786833ce0f288.nq.gz
    ├── a84997c5853bc9798995e867e6b73e19c1d2bedd.nq.gz
    ├── a8ff8945472b1a510bbad7eb9c21624f567e0d17.nq.gz
    ├── a9639f38ca6481df3b40e02a8ab79c20ab0dbfc5.nq.gz
    ├── a9974d83cc8718e314dc4eb242d7a91bb42b9fa5.nq.gz
    ├── ab5ea09442f06c661ef67af85d30c943c7435027.nq.gz
    ├── ae23377c3890cdea78fafc65c6d3fa2d710cca68.nq.gz
    ├── ae285f92c8fcc58a4086d34af5e39b7a662da11f.nq.gz
    ├── ae369c6a6a7ffe04a5f5988bd9a00115e33f2691.nq.gz
    ├── b2baae797e9411f1383d6f2814c6d02c807a1444.nq.gz
    ├── b33a76fb8786fc4a7382f1c11d8d58218eba5660.nq.gz
    ├── b36a064ccd5caf7b5bb674bfdc2632e179e4e639.nq.gz
    ├── b4c2b5a6e8cf4e032a0611076922e0f329fd09ab.nq.gz
    ├── b52bd00dff9f62b6ea94bad63aa933dce8253651.nq.gz
    ├── b68f584e4251c5beb295f9e677a22271cae5694c.nq.gz
    ├── b88327122a15af0ac43f9d0621d0b73e0cdd55cd.nq.gz
    ├── bac9a74c708b4ad67a32008a04c53af7b00035a4.nq.gz
    ├── bb85563d8a02341077c86da1d1b0e51648602681.nq.gz
    ├── c1cf0c8adba67ede280ce9e0459bbb907ebe87a3.nq.gz
    ├── c1dc6d7c3c21eb22ccc0ac52caf292ab74168670.nq.gz
    ├── c23d30140320ab184f5312aec1ad4fc5569de6d9.nq.gz
    ├── c3c623b11e7ace04b7a958cec45714eab94ca89e.nq.gz
    ├── c4cf4ed8916af7a3eb3f16d266508b3a866c18df.nq.gz
    ├── c4f85494165a806400332437fa9cc10fb95c3f7d.nq.gz
    ├── c508382feae5d59704d982669e1fc9f254b349ca.nq.gz
    ├── c5f3b53bd6159dea6c582b5184de00c47e004f55.nq.gz
    ├── c71642cef41cd3fbdc1c62dd9c669a4752d923b9.nq.gz
    ├── c9c0a16d0f6b581e0651c8e89124cd0636cf089e.nq.gz
    ├── ca2684f42f8b1862deee2d86430c9ab3395bdc50.nq.gz
    ├── cb05cc53556c7e5d86ad0b792b74a7c25e675186.nq.gz
    ├── cb0cdeb33cbdb5a6242522d75a93bf483c70dc27.nq.gz
    ├── cb174822179428bd3c7f70bdc8b6aadbdd231eb8.nq.gz
    ├── cb2556211c7441cc62371771d6f93d1d4fe78250.nq.gz
    ├── ceec6d677e1eaad6c209eb034a1b018bb3efc95a.nq.gz
    ├── cf4e56c522be2f94b4315e36b72145acb5e32eef.nq.gz
    ├── cfa8e731df41febe1cff4008479842c55d09c888.nq.gz
    ├── cfe71d1c0608bffbafcb671082eb77853322133d.nq.gz
    ├── d141aaf3a49d3501b4b78108f6e34574779bdfd0.nq.gz
    ├── d15b78c31fefc725d51c02015dc88a130042d66f.nq.gz
    ├── d2327693a98bee95d085087e3626a169fecf59fd.nq.gz
    ├── d24f38a2b4116a971f715f0daa93b5fc7adea7d2.nq.gz
    ├── d363df7a346c79613a1d9f465a3864f3c8819842.nq.gz
    ├── d4195101b62e2184b8e4ac83c4e8ed8c5626e85b.nq.gz
    ├── d47b4cc469a69789b07249cbb3b1d1c021f4f0df.nq.gz
    ├── d4c6a3a95d2db6b00cd8a013eef21530e0cd3592.nq.gz
    ├── d80369ce090ff8ea0f213ad1923e357615a67ebe.nq.gz
    ├── d82945a037e206ef3eb4edba45d2fd77c6480dd0.nq.gz
    ├── dd03ba224aefe30f7e4bc0bd6181a1f5a43c1c57.nq.gz
    ├── dd76d52b7bec30d4d7b71c64fb507dd5462d520f.nq.gz
    ├── ddee1386df9877540796ce28eb5681b51ebdaa02.nq.gz
    ├── e20613f347ab0b97a7db4dc6608d3eb31fbc3bb5.nq.gz
    ├── e241f489fd551d0ae9b44c33a1face51a5171ce8.nq.gz
    ├── e2b158f8d8bc153ca5f9e98c391302a34324d30d.nq.gz
    ├── e32aa1acdf0a2d8c7f8c4ad0c4e114194eb8a83b.nq.gz
    ├── e3b71e32b43c70111bb6359d6fcb39233c5c05de.nq.gz
    ├── e4eb46f3e9adb55a25eda0c3f6014025a8ef43c8.nq.gz
    ├── e53731b7708fc562ab255e7b1d8fb5c90ead1d48.nq.gz
    ├── e5b7d34b6891bd69659b2a0f2ad743bc11df2f19.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e6e4e1e8fdb919febbe64638089fb3ca43148276.nq.gz
    ├── e801e038578a2bbcb6e0ae2804c348ef5f8d0b4a.nq.gz
    ├── ea9c71d671d6d969642620ccc439a39688c6434b.nq.gz
    └── ecefb86f5c9a3643726ec539109f82dea2c690b6.nq.gz

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

[google/pasta](https://github.com/google/pasta)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
