# Repolex Knowledge Graph of jupyterlab/hatch-jupyter-builder

RDF knowledge graph data for [jupyterlab/hatch-jupyter-builder](https://github.com/jupyterlab/hatch-jupyter-builder), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterlab/hatch-jupyter-builder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fedc855da78b965f69a0c6d02e5645adcf2a6fac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fedc855da78b965f69a0c6d02e5645adcf2a6fac
│           └── chunk-001.nq.gz
├── blob
│   ├── 00fb97e51772ed2f655db83123fa5d9471521b63.nq.gz
│   ├── 056698c4e5c35411d939fc41c13426531d4d719a.nq.gz
│   ├── 0a6e05b877d97c92cbad01be502e3c0bf8d94878.nq.gz
│   ├── 0a76836c5f6ae1e981be42773ba97c3ca8258e1b.nq.gz
│   ├── 0ace70bfc50e3d23e8550cf01d6e7a0d68057d3e.nq.gz
│   ├── 0db021da71bb1268a4e4b83f7f9291807c8df03c.nq.gz
│   ├── 0e1ff30327c8f8100bf97da16f24d1eedea93774.nq.gz
│   ├── 131995b025b16304e190950d73a2a92e0c68f9d5.nq.gz
│   ├── 1454fa42b070a653c00fa61a24bfc8c0b3309619.nq.gz
│   ├── 1a8455b3f6e8c8a0c09007b310af6f420a13c7e0.nq.gz
│   ├── 22d7e168020c9744fa33ee495607e4d230d23712.nq.gz
│   ├── 2506993c21d1b1efcd27844d880f7d08ebcc6de0.nq.gz
│   ├── 258bb0f010ea5a1338ec4f11679f645f9fa7ccf3.nq.gz
│   ├── 2812097954b9d586da09e66fce2b2eee65b8f462.nq.gz
│   ├── 2973047a8f9c5027e9b5b4e7bbc492f9906fe1e6.nq.gz
│   ├── 2d352af421a2a63c8264e83877f79497337429a6.nq.gz
│   ├── 2e8129490a1a49394c11ca3ba2d29d27d0a2f892.nq.gz
│   ├── 30bdcf71672b06f285eedb513a51d0f1c780d6e3.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 33cb5434f7119f2ec5a1f4c6b9d1348fe4bbf354.nq.gz
│   ├── 353d021f690e1aa06ae28edd258cb0488f426c97.nq.gz
│   ├── 383dca87d21b311625cb5bca864dd43630f73f27.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 39983fde99b8155f347597d83edbf5f2a2aa52d6.nq.gz
│   ├── 3e368697fb69d2b2522f544a27c1b29271d118dc.nq.gz
│   ├── 40a0d3e65a47575583b1aef408c73e99dac55d26.nq.gz
│   ├── 40fc233a822f04a9de659c94a4059bd0c2cc63de.nq.gz
│   ├── 47a7a801e14159b8567142ca6dab0d103ecb11a4.nq.gz
│   ├── 4acf3e434992e5e3f3c220c6e4f04ef22532b443.nq.gz
│   ├── 502f2d029eb6ef47942beb7c8b34eb510e5e6571.nq.gz
│   ├── 516ead35917c3ee4c9f8240acf864c8f0ed3f5ec.nq.gz
│   ├── 5295e776b63d7adfab3ddad99962cc6f81968909.nq.gz
│   ├── 536ec14679a238ce2368fc32ec3c530c0172b003.nq.gz
│   ├── 54166e27ece79e04f3b8b0db468a8cf4c03edfd9.nq.gz
│   ├── 544138be45652abc7bc3873341deacd3f4f90c61.nq.gz
│   ├── 5455d981f19dc2026352c0e7127963a9a289ee6d.nq.gz
│   ├── 5607670ba863990c19a8031c9fd904a543c77846.nq.gz
│   ├── 56444c189f47c6c437c0b8abd086b2709d6b9d62.nq.gz
│   ├── 568af68d1031b090f86fe49c69f31255ae24a2c1.nq.gz
│   ├── 57bad7f446076d7079d5fe95aa37141e5c6c9572.nq.gz
│   ├── 59dc9c855f3375976f00e383d0abc5848a2e2679.nq.gz
│   ├── 5a0d0a4bc65bae5a584c6dda150d964c62408247.nq.gz
│   ├── 5bf6ebd3cca7346dde6237a38c2c17f4a2056d05.nq.gz
│   ├── 5c99ba78a7a246729fee6a3c03707e5e4ce4fce5.nq.gz
│   ├── 5ca0c811be2fde85f46e4854227d85495947934e.nq.gz
│   ├── 5fd2c7d8365a4c1d8cba8e7cf18ef473997bed0c.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 63ed20b8dc8dc107049e70c502a1be53480e328d.nq.gz
│   ├── 68872903ecd0394a9154836bce1ab77e2bd8a6d8.nq.gz
│   ├── 6b07064805bff0593aed2af25cbfa65e6c310037.nq.gz
│   ├── 6c45c7955fbec18896264e54b3653188d6815547.nq.gz
│   ├── 6c4b369539355a7bc893f1aa7b0509fd09ecdc2a.nq.gz
│   ├── 6e76a512caeb0616240a4ea8d9124ec093926d5d.nq.gz
│   ├── 6f6c4300b58fc0521d83bae55bf0199002f75090.nq.gz
│   ├── 6fff6fea1e6322fac993f2b766d00d30e154b48a.nq.gz
│   ├── 709e5797174d7b1014563735651ace35763a28f3.nq.gz
│   ├── 7119cf818129b042eed883921ef6cac5ad91fabd.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 775c4580d3275422427adc282393f2359bb29dca.nq.gz
│   ├── 79453a3aecfcd81be6ad883b331fcf34e339269d.nq.gz
│   ├── 7d0fae840f55c816b4deef8ca15689847cd13811.nq.gz
│   ├── 7d3c4409677c105ccdf7d3772b269e534f820202.nq.gz
│   ├── 7ee7f29edb22e10593836d97ac2fd5b631d399f8.nq.gz
│   ├── 8103ecd203bcaae3ac338b32a6e6c6ce088766e6.nq.gz
│   ├── 834a420374c0d7974108ed1426af6104d5e422c1.nq.gz
│   ├── 8506366815564071b7f7be412ad16e984b039107.nq.gz
│   ├── 851647f0fcd858a8552e02c581a5ceb78f2b8348.nq.gz
│   ├── 854e42d487fb2c14f43c2e6298b2f835f2f9de77.nq.gz
│   ├── 859f59f1f5d93e6e47cafc650205390b3f15c350.nq.gz
│   ├── 86d0aea86d5f4c452f4006235f5931dddc8e9844.nq.gz
│   ├── 8739836d282a928d4a6a938a03119ebe1cee03bc.nq.gz
│   ├── 89f1031d432c95efdc953d673ff5730646e67bc6.nq.gz
│   ├── 8a7ea29e69487a93c256fee6e15adfd533a53280.nq.gz
│   ├── 8ac11706a72a63fa2f7bec58f5d5c5c9a1bb0128.nq.gz
│   ├── 8e6b4cbeb04036e91810be960df221087f2cc6f1.nq.gz
│   ├── 8f9f1de7eaaa5498622a6948c15d0e612798ecf8.nq.gz
│   ├── 920687d2739efb21f7989945e06b08a49bc0baae.nq.gz
│   ├── 9319c3dc56b970c0dfae1ac43551fb5ca9123542.nq.gz
│   ├── 96b0fb1a6f33da9168ab6f46e87b3883082dbfe5.nq.gz
│   ├── 9ac1801e51b0e32379c2cc1df521102d5143511f.nq.gz
│   ├── 9f4bd85e5d24bb08fda6140105f92e5b0cecbfb5.nq.gz
│   ├── 9fff5f8b35dab9060b5c531fac1975627cd52c8c.nq.gz
│   ├── a3968fe1c1e2a2f7e037a2ea63a0f5ebfdbbc3dc.nq.gz
│   ├── a699a7f99b270fc7a8113aabd80aebc03e940d70.nq.gz
│   ├── a74a312056b48636746e2c18220237ae87a47300.nq.gz
│   ├── ac7cb1ba4c43de29f50129b9031c932534375538.nq.gz
│   ├── ad0edd44f2396d7e34696000ad052789ef187536.nq.gz
│   ├── aecd4fcab012f9901025e6a479c201b1fc6d72b0.nq.gz
│   ├── b080cfd0dad7a1de585cc7248446f156e8e33f49.nq.gz
│   ├── b48d48f089976bda46cc86d688399eca93cb8ba4.nq.gz
│   ├── b869a2600da56c314596b123cbda0c7b8329f39c.nq.gz
│   ├── b9a17cb535542118172768f54d5a10ed0301bc5f.nq.gz
│   ├── bb5b51e0a9382a8cfbee0074137a02759358fcb8.nq.gz
│   ├── bbc789a7f2418e428e287485c14a4ee3fbc59288.nq.gz
│   ├── c144f10f7a363be2a44f9851144e2af5d347f00e.nq.gz
│   ├── c1f04331261c3ad31897ecb1a270bf4fb41caee2.nq.gz
│   ├── c210c3954ccb9f96a413069a9470d31da7b8c0e3.nq.gz
│   ├── c8a10c13f535b761da2ad381af24dd51977636d0.nq.gz
│   ├── c972d9ccf24afee0885a5bfb0ace67ebfdec6cda.nq.gz
│   ├── cb3ef235fd9ed6c6538ac4c913cda33a92fa79e0.nq.gz
│   ├── cbaf06ac2384c852f9a428ce7166bacef7502bac.nq.gz
│   ├── cdb3ecae6fbf42081ce02846bbd96dea16fd81c7.nq.gz
│   ├── d0824a69c143d80f2a5ef9fb11a7cb2e9611eb61.nq.gz
│   ├── d117ff719b3eb592208d0b7a874d8ec561369c83.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d6d045763ac618780b666837a8b3cbcae0a94baa.nq.gz
│   ├── d706bbbd19d9dd943d1eb3c1bd670a38e6cd8798.nq.gz
│   ├── d714b5bcf721dadc5669aba721bec82c8ca778ae.nq.gz
│   ├── dc489a125d46966f834367510d7e7cf663ed4be8.nq.gz
│   ├── dea23559074deff71734b64bbb6fff1760d2ebe8.nq.gz
│   ├── e0436c65781a7c3c43e9432bde7b6b7a0ec1c560.nq.gz
│   ├── e11f4577704a77493ff8a54e87f7ccd4bce96aff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78d4ab9b63404dc6ed4338125b5c41967b04c1e.nq.gz
│   ├── eca58a66b0bded8e4606a09df31fceb5e1aa7f44.nq.gz
│   ├── edaa3a1b3371aa579dd2b5cdfc053fd59f1f2c16.nq.gz
│   ├── eff184915be0d0955574d305e3e05e5017aeaf1d.nq.gz
│   ├── f143f2cb24b6f2c5b59de6e4472eadbea248c403.nq.gz
│   ├── f4452587539343e2ec6ce33740bd6e3dd6ef994b.nq.gz
│   ├── f465cf80851acae094055838e3a381e7a07c1695.nq.gz
│   ├── f5360f6bde283da841533e9638e85ff6eab08559.nq.gz
│   ├── f7abb3f640f35004478d872c1d4404acf686af4f.nq.gz
│   ├── f8ec1d1968b229acc328340b8cd336c5175111ee.nq.gz
│   ├── fafe9b4d07bda58eef705b2e0326c565d8907539.nq.gz
│   ├── fc3d26a580f9c3db3bc826ae7e8883efe65f98fe.nq.gz
│   ├── fc76a2ade3e1377b2055a11d14a5c0fb15f9a4ef.nq.gz
│   └── ff0605a7b22e025028ed571e6e8f013d7b2886b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fedc855da78b965f69a0c6d02e5645adcf2a6fac.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 135 files
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

[jupyterlab/hatch-jupyter-builder](https://github.com/jupyterlab/hatch-jupyter-builder)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
