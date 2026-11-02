# Repolex Knowledge Graph of anthropics/redis-py

RDF knowledge graph data for [anthropics/redis-py](https://github.com/anthropics/redis-py), parsed by [repolex](https://repolex.ai).

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
rlex download anthropics/redis-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 04589d47d6f575e1ebcd2a0fe8ff85e02d42859b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 04589d47d6f575e1ebcd2a0fe8ff85e02d42859b
│           └── chunk-001.nq.gz
└── blob
    ├── 01077e6b8871eee1bf0d2575eca966eebe354687.nq.gz
    ├── 0288496e6f1c6f7675db2acbd7fa5206d381aced.nq.gz
    ├── 02aa244ede48c5c8a6d7b3586bf87de2f72e8118.nq.gz
    ├── 031e8364d70f1f6a04381303c4e93b4588fc9e7d.nq.gz
    ├── 03fd973c4cee9ef05b6fa78efee40dc4837c4024.nq.gz
    ├── 048d06c53c7800937f775db8a32495b1fce49081.nq.gz
    ├── 05c2c8208156f0d29d8f155e8a6f112f4fb50747.nq.gz
    ├── 05cad1bfaf0461bb8d76c07a6d2e3e71eb7d3833.nq.gz
    ├── 07914fff12de3b89a932b559581692251d89b5bd.nq.gz
    ├── 08e980e866cd4f377898d0517ddbbef46d276bfa.nq.gz
    ├── 0951d95641f9f19f3ef53a66dc2a2b09e0430c5d.nq.gz
    ├── 0a491276ffe5b478d469106cad30f73b20810256.nq.gz
    ├── 0a885055572a9b9260b496fd632c3251889032ea.nq.gz
    ├── 0a920cc55bb2f8424092ab0046f54be0343c9035.nq.gz
    ├── 0d128bbedb14fd2e6f4c7622444563b580f16832.nq.gz
    ├── 0ec77a4fff8b8555df0294288f655c2c3eb119cd.nq.gz
    ├── 0ed3e1ff34943718a68c66c73ccb820c762fd673.nq.gz
    ├── 0fcb256cfb3cdd0867e8fca8776f766fed45c6f5.nq.gz
    ├── 10db91dd28e94d6eb9e7dcab60ed4102654b9287.nq.gz
    ├── 111da8eb08bef4b26d15e94560c191b7dabb74f2.nq.gz
    ├── 12ed6562777e9db85105d32a026a55a4d751ee80.nq.gz
    ├── 13a6158b4009ea52ad4a29423bfd0bec3e8d04e4.nq.gz
    ├── 13edefa081fac0a1f0daf11c7640e9a21ebd5e07.nq.gz
    ├── 13f20352652b96ddb5044e340ba410b911986964.nq.gz
    ├── 16d7fb6957591f593ed6479abafa50a49cec1df3.nq.gz
    ├── 17bfa9d47c88bd7d9e14b5407d13a08b0946ed02.nq.gz
    ├── 17dd52b5df5149de5e6888b438f99a57833bf6d6.nq.gz
    ├── 182a5b2bd3afa3fd1d4c0471833ee0a1249fbd4e.nq.gz
    ├── 191600d7c683d9503b000faf84f0527412c50ee7.nq.gz
    ├── 19e11dc79231c2421ce037a8e27c76b815510d71.nq.gz
    ├── 1a876c165575f4f78e4f46a9915d9cf6b138a568.nq.gz
    ├── 1af2323fe99c8e58d17ea917320fa2c14b70ad12.nq.gz
    ├── 1f0b24d76815627b4b3e3acdb5312e4ffa3e75ef.nq.gz
    ├── 1f239546c15daf50f9bda279be6d349a70b02974.nq.gz
    ├── 1f613aff5ff567007c4e8310520517268622eaad.nq.gz
    ├── 213280140c1e6f0dc7ae159c091aef33a52f136f.nq.gz
    ├── 23551be27f8bc05e2a89812b89f6533bf1c7850a.nq.gz
    ├── 24ad6074801e43a7dce1b8c54b33fb4e3e9ca3f1.nq.gz
    ├── 24b52c54db57693b4018389501433b85cc53007f.nq.gz
    ├── 281d7f0a0b1148beb3a1811f407054b48ab7ad2d.nq.gz
    ├── 28fcd3aa23d90dac220924f9d4bca4dc35bee674.nq.gz
    ├── 28fe758619ad18110c56db8582dbb6e4e5ed0d4e.nq.gz
    ├── 29bcaa9d77e9a04ab7cb8554686081d89970afe9.nq.gz
    ├── 29c5c18767a9ee802d333638991c43de9e58f735.nq.gz
    ├── 29cd529e4defee72a1eb00105b05d8d703025b34.nq.gz
    ├── 2a945ac28728cc2a01ec4d0e72773f05ddc134ba.nq.gz
    ├── 2c0557cbbe69abda8a4d2200a2d5aeebbb11a19b.nq.gz
    ├── 31f781f773b83a5d817bbf33125d1c8686f5bdde.nq.gz
    ├── 326495b775bb3aac5a8e3667ddabcc9724938ae5.nq.gz
    ├── 3400bcd60f428a0779a22140eff2c789fb3c62d9.nq.gz
    ├── 340d146ea3f78762d37abdae77b4d462be0a1788.nq.gz
    ├── 3545ab44c24f506389cc88a7ea42b6d750ebc840.nq.gz
    ├── 367700547fd0eda04af8352225e4f00d57b071cf.nq.gz
    ├── 36ce31d708cf9c2ad5291457837ed73a84802236.nq.gz
    ├── 37ffa97812e404a72e28289a71357c04a6dbbbad.nq.gz
    ├── 383b9de794f6e1f03a6de441c6cac9971d6fa56f.nq.gz
    ├── 38764d30cd4696a90c6a70f2f6311cf5293c9890.nq.gz
    ├── 398171a04c91b8e26331c9b27dcf0465a3ee2d85.nq.gz
    ├── 399c8a0ddadad3633629e757cfd965667f88f711.nq.gz
    ├── 3d120e4ca7fd452089378cc768a2c1414565a91e.nq.gz
    ├── 3d6d81465e3477f4020e4d892c020f12b75913c9.nq.gz
    ├── 3f35fdd59e7d1d642a0554e1799284b63b8ad0cb.nq.gz
    ├── 3ff1320972f2a27c40378d7420b975fa0c6186ce.nq.gz
    ├── 4188b93d706bb591dc437714a00218cce7c7ef87.nq.gz
    ├── 42866f5ec124b9b34cd37f9d6a73d6c31e2754e0.nq.gz
    ├── 44717bf128f5c1250ae7d6fd9b7af367e829cbe0.nq.gz
    ├── 449ec0c50f0a1629cc954e48e5c42a078158fc83.nq.gz
    ├── 4607da071cce4f078094a0457c4e1924b760376c.nq.gz
    ├── 4670c55b0f33f961ae94ca4644680ab041cc5e5c.nq.gz
    ├── 47534ec248d6be6d02b7961bc42eaf53c3ca8f4d.nq.gz
    ├── 47fdbdf41de1d27a1216d018c36f3481fe610dc4.nq.gz
    ├── 499c8d917eec527af45740ccdb0351b0ea7ab9c4.nq.gz
    ├── 4a9d95bc1fd2e14aaab5f212c75cd6896c70dc2c.nq.gz
    ├── 4ae336acf86fda5bea860c677b8190b597eee0f1.nq.gz
    ├── 4cb39f8fc884e7bfd964dacfb8ed6499120aa041.nq.gz
    ├── 4d0fc338d687954d6a827b7296d754f44459f2e8.nq.gz
    ├── 4dc633c1a65e96bd5d4b69befce21bdfcb37b60c.nq.gz
    ├── 4ec03ac98fc484f638b2eb00b04337d15c9b26cb.nq.gz
    ├── 4ef957acfb2c0e7ecaa26e991e706b91e1186025.nq.gz
    ├── 4fa8f14b84dca6dd9288ebb2da29d524cbf7de50.nq.gz
    ├── 4fb71964222e7b247ac761640c19f634daf9e7c9.nq.gz
    ├── 4fbc02c5fe6e8ff56d9b49f21e0f98f46f481e6b.nq.gz
    ├── 51360639eedf5f46a1759030505de507391945c2.nq.gz
    ├── 529c3ccdee577abd4c07431dbb1581fa128d6890.nq.gz
    ├── 52decf08e76c21bbd2913b2868ebeb377bed3121.nq.gz
    ├── 5468addf626c2690d025b5c7229253e2c864e820.nq.gz
    ├── 549eeb49a2979ed0df51dc91287430c97539671a.nq.gz
    ├── 58085c9637ec6af444ace393677caa82e484d223.nq.gz
    ├── 58bbd01f28ce61beb832c6e7afa6071852879d96.nq.gz
    ├── 5b15c09268d4d9c28cf1038a6661767463f293b4.nq.gz
    ├── 5cc6c0017c1e632f188aa78d9faae29f2d4790fe.nq.gz
    ├── 5e34ec8866a3ebce38551c37948ea4dbe79423c8.nq.gz
    ├── 5f77dcfde49dc2a06a23f76da64ee01930882c68.nq.gz
    ├── 60f4ddd3d327bf1bf18e4a9c7ee6a52cee000a8d.nq.gz
    ├── 61124ac79b36326fd5087a8babe771fa76f83383.nq.gz
    ├── 612c0d5aca36aea4d7baa5f876dc16144c23f3fa.nq.gz
    ├── 65bbd52d6033be7972e12e341e279f077fcdf0ea.nq.gz
    ├── 6695abfe4bc6ef198bc7db272ff0a8d69662245d.nq.gz
    ├── 66cd6b320daa58984956b19993b41a0b9d7f7b8c.nq.gz
    ├── 677e165fc6d924e5e40e8d57194cfef051b2e4ca.nq.gz
    ├── 691e13350a1d014619a378834b502f41d4997408.nq.gz
    ├── 6ad2b6acb2e8dad297fb71c56ace691166f8772f.nq.gz
    ├── 6b544553cb43be662301d3445352663c9e42644f.nq.gz
    ├── 6c4b3c33d730aa95f8a7ab20c8bed4c334e85025.nq.gz
    ├── 6cc32e3caeb677171a78eccddaf123d4c37c3ffe.nq.gz
    ├── 6e253b15972e97f28ab439cbf6837b91eea96f07.nq.gz
    ├── 6e59454ed32762e2a5b68d64d02ad85a7df60e49.nq.gz
    ├── 6fdf0ad88263c9e83c8a29cdcb7be1276d1ccd5a.nq.gz
    ├── 7010baff5fda70cb2d14935500aaa84ef68bdfaf.nq.gz
    ├── 722906b0489d5ebe76daeb015b0a35eb54c3e87e.nq.gz
    ├── 7282ee3d24fc7cc11b00d14bfbc974ed454d39d7.nq.gz
    ├── 7323c143923a659b12bdeb61de499745b5e6166c.nq.gz
    ├── 73ee3cf8114a22591eba34da14923e093fc7c9ba.nq.gz
    ├── 7404f3d6f8fa70c0634a80a11c0041748834ea35.nq.gz
    ├── 743dab18fee6b92027272fe562f42cf1b665742d.nq.gz
    ├── 747b3b6d76d58467b31b659efc6ac5c67eeb04f3.nq.gz
    ├── 74a9f28b2d040cc22918cf1c0600514628b7c016.nq.gz
    ├── 75de8dbb9f61d15dabed57e73a9f395c3afb2c37.nq.gz
    ├── 75f711e5d4f1f00667fafb505af5b8232ac7adf8.nq.gz
    ├── 76fa72ad4c6d063706f7cf91463f49a670359061.nq.gz
    ├── 7c2beb4d6444a954184d6847bebd586339683f3d.nq.gz
    ├── 7c5e3b0e7dd58b4eb87f3afa00e0a27b794b6c46.nq.gz
    ├── 7d4cc41b8910fec4c14bf1e52ac7a246d5654439.nq.gz
    ├── 7e4f59eb7957a238a8328c9cb82428479370eb5a.nq.gz
    ├── 7eaccb1acb7199ca4040af5ece5607cf9469d8ac.nq.gz
    ├── 8147243bba23d95e285d607c2f2e411a47dede99.nq.gz
    ├── 828b3f2a430679026e0035728b0c80c7d07ee153.nq.gz
    ├── 8509ccd678eea721e68a9c75139554e5d3aec8cf.nq.gz
    ├── 852fd4aaa6e6130ea65e4f4504fbffbb096d01d1.nq.gz
    ├── 861e3ef003886edf82702b1a8b04c3e79505fd64.nq.gz
    ├── 865bd522a2004933ae5e59050015efb3a187d86f.nq.gz
    ├── 8758efa7719f401ee9d2da41ce7a0425459e08fd.nq.gz
    ├── 899dc69482487b4db7bf2b9da00da9c89d851558.nq.gz
    ├── 89bd9c0ac44ac156c27c26529c1baa983f0cb441.nq.gz
    ├── 8a9fe457fb692259fb126eaa663802a42d461abe.nq.gz
    ├── 8af7777f19f9b40fbee15ede0479bd226e3e504d.nq.gz
    ├── 8b4884727a42a91795771f543f424d0f34a001d4.nq.gz
    ├── 8b4d4b6875caa9d2ba6566a14e9d1af8c522dad7.nq.gz
    ├── 8b60f2328343407c0d16080015c71de185bed819.nq.gz
    ├── 922c83d2fed907b5d28b2ffd785127782af9b4b3.nq.gz
    ├── 93455f3290f53adad9378b9243af775c054825c6.nq.gz
    ├── 942574e0f331e76af6e587c8e9052954bcc9bace.nq.gz
    ├── 96009cd0633d720da0400a7589c8a90cd8f45f54.nq.gz
    ├── 9664146ce515dbf822cd4b3b5ad90686657bab5d.nq.gz
    ├── 96abbe6da86e93d57dd2ff51da1f9fee459e4de9.nq.gz
    ├── 97633e38e781294beb55feaf5e526c1d038e8232.nq.gz
    ├── 9767e3f2658369553079bbd0d1198c3af456680d.nq.gz
    ├── 9971edd256b81f14d987939acd50350e98900193.nq.gz
    ├── 9a318796bfbe8fd5eb4a027eaaa5ea4d356dca72.nq.gz
    ├── 9b07c80201a1fd185e8628875b833e166ee7e7dc.nq.gz
    ├── 9be06b93cab1d2baa7c70b5345d5f846381f821d.nq.gz
    ├── 9ce1efc0ec31c6a1b740e25100f7072870f0e02d.nq.gz
    ├── 9ead455af3bfdaedaaaa18dacb4339a7f8207350.nq.gz
    ├── 9ef672330530a99ba564c20762a419529fe7675c.nq.gz
    ├── a00ff11150342f93f2dd9fc6f02263fd8a29d3fc.nq.gz
    ├── a011697f4ae39c98485c836167c6e211b571ab0c.nq.gz
    ├── a0429152ec85482c89b3ee0de45e78104bf61429.nq.gz
    ├── a17f19417cb2725129bfde22454d76c16505e6fa.nq.gz
    ├── a27ba92bb8b5b38a137bdab6b76a5669b4b89733.nq.gz
    ├── a2bb23b76d9efb454ed8aed0ffa649cff3d21431.nq.gz
    ├── a566262e09bee755f24756d26fca5015872727dc.nq.gz
    ├── a668e85b42c99ce5f8e6bdbaa29bdd7ddfaec871.nq.gz
    ├── a769c968638eebf7a4e61407596b0f5cf8f80a19.nq.gz
    ├── a8312a2ad289f2fc6f270d6211366b02c9bb9121.nq.gz
    ├── a841cb1df6e1bb31e42501c70786f6fa7b4d451b.nq.gz
    ├── a8c327f08fb80d4b0ce6102c623b2f531cbe0d1e.nq.gz
    ├── a8de68d23cc9439517539a49125702ed96f39311.nq.gz
    ├── a94d9764a67c5d35bcb03bce8e54d5cf4db0b4db.nq.gz
    ├── a9d5b0bf645ca5535c5ee6aee4446a35a357cd68.nq.gz
    ├── aa1dc49af071f1dcf6de160f87ad4dae12abcfe5.nq.gz
    ├── aa958a92361bb9bdac87f9e6beba8dc78c631469.nq.gz
    ├── ab3e4cd77e0d98e02b380603ff9abddc6b331a66.nq.gz
    ├── ac3e340d9603c4c6139f6a62c64a17ca3fb29f67.nq.gz
    ├── ac71d74297d84bfcbe28f3ad14aed8386a4ec6a1.nq.gz
    ├── acf198ec9403490abf8c92b7e0b707dcbff8466d.nq.gz
    ├── ad0d427ef698c4588559009993c61a19a3f611e9.nq.gz
    ├── ad7330598d8fed43d01eb6a239711b69b9dbb722.nq.gz
    ├── af45b445118c7184d810cba5f499e48a7a843d9a.nq.gz
    ├── af6d825129869bc6665e2e0a1e83ec9765a338da.nq.gz
    ├── afb5833d18f83c0503e625afdfe13c8f4c322c01.nq.gz
    ├── b0cb8642373bb95d0f0e20385ab66cd770da34ab.nq.gz
    ├── b21f7d0ac829e1a1a5e1cefcf71644c3cfeea8aa.nq.gz
    ├── b44dd1fcf157962e40074ab5809bb744bf6002a7.nq.gz
    ├── b4824be4698fd81b8654fce696714be463f055ee.nq.gz
    ├── b5109252ae0c99f7552e1fdc6a9742714264637a.nq.gz
    ├── b547a7659e8d03c7de6e4a212d05ea0b040fd75c.nq.gz
    ├── b5deff7ff34d22feef2a5d216cae9b4d6a001792.nq.gz
    ├── b784aa5f3bb2c27e142bb3a740f2358c959d9f8a.nq.gz
    ├── b7c58e99f5591496f6b2f3c4bf7edbf32bebf0af.nq.gz
    ├── b8e100c04a6b687c2c23166134504137cd3d33ca.nq.gz
    ├── b93847112b4cf29ab03272031878d7f2a4e5d072.nq.gz
    ├── bad447a086e0aa88ff2f6f7edb17cd33a393e5b3.nq.gz
    ├── bbf1ec9eb56f806cdea1e7edc9b211360ad79567.nq.gz
    ├── bcf908aaf859ad2e6fecdd9ec3421c4364c58b78.nq.gz
    ├── bd7b9bc01d32595a51347062c27a7e0818e0880b.nq.gz
    ├── bfb0ab2db0c50dcf7024a2b0bcbffd8941dbdcfb.nq.gz
    ├── bfb6855a0f8c6535e2a2fd4a3d286b8fd03a5fbd.nq.gz
    └── c1f8355121648366f3c566a17188b835ffd6d9b4.nq.gz

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

[anthropics/redis-py](https://github.com/anthropics/redis-py)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
