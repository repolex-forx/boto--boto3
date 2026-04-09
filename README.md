# Repolex Knowledge Graph of boto/boto3

RDF knowledge graph data for [boto/boto3](https://github.com/boto/boto3), parsed by [repolex](https://repolex.ai).

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
lexq download boto/boto3
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a4315bc80b83e8cf59e8582eef0e75f79fc01e4a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a4315bc80b83e8cf59e8582eef0e75f79fc01e4a.nq.gz
│   └── repolex
│       └── a4315bc80b83e8cf59e8582eef0e75f79fc01e4a
│           └── chunk-001.nq.gz
└── blob
    ├── 005b474b616c31ef929b35861b28dfef551aeee4.nq.gz
    ├── 007b5cad338c21d796aad13a79904bc0d3ab4d8d.nq.gz
    ├── 007c5dbe7572938ac76255e2a173183d519b9093.nq.gz
    ├── 007d47dd3a5cd774dbc4e1e4569112b5d822ff7a.nq.gz
    ├── 0080fa9d01c3239749e5ffa305117cd38138355d.nq.gz
    ├── 0082f7556db177aa2012ebcb018ddeb177b85a7a.nq.gz
    ├── 008859f6359cfdda3416ab0b4d6fbf7b49a0941e.nq.gz
    ├── 00a45d160c8798bfdc864a4c541c922edf2b1ed8.nq.gz
    ├── 00b4505887378a3f28d1646a8f84da03e86bd1f6.nq.gz
    ├── 00b82463db3ccfdb4e0348208c832168ca4cf3b4.nq.gz
    ├── 00c794a492e95d04181392fa342195ca10f54cec.nq.gz
    ├── 00ca07159f66311ac85b21ddd42ba6af08317696.nq.gz
    ├── 00da75bd53ec7da66213f7c500038a65bb4b95f1.nq.gz
    ├── 011dde6fedd52209e59bf5ba5c03fd90577aae90.nq.gz
    ├── 0144186b564f6d85954baa5439e28f2f123436f6.nq.gz
    ├── 01a4f0a410924e07f5f61a56c844c94548199959.nq.gz
    ├── 01dce9ff3374de799df41af667b19152aae123eb.nq.gz
    ├── 0215905ade42a9d8cf8809bf0f19b7b6c1bf2a2c.nq.gz
    ├── 022bb1292d73c9de67a7edcfc094e8c51742516a.nq.gz
    ├── 022e34be541bd3f8eb07cf30a6d9d8164078784c.nq.gz
    ├── 02460529d66952f5578948f5c3bc1177a4444aef.nq.gz
    ├── 027070cf13d7bbeb6dc2816d78224a26874800b3.nq.gz
    ├── 02bd53d9e5e410896dad532d3d2c43abfea74906.nq.gz
    ├── 02fd7eed19e0fd3e1d4c919ed1dd2afbbc469282.nq.gz
    ├── 0388baefc71b5b8da544823a9a19ba553cc16e07.nq.gz
    ├── 0393d5ddf4f3b8c8a043c6e2d03596287c2848a8.nq.gz
    ├── 03a1b058629d8593b650112231fbfaef19519c45.nq.gz
    ├── 03acfe17a1cb93300c37f6dca8bbf27bab4c4b7a.nq.gz
    ├── 03b9782e7b54f6d8dc140baaf7aea84c51a197a6.nq.gz
    ├── 03d76fee781cd80a9401840bee69f68ad348f67e.nq.gz
    ├── 03dd20ee1caf8f1513159be23b6140cec64370d7.nq.gz
    ├── 03e43626ca7567c69082793c61ec370eb32eaf90.nq.gz
    ├── 03f62408ae91343cddf8c3e5a094d9ede80fb40e.nq.gz
    ├── 04112b5245473b106791ed0adf4156536ae2d465.nq.gz
    ├── 0415868847905220795291bf2cf72d64af9d3190.nq.gz
    ├── 0433077154338f792c0bae1d8cf74f74ee3e968e.nq.gz
    ├── 0442ad82baf2787f2c9b0108ea2512d345cb5dae.nq.gz
    ├── 04802bdeb967ae44c4c2feaddaba1ad058adf941.nq.gz
    ├── 04d99b64ea3df4c9bcbc05f7a814d87d86b9e02d.nq.gz
    ├── 04dff794397737439b4d28a299e6c8875ab360bf.nq.gz
    ├── 04e6bd81ba362ceb235bfc58bb6832d5239d86f9.nq.gz
    ├── 054cfceecf4717c14a0399bbf1f5d6c06fddc77b.nq.gz
    ├── 056b096b485698daa08ac2fd0bb69c28d91af13c.nq.gz
    ├── 0581a90a8038b1dbddaaf4659bba0be6f85d2168.nq.gz
    ├── 05bda387304568e029597c90bc9f3c77aea13ccb.nq.gz
    ├── 05e69997b6a2d9ef863407a6532c41e2919d37ac.nq.gz
    ├── 0613c52291dbc74c69b281382b38eb465d1bea0e.nq.gz
    ├── 0619cdaca94a23f10151372412ec1a794946c9f5.nq.gz
    ├── 061a6267f86cc0daa0239bab924782587530365b.nq.gz
    ├── 062ce55bf6cf40e605597ddc8e96187e2bd8e7c1.nq.gz
    ├── 06341c3606cd8a4a01bbec5079f79e424fe15d8a.nq.gz
    ├── 0654e8f179029484e5a63ca85f531946543115c5.nq.gz
    ├── 0683fd8fa5194acde0f12f373dfb7c276c477144.nq.gz
    ├── 0687bf3b0135be43319cbfe053e754462be4e666.nq.gz
    ├── 06a08e51c9470f76825b430f5f5a160831a44c91.nq.gz
    ├── 06b17c6971a3c3c4c9db85d0e7329288838f3c51.nq.gz
    ├── 06edbb0086e7127a8ca737d9602a3039754d6335.nq.gz
    ├── 0700a44128f89c5df34f42d5fa570aab3c261bfd.nq.gz
    ├── 0751cfc6a689844252cc57c25296f7a867f91f24.nq.gz
    ├── 077414dc1971cd35759c0499f7e8316ea036929d.nq.gz
    ├── 0788a0e7443a0b6517c2ee997bbba7cfdb63b0d2.nq.gz
    ├── 0790d728cde8775f3a9642e1fc509ea1db4c4cb5.nq.gz
    ├── 079250a3b514d1536840f9dbd7bff01d991bffb3.nq.gz
    ├── 07991f8408c29aaa002bdf2a5baf4445ec24f459.nq.gz
    ├── 07aa5210b6b150de05aed53ca8d8376946e6a321.nq.gz
    ├── 07b7a3ba0d0d4c31e54c6aa3abd18fd187fde565.nq.gz
    ├── 07d37e67ddd56f1a4b825afe5db87c78f43263b7.nq.gz
    ├── 080a10f061a2a279838a5c687c10673246346f65.nq.gz
    ├── 0830af5052fbffe5fa9156042038762b619b0fa4.nq.gz
    ├── 084529d63ff43fc239d2450816a8697875523a54.nq.gz
    ├── 08bcce85e1a673d820f08e7ce2eb48737f068eb9.nq.gz
    ├── 08c7d60f671b06ad295c5996cedaa37b049f4d7e.nq.gz
    ├── 08c90098bbf7b16ead95bc4bcdeef8ca9f11d9be.nq.gz
    ├── 08e55be513cd14a4e46335dc060c651ca24a9d31.nq.gz
    ├── 08e9cd30d677ab7af34f532069e5684bc7be4d89.nq.gz
    ├── 08f8e35ff310ff18904800ff8290f4073e85fbe5.nq.gz
    ├── 090da0eb64f49a6640ef01afb3ed94a2a9f2c522.nq.gz
    ├── 09174bde3b94a6f4ca8dc625ead84b3154f592dc.nq.gz
    ├── 0969bbf64dea53d8de4dffd52584985960f94707.nq.gz
    ├── 096ba002668a1e4eb57ca5e7a2ca7e2a590293e5.nq.gz
    ├── 096f893a16b5bbbff3ec849ffaa8e45d74f44564.nq.gz
    ├── 0971348611d8b66e6a68fc0cc82f246c056b0a1b.nq.gz
    ├── 0976f57cafc7904bd0add779b5ce845bdb2655aa.nq.gz
    ├── 09895ec423f7e2aa4f9e81a37099aac52d0dbb96.nq.gz
    ├── 09b3a48be094aed9db4d9d62aa44da0c2f0f0ddc.nq.gz
    ├── 09d3db405d28d2f7a6aa2640593b9c70f5db9797.nq.gz
    ├── 09f7ecd44a6d9de613b019f7c385b15ab4fdc83a.nq.gz
    ├── 0a445bc0bab16354a566121966cecab2387301f9.nq.gz
    ├── 0a6c2a07f34f3f70424ab2e178a72fca479b5a7f.nq.gz
    ├── 0a7ee0015353a41e0c1fa7be520f6c5b3a5f6442.nq.gz
    ├── 0aa6d67ab5eb5bc6c22ffdeaebe5f21e929537fc.nq.gz
    ├── 0ae0370c6dba3e6027623bc7b8cac5e89daaffd5.nq.gz
    ├── 0aeca3a2e4cf26c3d794268fb062e907c0984af4.nq.gz
    ├── 0af23af5425a26811375d59b6184a5dcb676411f.nq.gz
    ├── 0b27a999ab8300d83023d3e48d2c0e051a591ca2.nq.gz
    ├── 0b58a8a59b1850f352c357a0cb2bc82b48af930c.nq.gz
    ├── 0bc15f9b0d38ecf5df1b45a8eef4c337792df327.nq.gz
    ├── 0bc2192fefa8ce71a240e22c5f70568d33ccfae2.nq.gz
    ├── 0bcc1ab8760532f02a40c3d4c2b91b36b721d0aa.nq.gz
    ├── 0be0897ca4632225677816bc6dd0cd46ee139338.nq.gz
    ├── 0c253050901b04c27d3c71bc0fddd354a5b82a0e.nq.gz
    ├── 0c4050b76b1c5cdaad208b6e5ebe5b1163e061b1.nq.gz
    ├── 0c57394a51b899e26040120795f2c540cf8881d9.nq.gz
    ├── 0c6857d86d134d93673d20a8cb09dfe7d93cdf08.nq.gz
    ├── 0c786880a026476e5e6fb70620dca5ad3dbd9111.nq.gz
    ├── 0c78869ef2a82cf99be049d79426b8ffd131e43d.nq.gz
    ├── 0cd5ff14c6188505f381fd5ddeae23c235673ac4.nq.gz
    ├── 0ceb84e0afd2b32d8b29a22a3885d166eb76d072.nq.gz
    ├── 0ceda7f1c7cfbebb0ae03c325d7d58ab0cd8ed91.nq.gz
    ├── 0d29851d1b74107465ffb690a900cf90c88e58f1.nq.gz
    ├── 0d40efdde6e7697f7414d4d1965aed144445ea60.nq.gz
    ├── 0d6a6153180c464ff5ea1fd695b5ec24de92c510.nq.gz
    ├── 0de43a91d028483fe044acf57dfe7e9aab074415.nq.gz
    ├── 0de9962102ea19a6f8607dd574dee4bf1bd9d95b.nq.gz
    ├── 0e0e51e180a40cd118f1e5292547b2c8d6d3a4f6.nq.gz
    ├── 0e2d55a7406479ace32a98b6fb41da61ddcefbfc.nq.gz
    ├── 0e4d7fbf35c066c8c2dc8bf8858c65f5092ab992.nq.gz
    ├── 0e57a7a1ea0ab6ae70ee2a2ad15f8b1dde33c01d.nq.gz
    ├── 0e5e87774ada7f10eee89aee90f46d0e9136c647.nq.gz
    ├── 0e74ca3e4b3674c23dd37e5ad27d66b27e27c6d3.nq.gz
    ├── 0e8931d533cd50a8dd0db6bb08f2d7598394ff32.nq.gz
    ├── 0ea36f99853c9191dfafc663ae209109c66d202e.nq.gz
    ├── 0ea3d8efcc7c3df6c8b2be8d370aee5e24eac9cd.nq.gz
    ├── 0ebcec1e3a6cc2d670fe321972f07bd5be5a8e19.nq.gz
    ├── 0ecd4c0058eea33fd010ffb4d7efb4ee4bc5bc81.nq.gz
    ├── 0ede8afb6dccb6f2c005fc55e44ad75a302359d8.nq.gz
    ├── 0f168867213c8f266ebcc8e340951fc90eccc836.nq.gz
    ├── 0f2d2ddb629e6ad69f6f4432721f605b4b93f2ea.nq.gz
    ├── 0f397d55f9f929f4af5fcc0dd7e4f0bb3287c395.nq.gz
    ├── 0f6029c027858b47c46f960a3f889a1822e5c63c.nq.gz
    ├── 0f66e09ba26186cc7e9e50f50f9de87e199623a2.nq.gz
    ├── 0f6afaaab8098fb7978c02d9a8d93ef5eb1da86e.nq.gz
    ├── 0f6d8b7b07e516535abb2e5fe3040058504762e5.nq.gz
    ├── 0f6e0751cfa4b27f4a0028d1316eee8cf227bd1a.nq.gz
    ├── 0fb191f368a569d25146783f4360a055a67e003d.nq.gz
    ├── 104f2825e3ed47f724a1d2b1b65a10cf49efc77a.nq.gz
    ├── 10592c9172518e708060c14fd2df4cc0ead6fbc2.nq.gz
    ├── 10ac30864c413ca15e62c52bcfcb31d2a4fa3441.nq.gz
    ├── 1106e35b9857bbb928bbfb5d208f7ac8df49d51a.nq.gz
    ├── 1110aaa661c58feb6077265a37d463ff620d8239.nq.gz
    ├── 112498d97b5708808609c215d901ad78d03560d8.nq.gz
    ├── 11315a2fa8e27b6c558bca387ec748c6d7522547.nq.gz
    ├── 114599e45ba7a969f0548271114ec66f55f360dd.nq.gz
    ├── 11547fab54baef2bc897575569ab7976356d39ba.nq.gz
    ├── 11a42fa3cf11e1c15cc82cdc535df2b9917e4a0b.nq.gz
    ├── 1251286abcea29093bfffd3bdf1074695a13ffed.nq.gz
    ├── 126260d444a0294875d5fe1b51c789ab7e5b70e5.nq.gz
    ├── 126cc1733359a9b65ed749dbcbe8fd3690a19660.nq.gz
    ├── 128b8bcb6a6a9296ab02e7e7cfefb2dcd7ba200b.nq.gz
    ├── 129eaaba986a96073fa33ae2cb0d1009dfd3609e.nq.gz
    ├── 12b3ee148c17a719c9729bf23d896335b52f72b3.nq.gz
    ├── 12bb7ef085a67d82d8d1e348e461e938b1946d1f.nq.gz
    ├── 131929c271b608ed1217a80c82c758e4a8bf189d.nq.gz
    ├── 138766091d57443c4328c0dda17ba00ffc7551ec.nq.gz
    ├── 13912931f88913e46012a26a358a930be124b4e6.nq.gz
    ├── 1396ae97b460bb74cbd46684ba11ff0f846bf33d.nq.gz
    ├── 13986cdf00a4e8d090a30ebb8381e5e39c465962.nq.gz
    ├── 13b1b1cc00727712af6a290b01602ec303a93bd9.nq.gz
    ├── 13b689708df7deee1537b91e12ba711e2db39126.nq.gz
    ├── 13d30d5f223912f941f6218bffe8018432f3b034.nq.gz
    ├── 13d8d5ecc3962848c521a539bebcd366a96987ae.nq.gz
    ├── 13e49d046d73c6de318229d5d050bfab57b89a57.nq.gz
    ├── 143ac7036c454182dd2bb2ed838ab63e801a079c.nq.gz
    ├── 14422d74c9e863cd13952046f77f8fdb4bfc73fe.nq.gz
    ├── 148a2dcaed6257b63475318b8d98e9dd28300928.nq.gz
    ├── 14e05bcc33e856ac2496b95220ac91a74a11961f.nq.gz
    ├── 14e89120043035bffa54ee4cf8b4d8b882f8d703.nq.gz
    ├── 150d87f5e5b474560f108d6fc10f26f467aa63a7.nq.gz
    ├── 15228e1263de868a3d99dacc26010bf8367bd15f.nq.gz
    ├── 152d4d645a49bdf2d9112f1dde7d184723034d19.nq.gz
    ├── 1537a121f70d0bf36b7e437c4d821f688d41953d.nq.gz
    ├── 153e79e0e5d932244eab88ecff9acc266f34a968.nq.gz
    ├── 154d9541ce04c8fb4a922631d0b45fe14c94d3b8.nq.gz
    ├── 159efe78d560dfc67f3728d37fd50d78dd95293f.nq.gz
    ├── 159ffd63b05d9b7d60cc0d85bd47a454a95a7d0b.nq.gz
    ├── 15a3b6d977cc54c07d70d8760b170d5eb0089110.nq.gz
    ├── 15c9764824ba39b0e86cc5b771b1eefc7d52737c.nq.gz
    ├── 15f40ffe096ede179c9a21713318868a92e5aac3.nq.gz
    ├── 163e28d8fb4addcd0c050210412f5d2d06343487.nq.gz
    ├── 1651ef7fc9470ba4eabb103af2a145eda5d53997.nq.gz
    ├── 16525f913f64c14691840c68e7caae0750abd37e.nq.gz
    ├── 165670a3706e07528c30f53075569ea552504e19.nq.gz
    ├── 1658ddcceb0cf8f528c92c69af80cd9db4cd708d.nq.gz
    ├── 16820c72989d617766322899a33af15fd3705034.nq.gz
    ├── 16cc421b49667d49a5c6fa9f74ae925fb206ea2c.nq.gz
    ├── 16dac90482fe7b903993e2c902294bde9d822c17.nq.gz
    ├── 16e10b674bf6a8efe4ad5cd84dda9d242bbdb18f.nq.gz
    ├── 174eb8eb9a927cce65c781d53a7519921c2bb9c1.nq.gz
    ├── 175d952da46a294580254e24cbe0b642593ddebd.nq.gz
    ├── 1760dcbd5e37ddbc18aab6a451ebac3ba547f7b2.nq.gz
    ├── 17a79eeba004f8a64920fc9103f9050377a2af10.nq.gz
    ├── 17df24a018ac4e211282fa7ce1c0d02f2afb712e.nq.gz
    ├── 17e1bc037e9932a736b3a4c1b3045e92b4ff1fe3.nq.gz
    ├── 189299d740f63c3362b7fbb03688d86a82908d7c.nq.gz
    ├── 189c7ad828113787ded9ab1f749abbf8f3048d88.nq.gz
    ├── 18cae2bd7b116f13f0b653efb67ffdd273c16d79.nq.gz
    └── 18cb7904236be07c89bd3da47f65d22e1e446066.nq.gz

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

[boto/boto3](https://github.com/boto/boto3)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
