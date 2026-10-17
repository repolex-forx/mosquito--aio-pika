# Repolex Knowledge Graph of mosquito/aio-pika

RDF knowledge graph data for [mosquito/aio-pika](https://github.com/mosquito/aio-pika), parsed by [repolex](https://repolex.ai).

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
rlex download mosquito/aio-pika
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 39cc074a26375cc8d9d66648cbaf08a7eaff1dec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 39cc074a26375cc8d9d66648cbaf08a7eaff1dec
│           └── chunk-001.nq.gz
├── blob
│   ├── 01215e5ed3460bcaeff44f6d44e62c5f28f3c6c3.nq.gz
│   ├── 013d4a6a53334fae827a32824eaf51a889396514.nq.gz
│   ├── 01a54b2d3e861bda3bb4a2061d41267222afb870.nq.gz
│   ├── 0345be4c7215d8dca3f50ae2c6e9f6751c6d675d.nq.gz
│   ├── 041a3d930cd972335de603f7a2e303e52699242e.nq.gz
│   ├── 046a8769505142c89e30b57869ba627487a782ef.nq.gz
│   ├── 05e6bd5468c9104893a07011cc0b6b357fa489d9.nq.gz
│   ├── 06d31dcf2516a2bc888d244c97f36070626aec4e.nq.gz
│   ├── 079f700bad7e334e40d51760530f14d1080c8573.nq.gz
│   ├── 087b46f853545db766105d062fc5f2a7b3593ff8.nq.gz
│   ├── 0943a9166b88d590a04c64c8b9ba6881ea16a5b1.nq.gz
│   ├── 09a54228a2e5a59cd83619b4ceb20b7037cf8fca.nq.gz
│   ├── 09fb52d7ebc8ac744d5a3b7057b0cd328f7b78ae.nq.gz
│   ├── 0b0c52d966ed9b98f7a25e12e9c4c2737c51dd4a.nq.gz
│   ├── 0fd44b071e5e6cb66e46ff583d6b064f70e52ddb.nq.gz
│   ├── 1022bcfb90e60871dfa54180b1251459a26bd056.nq.gz
│   ├── 1376c9347458c438d107bf7964d45403846a89ba.nq.gz
│   ├── 14840cc4cd59ef9aadc3173151b6a802dc99e1f5.nq.gz
│   ├── 14dda35c2d22c9302ec13f2387ac5af9f6f359ea.nq.gz
│   ├── 163a431868edd7f8846d4a838665f16fac56013b.nq.gz
│   ├── 16889aad3f81db409b6caff3e17dfc04a4ee1c9a.nq.gz
│   ├── 16cdd1659a5535789bf0762e4ab6c63f7918c9cb.nq.gz
│   ├── 178a08235e149120bcaf147971dcd6491019ddb5.nq.gz
│   ├── 1d4bada2fcbd1de0bc3a1927904c28051e82a233.nq.gz
│   ├── 1d83cdd4d37c7773f5183094f53bd1cb588aef5c.nq.gz
│   ├── 265ad0c1716dbc3a517038c45b222a8e4f7e5af5.nq.gz
│   ├── 27b66ba8adf277594a49e330a31549aabc51722e.nq.gz
│   ├── 28f78ed3dea3ffd854f2eb080bafdcaa0398ed9d.nq.gz
│   ├── 2b6c993c50584363a7a22f5a1da3da26af4ecca3.nq.gz
│   ├── 2c41c63688d62cce3c2d0dab4dd7ac940a139fe4.nq.gz
│   ├── 2d6ddc8dac932a7a8bea71e8deba76509c2c5ec7.nq.gz
│   ├── 2e0d322e011541cc96466b5d5dbcf63572ddc768.nq.gz
│   ├── 2e51af2a8ab093fb1b033cde9a319797f866c765.nq.gz
│   ├── 2e7fde9735c550bc31adfcd0124388a04dcbf4f3.nq.gz
│   ├── 31d69dc7a46b079e557219725244f33778ba47d4.nq.gz
│   ├── 33f49d0a78f9d9ea2ac9eecb6cded76e67cf6a22.nq.gz
│   ├── 38c116c244ee5e32992068adf74f3e5efc1fa424.nq.gz
│   ├── 38df37c9475c586e4bfc7b2f2b3a90e7dbcf41c8.nq.gz
│   ├── 3b5288dd0e6efb9784b4832688184ccd31b619f4.nq.gz
│   ├── 3d9d0db4c6ad19b5d2daee58efc39321afc34256.nq.gz
│   ├── 3f46f8a02b6ef8f4917766d1306ba9fa28f8d918.nq.gz
│   ├── 42df53b103d81421ac3eddc53a68a9921ae1969e.nq.gz
│   ├── 43e7e9f344596b09e0c9f14696306ee4ffbc4783.nq.gz
│   ├── 46858ceb2c61bad2eee059c762fe567293e8becd.nq.gz
│   ├── 47c1d6f0563e922afb87e3c981136041384ca42a.nq.gz
│   ├── 49d201137cce4a60d0e9d31d110bc6ba5f1524f4.nq.gz
│   ├── 4a3a89207b85264a2c5463dd8076b6289c9f5cfe.nq.gz
│   ├── 4a421acf83859afc04d5cda12efc0933edc1f9c0.nq.gz
│   ├── 4af54fe125f9a20341744346ca93bb5fa3ef08b3.nq.gz
│   ├── 4c20ec8e270c50c6682bb12fb9588297beb6082b.nq.gz
│   ├── 4e9fbe54f1221933fe4100c836e869477b3a3a11.nq.gz
│   ├── 4f73c463ebbef5fb3c8ef7f5eb9e05c77a9168e9.nq.gz
│   ├── 575ccba5c271a9cf3262b0770bc3e51c18aac8c7.nq.gz
│   ├── 5bee3e25d756ff0bf8b77d86088e9d047797ee96.nq.gz
│   ├── 5dfc4b1ec588d1f97a96ac5d86c752169a8baedd.nq.gz
│   ├── 5f2e17963df8513901ccefb7652fc07e261dbd82.nq.gz
│   ├── 5f557801f0ff82164601a7cec399008bc815b136.nq.gz
│   ├── 60e8eaf25e4866b486142bc4451f6f1d817bee0a.nq.gz
│   ├── 61dd1f38096a83772e0fa24446e5e3deda6feb0c.nq.gz
│   ├── 6597aaae62380691bbd9671ea49243ddc9962eb6.nq.gz
│   ├── 6ada337f1ca6fc076839583ef3578006a5383946.nq.gz
│   ├── 6c04ffa94fb78ecc01a52c52cd916bd9eb371c43.nq.gz
│   ├── 6c6fabcb8aa807a2ceb7c0344f611a895aa9336e.nq.gz
│   ├── 6cc16d529e46ec46266ec727f8ff46bc8a5e3f8a.nq.gz
│   ├── 6dd3d71268c459efc86fad6c9a9c8e91fe36b8e6.nq.gz
│   ├── 6f79d23b619918aa1577011ec61f7e93c62808fd.nq.gz
│   ├── 7028ea67677db42e6134d175684605b7fec548d0.nq.gz
│   ├── 7430edae0f0f0c5e6b17e18f2fac6401bf3c2001.nq.gz
│   ├── 749736a20fa4d81aaf2b3b769787c79a9f4c19c6.nq.gz
│   ├── 77bfb8532c6ee544831963b27cc9d7cec4a8d4b0.nq.gz
│   ├── 77c1a0950d2d3e88557fdcdfa285b39f1162e2cd.nq.gz
│   ├── 78434d35dc6891a01d5e17bb5dfe40839d422655.nq.gz
│   ├── 7cdd97d8ed6ce428ab7a6e9a25f0a762a9ba5537.nq.gz
│   ├── 7e0a6aa1a9a34dbdd66ee88fd2a679e5cdc3b3ea.nq.gz
│   ├── 7e4c35f3219cb5e3e92ef4b58ffaf56109649d69.nq.gz
│   ├── 7fa798928498bf111efd849406dd566f857ed388.nq.gz
│   ├── 7fb9d771c175412b43bcc7965f78dc6cecaf5571.nq.gz
│   ├── 8090599850548975ccaff44c1af0a45db75ec3f3.nq.gz
│   ├── 815cf4e7ebef8c805c117e0208822c9cb12a3467.nq.gz
│   ├── 854df81d2ac393c48e358ff44b5218e12a95ff1a.nq.gz
│   ├── 864f40fb07609d2b3f8ca6350969628eb6612a6a.nq.gz
│   ├── 889841b497077368f69f8d41daf8f6da316c9ff3.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c204e07911c8f20d18bf20a9b5466ae66de77e7.nq.gz
│   ├── 8d8114a116ecf83124f5d8aa3aa21d1f932725bf.nq.gz
│   ├── 8d9ffcfee6f3d924678c6d94a60ebbe716b73302.nq.gz
│   ├── 91a320f27e86a525a7c161121a209f3fa32980b9.nq.gz
│   ├── 91a571ebe2d7c86a46dfe283f5ae63aa159a5bea.nq.gz
│   ├── 932dcd89e44cd7b73da34c3a0e74575fcdfcf1bf.nq.gz
│   ├── 9341177ee984ad32bbca3727b6d951ef3a0ea2fc.nq.gz
│   ├── 95895fb843d4df652ff6fa3210f288d66a1407bc.nq.gz
│   ├── 96fd54620de90bacec02653a7ba4ee26a55977e0.nq.gz
│   ├── a14aeff8f7547e11abad7126b9b579f19fd16593.nq.gz
│   ├── a22efbfc52b38bac6047447a12aba3a7a9f6528a.nq.gz
│   ├── a275d2fde2074366b085c50086e90b3e2b480efb.nq.gz
│   ├── a404b2d125ceeac210b9a8269bd77f1ff19f0e72.nq.gz
│   ├── ad652a140a4e99311f2bb9a283842229d7c71368.nq.gz
│   ├── ae35847e3ea85a46d186af3cf2e90d4798542171.nq.gz
│   ├── b1f05c0f36c7a31df2340e7d9e07a734e75be800.nq.gz
│   ├── b2079480d1a3d206f3cd73e5839ef3436b9ce896.nq.gz
│   ├── b273e339cec1063399471a1deaa8e9363c935a9e.nq.gz
│   ├── b2a83500cb59cb50aa9438f35780cc64758f52db.nq.gz
│   ├── b42057ef8da0e1df514cd5a9e1e00f4e15137640.nq.gz
│   ├── b471553796bc655829f1261f826f699d1e87b181.nq.gz
│   ├── b5edf3a31d5e9b7c37f8637249a185f7a814f1f3.nq.gz
│   ├── b77cb2319e24a839abe5ad2e6db65a73892c9982.nq.gz
│   ├── b84893cad3a472c4a2b10252c091d729cbab655a.nq.gz
│   ├── b9d282af12bc8ed64c8ee7b7ce6ee2d5efc860c7.nq.gz
│   ├── bbbd3cd87af0c9a4f6786bd2b811f4269761d8af.nq.gz
│   ├── bbd1ffac7e6e142f2ede7ad5847686fa2d5dd4b1.nq.gz
│   ├── bd06963bad1728c37974e22a0d3b2ae6d66c29ee.nq.gz
│   ├── bd7cd5240d1e3fb13e6f69104b395cc1434f83df.nq.gz
│   ├── c466b507a14b1ba3c771114ea415700166bf8a4a.nq.gz
│   ├── c5541482230075d4b4800ebbb7ac42fad29e5133.nq.gz
│   ├── c6419a323f8dc4e08c18d56992d80d306034f925.nq.gz
│   ├── c6de953fef33cee0d39781fee7ddeb12a728944d.nq.gz
│   ├── c75c43c481d992ff414c9cd4725ea1650dd909f6.nq.gz
│   ├── c7f2d3f39856e27b2345cdef9bc5a4935817cba4.nq.gz
│   ├── c8a279b215afc026ae7d264cfb12567e7b6c7678.nq.gz
│   ├── c8ca6ba3191c9d8a53707469203049f5c5e5daa8.nq.gz
│   ├── c8ca8f1c9f61dc49406ae57e9d297f63283f3c8a.nq.gz
│   ├── ca5f9cb675e5f8b634596272d5c0a6b15492017b.nq.gz
│   ├── cc4ac0629913537c791905fbb1f35495181443a6.nq.gz
│   ├── ccb5979d6c0d99475bdf7e7626a07ed1b70b5dc1.nq.gz
│   ├── cd35176efe612c34367a049a9cf85fd34448c593.nq.gz
│   ├── cdf78b0794f7fea24c189f71b2d01a98ce8113d3.nq.gz
│   ├── cef5c7ef33e2e1c671bd712bf9e70853988e7bec.nq.gz
│   ├── d2ff706bdea9381e55bf9c6856a36e63ac880449.nq.gz
│   ├── d420e94e47ee69db7fbf057edf4276e24694af2c.nq.gz
│   ├── d69958f8a45a04e3c873795bb82c7b300e9393b6.nq.gz
│   ├── d8c9bdcc56121716655d9c3aa81cde4f8c2c1bb2.nq.gz
│   ├── d9a2149c950845f94271315ffdab54f370f65932.nq.gz
│   ├── db1fc9372c840fdfd161038bb65d78c06184d8ee.nq.gz
│   ├── dc15550c9a87d94264eea2de9ced520992ec4ce5.nq.gz
│   ├── dd5a695aba71d5bf028a91bb43f11b2fc4236dc5.nq.gz
│   ├── de846f07498947cc3a68da8f478a902f803842d3.nq.gz
│   ├── e16bc4338a57559f507cc8f7207ed1d71e681aa4.nq.gz
│   ├── e4bdf4d70b0de52908d76a1babd8e3631d377feb.nq.gz
│   ├── e571ba5079c1bfac7ae20af42f28ef37e0650fee.nq.gz
│   ├── e85a5f7bcd318bb6d53eecd7d7b0db9b5d73fd24.nq.gz
│   ├── e86d41e8f5deadcef3be8abfe8fed850fec75450.nq.gz
│   ├── e8f4645b4317ad6f4bc4138b69d10eafac86eed5.nq.gz
│   ├── e9f878d9613c0e86086303967057b5622cfca093.nq.gz
│   ├── ec557104e2ccdb85f6d9a24f16b94665bdf30de0.nq.gz
│   ├── f08a438c784908359664b345278f94a9227beb5b.nq.gz
│   ├── f40ae851fee81120e36b352f6e84f063c92d596a.nq.gz
│   ├── f44bf2527a12533455fc1563a0010d6e1c0e4fde.nq.gz
│   ├── f814053a48b09ed9812f032f632c6a1939469d5a.nq.gz
│   ├── f85e1b787a997cf547648af0f5d83423bcd0247a.nq.gz
│   ├── f9de1aab73a4b65324b459194f0c72af314c08f9.nq.gz
│   ├── fa7505d88bf766d6fe5a8b9d9df90815b06cced0.nq.gz
│   ├── faee0a337dd020387b1c4cccd6198f3f6c14660c.nq.gz
│   ├── fb3ec006060763c7268b1fcbdd41db7a1f247a05.nq.gz
│   ├── ff47e3cec9d70872b8969495e976b06ee15790c1.nq.gz
│   └── ffe3f7ace84d8db189e0938a48c6ac80e4a9c96a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 39cc074a26375cc8d9d66648cbaf08a7eaff1dec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 163 files
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

[mosquito/aio-pika](https://github.com/mosquito/aio-pika)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
