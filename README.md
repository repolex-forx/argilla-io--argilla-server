# Repolex Knowledge Graph of argilla-io/argilla-server

RDF knowledge graph data for [argilla-io/argilla-server](https://github.com/argilla-io/argilla-server), parsed by [repolex](https://repolex.ai).

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
rlex download argilla-io/argilla-server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6130c634506bc649a64d8461992946537ae287e1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6130c634506bc649a64d8461992946537ae287e1
│           └── chunk-001.nq.gz
└── blob
    ├── 000770658932db1cb074e8079b4009e883543fd8.nq.gz
    ├── 00216e7fc291eaf97bda5dc5c4b157b74d52f525.nq.gz
    ├── 0349dd739c94d654abc5c530bfff08f5bfcb3674.nq.gz
    ├── 03d18e29e2e97a07c639633b2be4fa4ea973d32a.nq.gz
    ├── 043b9dc7a49c766c7eb326fc0ed907216f4f99b4.nq.gz
    ├── 04aa67f9218c924ffd37b3f93452325a1e5a7cba.nq.gz
    ├── 04eb3a700b81f9ea2d1bebcc9a977feedc6d09a4.nq.gz
    ├── 05598f256f0c1fb7e9a5434806ea6e39c45e4b86.nq.gz
    ├── 063287e9709cb6c427f3e8819687b8761164df26.nq.gz
    ├── 0652581aba3031e68b73e4c163a6d0f63678a582.nq.gz
    ├── 06af1bba6ecc8ef3799068bb6e46be35f21e0e40.nq.gz
    ├── 0703c6a82cbe5c891e1fcbd9b8339a35de4d3471.nq.gz
    ├── 0710902db4980c6a8ea6cb61b0bf748fc4d90a0d.nq.gz
    ├── 071aeaf7b6d20db7a99b3d11084424f64fb6dac9.nq.gz
    ├── 07b7f778f15ea151bec3b9023a583c9a9263b865.nq.gz
    ├── 07bd2b6b926be8cf02d6180bce323d6366a15cf2.nq.gz
    ├── 07d2b65ca7a715d67b075bd8778cd61780801af3.nq.gz
    ├── 081cbbe2c96ab958c2caff77a54534117eccfec7.nq.gz
    ├── 082371ee31c33433510fa1c7927c45e0c1988b19.nq.gz
    ├── 08d10a155bdb983c997c7b5b85cc9f6589a6b32a.nq.gz
    ├── 092f5b9d2de0062fe7e5c78ec51f57153a3d9d83.nq.gz
    ├── 094047e76b487469c230f9d008f9a99cfacf6db1.nq.gz
    ├── 0a3e5c4d4062a71005ffc683e5161faae36e4a49.nq.gz
    ├── 0c3b6b58c6edf8179e61ad23ab78fc01311feacb.nq.gz
    ├── 0dc53f511c661adbadbd6e1f7f5978f37f021325.nq.gz
    ├── 0e4584324a55456e3125703fe3efed49d79a0053.nq.gz
    ├── 0e750724bb6d81a9566a1bee7a020609837e4610.nq.gz
    ├── 0eed99b342bb5b965d3cc5ee169e607c29b99cac.nq.gz
    ├── 10ffa693c984a1054dadd240bee71380c788b475.nq.gz
    ├── 11e36a5abda7406f5a92805bddb392152e993114.nq.gz
    ├── 12396175e80011f087200a84d1372b4b68daf15f.nq.gz
    ├── 124e42c3708c99e6555ff68b76e130683415f200.nq.gz
    ├── 12bf7918ff80def003d04530bfcb3b2a05a7a392.nq.gz
    ├── 13b484328005fe2b0ffcdf036d60aecfd38df78b.nq.gz
    ├── 13b7bf05006fb414072cee8a42f7ab8ec4fd2d95.nq.gz
    ├── 1539dea115fba24bf006fa8409df713d8c707d93.nq.gz
    ├── 156154db4525d178af9445864e95724f96d6aa25.nq.gz
    ├── 16178af6a9803f4086ae349edcaa672cc0e97f96.nq.gz
    ├── 168dce9eb1a664530789ca5075c34f082f3ed8f3.nq.gz
    ├── 16a99f041f909483b0a2812ad04014c16831346d.nq.gz
    ├── 1763eedc373683bf710d5261879454e8df15d3f9.nq.gz
    ├── 176d8da54a20de4f62e47c2be089199259dfad31.nq.gz
    ├── 1881a97096e89d90b96d44a963bdc7ff77629bdb.nq.gz
    ├── 190fae7dca22b2c2d033fded4e4c48d1b8d82ffb.nq.gz
    ├── 1a1e5b6fa5759d7c2c925d944a3e7b1a1936ab42.nq.gz
    ├── 1a67dbcbd3ec9e98f64951781ed6c347c415eb03.nq.gz
    ├── 1a86bad7fbff25d798894a0504a51411396cc2e7.nq.gz
    ├── 1b239023176a87e92d700ae3cb50d66444e0c96a.nq.gz
    ├── 1b93d7f6e27506a5a420545d4ac4e57488279542.nq.gz
    ├── 1c115c70d8086ca94bc27ab19f264e6abbcd2e2f.nq.gz
    ├── 1c4204962a9c0d6d971284c82362f9e8ca135a31.nq.gz
    ├── 1cb795e847498222472b1f9ad293d93b80adfdeb.nq.gz
    ├── 1e3e70817b2142da15908cf79c56f01a7c990495.nq.gz
    ├── 1e6d4644baec1ae4d5418f5806827c141b43a452.nq.gz
    ├── 2030ff38e8f2191fb7e231e464cc2ef072b384ec.nq.gz
    ├── 208450a24b4cad61a1ed182d6a281bed4b60745e.nq.gz
    ├── 2099447fd907f8703e5fffae7239a5c101f277c8.nq.gz
    ├── 23682d91a5ac43f4fa9c38f2f2552613fd247d8c.nq.gz
    ├── 23c53b528e59df731f998c3ef836bd3c5a7e992a.nq.gz
    ├── 2612ffc751bce5660ed1b2aeffb163737dcbc11a.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2716507f041326bb14c50bda1e94bb164f7453ae.nq.gz
    ├── 287daf66d951cef3718a4f40945e53323a8e22b3.nq.gz
    ├── 2ac0cdb1234abd008314b4e4bc451f98cbcae01f.nq.gz
    ├── 2c921d848d0f7d7c58c8b78fbb3de9723083998f.nq.gz
    ├── 2cbdc4b744367bc3711108a12a14a55c8a0822a1.nq.gz
    ├── 2fe075c25be0a9abb2d63634e8a8f8dbce86560d.nq.gz
    ├── 30471e6cd7edf34a2f704a61c9236fc33c359770.nq.gz
    ├── 3265d5704a5b5a4a486b340fa0500d312673b6e3.nq.gz
    ├── 339eb2439b74193b36d75b0d6309c3f472018719.nq.gz
    ├── 33ed2ccb3e354cfb81c7c0342b6588f4e686051f.nq.gz
    ├── 344dfb58f04ec63886057aea5bd31251b3e2e99b.nq.gz
    ├── 3577126e973c15e83efcd83a0e4637449ac75a84.nq.gz
    ├── 358d710d343f3a718c882bb2f8f9e0508c621d50.nq.gz
    ├── 37ed2988667f644d38e6beae6932e127ede0f240.nq.gz
    ├── 38a8a6aef291a99aa1193472d0e1efbe093fda1d.nq.gz
    ├── 38e835aa4345041729eaae7fed4de4948f260edd.nq.gz
    ├── 3a5afedd00cfa781e54a00e81f04719018e47877.nq.gz
    ├── 3b7ec5492b7cefeb6216655daae1855568a8d399.nq.gz
    ├── 3c3037bde6c5b2bbffc2b4545dd8990cd381d050.nq.gz
    ├── 3c885db15860e5013afaf5305c3b897326d0b6ab.nq.gz
    ├── 3cb6044225d9819136866800d3400f3553b3c850.nq.gz
    ├── 3ce5e1356ad007a46c96382b9057a6b24a896f09.nq.gz
    ├── 3dea25e48b2de1173ef86623d49b84cc04f57062.nq.gz
    ├── 3e4d3186677511ba7734194d132da2808332942f.nq.gz
    ├── 3ec6ac00374d32ea0963de6bae04c5915cd1aae3.nq.gz
    ├── 3f3b505a22270b0ba0c04c9ed6c54688408daffc.nq.gz
    ├── 4349035bfe8e271fb4a70fe969184c6235a151bb.nq.gz
    ├── 44b2d5c496c6fba379aa2cdbb55a9e95f9eb063f.nq.gz
    ├── 44c8194f7c7a7cfa5dd895519193e447e4fbad2e.nq.gz
    ├── 4565bd76fb5530234990f51c75f992cb9e3ad3d6.nq.gz
    ├── 46ab36c2efe99709e4cacc4cfa1ad2b499aec378.nq.gz
    ├── 46c15764462905d1d55a632bcb5d4d09fa74a3b9.nq.gz
    ├── 4725d6cb9822c14df7c3d716b8c8a87404cbc246.nq.gz
    ├── 483acffe0df85311210398898f440f125c8cf18a.nq.gz
    ├── 483afa5d0026a4448995949a912bc7c2a47a5f30.nq.gz
    ├── 486f6296334bf6a8e59b26c682996918e6976bba.nq.gz
    ├── 4a2d287b559049d27ece673325e01195d8c55dd5.nq.gz
    ├── 4a697b67a078ef86108f62e5a13cb2ff9412bd64.nq.gz
    ├── 4abf8aafa3ee3cbccc53ad71c439df52891f8540.nq.gz
    ├── 4c1e53ca277090a9af0d8ffc3176dcb574308091.nq.gz
    ├── 4c517672c9cf893cc71935993268690ba1c64fd6.nq.gz
    ├── 4d4757c161157fdfb1d52f237522a964bba54673.nq.gz
    ├── 4eaadd14e82cf0eed2cd0e438342fa86fee14115.nq.gz
    ├── 4f188f6d8ac41a0bbf762b03115b58f5d9853bb7.nq.gz
    ├── 4fd4d50d531f81fe4292b43f8a8318a0e1f9cc4d.nq.gz
    ├── 509840ab9dd86bf90da5541d175bcb2f2c2dfd8a.nq.gz
    ├── 50c901d196b6e6eb196239d7b8bb3936dac62edc.nq.gz
    ├── 512eb73093808f8782ba1c69a17c34192cf1ea7e.nq.gz
    ├── 51ca7aa1444d57bec5e2e2841b7cc23b718a72e2.nq.gz
    ├── 51e3c56b4986904912585c23c59b352f4acf34fe.nq.gz
    ├── 51ec1a14a9553368fb3db16eb02c32c64209a682.nq.gz
    ├── 52032b0b836c776990e3e4285d67b2dc36efde5c.nq.gz
    ├── 522c40e5c785c194bb85dc282a230e361a4ce609.nq.gz
    ├── 529c89f7b68163fa3a7f5e6e2438a450f1890c14.nq.gz
    ├── 52cb08924f9d46fe670a83fe2850ec42babf09aa.nq.gz
    ├── 55be41799b73a23a42e6a157a1429a681e81d8f0.nq.gz
    ├── 55df2863d206fa1678abb4c92e90c45d3f85c114.nq.gz
    ├── 56d69af76ed774f26c3536296d371e7b4b4e04f3.nq.gz
    ├── 57332eeafb8f8cabe0cd6f8eddf1a1c33bebec0f.nq.gz
    ├── 5879c06e65cb7fbecf212a41767e402d4b8f24d2.nq.gz
    ├── 58e936a782362a65a9e977da2d7a5120af9d9a06.nq.gz
    ├── 5972504338204b030cddfa615d8abf4037aa9d23.nq.gz
    ├── 5a196b3f6bacb05fff4088c53f3568e04aaf4f68.nq.gz
    ├── 5a908e96d88e50005b91d8543b411e1463e3f482.nq.gz
    ├── 5ab4917c05bc5aad234e20efc8d1f634a2ed4cfc.nq.gz
    ├── 5bb02e7d02d22e5e3642cbcd737840fa473a3c26.nq.gz
    ├── 5c5c561cc7d8d4f6d97e78df0d18020f97a1d68d.nq.gz
    ├── 5db918c016d2596647c9b99c031fd75b3ae96dfb.nq.gz
    ├── 5dcd8341c158a71950151816366ce0e821f24c7f.nq.gz
    ├── 5fff65361641e80f318bb0943fa30b3af4a1a79f.nq.gz
    ├── 612c628c02f1f962e7da502407d6d11cbbd4e8e3.nq.gz
    ├── 6164ee727dc42f0f8538e6bfb7cf2793ae7d3e5a.nq.gz
    ├── 6283d49657fc091c25d4895a16ebe9cb07d51f7f.nq.gz
    ├── 62a32d9538d74022a0651757c881f986c1f8da87.nq.gz
    ├── 632b09fa840ea8d9a0126b2fc62afcd8f3d91b4c.nq.gz
    ├── 6333dd64e55b10d5500ff8bce17684bb935fad03.nq.gz
    ├── 645dd3cd18626a162b623885c6dbc222b00b46dc.nq.gz
    ├── 64b3f69cee10b377dc587ee650b580d5c616b810.nq.gz
    ├── 64c3800c8d5334b2c0fbfc9bc706565048f4b467.nq.gz
    ├── 65fc715b7e0e1c0b04a6d6fb17f1971bde2d8af5.nq.gz
    ├── 65fcc1174625c112be5315fc46d879de5f9ea0df.nq.gz
    ├── 6622585f65ddf1ceb75ddb02202f7d8c2a1a12c7.nq.gz
    ├── 669905fb34970dc56c81f853f5be9abff3b20ae9.nq.gz
    ├── 67ba2521383cf9a8bda1b1e6d848ca9283f06578.nq.gz
    ├── 67d704bf2c3fc7bc541bea084501eae9be5f5863.nq.gz
    ├── 6910885c06a6b5cae9e5be4fa3a99b61d678d8b8.nq.gz
    ├── 69dad7c43337562824f78adccd4c480d4ee93145.nq.gz
    ├── 6c37cf700db765b20fec517ad7e8a3b5c788643d.nq.gz
    ├── 6c430a3f6b441d62072ac478dd5e01d74388f4b4.nq.gz
    ├── 6da759cd95d73f572f9f52787d4c56826f5b0011.nq.gz
    ├── 6f289d5848aa5878fc3c20f6a55e9957732b0f0a.nq.gz
    ├── 6f877b97444bef20b5bd43a4b83d582d7ea8c231.nq.gz
    ├── 701b5830fa9a85490205335fd6953f4acc1e3542.nq.gz
    ├── 704cc92948ade85dc72a5b524d84af5cc512143c.nq.gz
    ├── 72c97c79dbaa240f880da19151a6328c781d879e.nq.gz
    ├── 72ff87bd635660fa97a88f0bec3ac94035f92516.nq.gz
    ├── 7396c3dae3d4f441cdd40b02d994159ef31fdcbb.nq.gz
    ├── 7429624c1655b54b120cb1e7f425aea4a81620be.nq.gz
    ├── 749393c0850e8f8462e154e679f096607d876a76.nq.gz
    ├── 74fad70aa74ffe2ca6f41ce612dd23ea2a039ba3.nq.gz
    ├── 752246e9e0190cbfba458fa81f1bd02fee34ac1a.nq.gz
    ├── 7541573b15ab193c221537d47982dfb5b3feb879.nq.gz
    ├── 7554f822211cab516d28e18090bfe572a53c396f.nq.gz
    ├── 75f26385a8eb1f068a8f4db861810995ec9940c0.nq.gz
    ├── 7610d6c7a3b2b80ebae085152ef643f57bb7fd67.nq.gz
    ├── 765dcecf46f19d2d0fd26a6bf7b7ad4995ec7228.nq.gz
    ├── 76aa754ab1c5bbfcfa4b4cd0ee7422866fa2ad13.nq.gz
    ├── 76d6f40aef951200cda38f0b3306ac84cb4219ad.nq.gz
    ├── 76e0db3718227b38328b3dcc58d08220414e9b68.nq.gz
    ├── 77002f00d893e0d8a5f907b755ae7e17e0ead95d.nq.gz
    ├── 779340a32ce24611b5e1a88226e1c01aeac44bcc.nq.gz
    ├── 7834bc990334429f53b75940fd26ed7339df6ae1.nq.gz
    ├── 79d6224c80f5d2cb543b598153d6f4663164e4a4.nq.gz
    ├── 79fcd4fcb7f660cd30ae32e48157962e5b5efe58.nq.gz
    ├── 7a1f1d271e180cc48e3a0c489458dd5a9fabac47.nq.gz
    ├── 7c77829cdfda138b273971c5801c049d03510694.nq.gz
    ├── 7cb04d3fedc7d30ac910136662cfe969169bb1cf.nq.gz
    ├── 7d682d945b14ce8dd11546b38cba37ddeeaa9fdd.nq.gz
    ├── 7d9d1ce773f91ecee7ab11a5795af824ea9b3da9.nq.gz
    ├── 7f724f74025e56012b8153afb938700e75a7c70c.nq.gz
    ├── 7f8b333f0230af3cc463bf5db623ed0b8d95eb7c.nq.gz
    ├── 807d71c3bde1e3f166f203ac0901a708258f8a11.nq.gz
    ├── 810ded14ca266b945705656e7f423040ad9cf6c5.nq.gz
    ├── 815585aae83fd74475870d970b97e1d5be04495d.nq.gz
    ├── 81b55ba1528e7580cdc120cc78e7d045a7954de8.nq.gz
    ├── 850260dfb8e463b4c8e9c5e81ef1c47a1147666d.nq.gz
    ├── 86afd80f22613de48305960031b13df97c5aa72a.nq.gz
    ├── 885c7f860cd052e95ef61abc0cb1e0806317f8e6.nq.gz
    ├── 88892c3ced15f9fde7cb637165cbd2fb67689a9d.nq.gz
    ├── 89bad9bfebcd95b07430b5b01b2efc96d174c3a7.nq.gz
    ├── 8a2606049487863e778a3f199311db22e91851fa.nq.gz
    ├── 8bb1885d53d2a14853527fe8485017e61c68ad80.nq.gz
    ├── 8cb4439febfa77200c05d22b42ccbfe8b3a52ea1.nq.gz
    ├── 8cd1538fb492327294fa122b5745f2d22b6cb3de.nq.gz
    ├── 8d07a20cf55e4d2c344596ab85d7249d95d702c5.nq.gz
    ├── 8e7d0a31abf845e24266dbd3f5a4555ec5c62e02.nq.gz
    └── 8e84debc5a1f4ed1669cd05da655115abc2d0af7.nq.gz

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

[argilla-io/argilla-server](https://github.com/argilla-io/argilla-server)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
