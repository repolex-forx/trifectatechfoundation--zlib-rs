# Repolex Knowledge Graph of trifectatechfoundation/zlib-rs

RDF knowledge graph data for [trifectatechfoundation/zlib-rs](https://github.com/trifectatechfoundation/zlib-rs), parsed by [repolex](https://repolex.ai).

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
rlex download trifectatechfoundation/zlib-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 734b2c1f42e2efaafe04cbab9c61cfaa5dead9ad
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 734b2c1f42e2efaafe04cbab9c61cfaa5dead9ad.nq.gz
│   └── repolex
│       └── 734b2c1f42e2efaafe04cbab9c61cfaa5dead9ad
│           └── chunk-001.nq.gz
├── blob
│   ├── 00518740387fa2202a59faa0dde967059b93140d.nq.gz
│   ├── 022654be73cb6155938482436f22ab8c77324053.nq.gz
│   ├── 0247f6d0d8b740ccb329db8be8785c1e2a59fdae.nq.gz
│   ├── 05deecb09dae9cdb7ad3c1588ac0f80becba3e4b.nq.gz
│   ├── 06443f36db9b1bf0054c61ae8ec7e1609e7f8a35.nq.gz
│   ├── 06788bd034abfa72d284ea7028ff951456d2958e.nq.gz
│   ├── 078cf1755dc0853e97ad30fc7af4d6af0b67047e.nq.gz
│   ├── 0a66c7ffa80dfe9e00e2116d71d7b2ac9726f114.nq.gz
│   ├── 0c3b0ba1e7056df1550c1cef9c0cc11e6ffb9ee4.nq.gz
│   ├── 1161d46e17e622e5d9e8a4df355b04bb08cb6575.nq.gz
│   ├── 1b4867db2a12d0da941de497b0ac322a2b7fdb29.nq.gz
│   ├── 1cc6ad7810e938c692ea660f0c582cc8a4a5da6f.nq.gz
│   ├── 1cd65a54302b392372bddf08aa858094f36d40cb.nq.gz
│   ├── 1d79949788956cdcd635f20bc67797e63beb8df9.nq.gz
│   ├── 1dbdfc56e436c07da70b32e29b086fc0e649b8af.nq.gz
│   ├── 1e7c0ad8c802e65be0081e745509da4449d33021.nq.gz
│   ├── 1f5a9bc85efd21f3cc3fd05ff099f5fb53e5815b.nq.gz
│   ├── 234b38960768270cfb6b7e7f110d1a90b3f084ae.nq.gz
│   ├── 2b366e0b962175d1a37f05740ad7e06c9bf274e9.nq.gz
│   ├── 2b937a7f43ee323e096b319e7a0269c47bca53a4.nq.gz
│   ├── 2ee4e993376ee77a74a6348d3f13c9cc2fd2ebb3.nq.gz
│   ├── 2f0ce72b1255a00403f3f2e8ab3eb48a7ca7d1f6.nq.gz
│   ├── 2f2556f13faf4283eeeb85bd21f041a208659449.nq.gz
│   ├── 2f68bd556226b99dfcd72e438ff23aaf23f0e954.nq.gz
│   ├── 324b9f74e147094ad0b3a320d9c83f095a3c0cd7.nq.gz
│   ├── 33ce25e29fdfe0015ec1fadccfb1742462019613.nq.gz
│   ├── 33e2b2aca3708dd812230def2ee3728ecd04a26b.nq.gz
│   ├── 3583a6ad1da498ff9c68d1649e22eabe187f347b.nq.gz
│   ├── 35d85649e5336352abf9ef50b7d999809c9654d2.nq.gz
│   ├── 370a80ce58e07f7256a0241bec72be0d42d8f6a0.nq.gz
│   ├── 41110cc731c8a9626b0f0af3f671325ddf18426c.nq.gz
│   ├── 48bf712bf6ee9cbd7d0e6b16025174356bb54f87.nq.gz
│   ├── 4bb2a9eac83dc1acbea8883d6eb88f5b3746a1b9.nq.gz
│   ├── 4c0c30dd4f65adcba5de07e118ec529b8e50d564.nq.gz
│   ├── 52a0150b60a6f4466657926d80177f1157c9e977.nq.gz
│   ├── 55faa3c0a107935456f375b1e67383d48decb68d.nq.gz
│   ├── 5931336039685377230f19c2796ea6a04076b638.nq.gz
│   ├── 5b179d7a841539e691bf2fb036cf64a55ff89fb2.nq.gz
│   ├── 5ccca248c52cac7f014a49c405c3f0ca016b71c4.nq.gz
│   ├── 5e3f552f3e5c91d27027340560df71bb5cb73c00.nq.gz
│   ├── 5edbff64804ae1d972614d482351f40003797581.nq.gz
│   ├── 5f8035933239fb42d883cd86f4ded6a992765125.nq.gz
│   ├── 5fa6a08044e7c58db0a5a254d10ec702f0830ecc.nq.gz
│   ├── 61073e9d5c5f4efa879657d75d25a3e9b63dd234.nq.gz
│   ├── 66c6665f093e64de3624e3b00cacf305c2d52150.nq.gz
│   ├── 6cb0a0df010469af0d5ae1156a3ae8b325ffd43c.nq.gz
│   ├── 6e1c668847215e3a214eb0b23901b5683ef0338c.nq.gz
│   ├── 6e9a7d531017675bf665484d143787b66c7dd19f.nq.gz
│   ├── 70e17b97366cfb023820042e0d366adbcb542bd6.nq.gz
│   ├── 73f955ad6dfd16a014241aaf230c2f835fffe8fa.nq.gz
│   ├── 76cb7852f2be513ec8109e87dc5cca305c477952.nq.gz
│   ├── 76d00bba8514523a4a113329ad125c050e8c6114.nq.gz
│   ├── 771cc1bb29be1e8e65ad67d2ad9248c9b98e76da.nq.gz
│   ├── 79e04ed4c4f9bee8fad2541bb458840298533703.nq.gz
│   ├── 7ac92edd375ecca6cf6bdac3a966ed597e8d1e75.nq.gz
│   ├── 7bfdd0b1744f829410033ca5cd9d4a748a89b2b2.nq.gz
│   ├── 7d56722faf8a88706fc64aaccd2c674b5bad6e58.nq.gz
│   ├── 7d9645680d0bcec26657076b59ce86f9b39b6dd0.nq.gz
│   ├── 7e99b6e4420510c79fe636c47bf7c2bb32ee918d.nq.gz
│   ├── 7f253b1a6a46afa1d0ba9bb7b0dc1f8594c13857.nq.gz
│   ├── 848b89342d3670552991c94bd0b5cec94620cd2f.nq.gz
│   ├── 87ab27b524656844ffee710ba5b4e57696152481.nq.gz
│   ├── 88e2e30b96f021a72406dcecc6a37865db1a0407.nq.gz
│   ├── 88ea3312cc5c76e63c7a62864c753ad5b6c4f3ac.nq.gz
│   ├── 894b0e209e469267823636f9e89a944f32a2610f.nq.gz
│   ├── 8982710598739809c201821c89a2a296886c8fb8.nq.gz
│   ├── 8a1a77eb9f0635ae83cf63b35faf8d2e351788d9.nq.gz
│   ├── 8cc08b96dfe5b00d0f82839adf2362e66cb07bd4.nq.gz
│   ├── 8e3b73b0e5460d80cadc8b763aaaabf12b8c3222.nq.gz
│   ├── 908f6a54779487b9cda26fefbcd5d520855a3f4e.nq.gz
│   ├── 95f3fdd3c7177420ba0797a3eeab7662fb8687a7.nq.gz
│   ├── 969a7eaac798348d711782fa6f3a62c9898f79a8.nq.gz
│   ├── 979949aacd0c0a3a4df6343ecfce64b490c51cf9.nq.gz
│   ├── 981aebb53edb978307051120db644b8cfe5984c9.nq.gz
│   ├── 9bcd710a6b7c6186d8691ba333f8189572342750.nq.gz
│   ├── 9f6a198759569388d3942cc08a902aa2028ed4e9.nq.gz
│   ├── a17b5ef0c3e59ee3ed9480132eed6a0e5512029b.nq.gz
│   ├── a53050927712cfd96a7715d37e4a1d51e89a7ca4.nq.gz
│   ├── a8f4122e8d6e0cc4fbae1cd0d1db0dd9e4c5475a.nq.gz
│   ├── a99a144f3ee11099cae4fd289f264558d8cffe7b.nq.gz
│   ├── a9ae9b1bd9d50fda19f43de99ac6824281e8852a.nq.gz
│   ├── abc8618781a476964037915f97d8a0bf86b3f388.nq.gz
│   ├── aea2c66ef3a8df7f03c0859e8f068173438e13d1.nq.gz
│   ├── af8bfc3a57440adbce47bb01e792358fc72f9145.nq.gz
│   ├── b1c3f20d8f1bc2a4a285269d21afdf458a75e3f0.nq.gz
│   ├── b3325e4a2bb578419d6c7fa412aaa78d493ff274.nq.gz
│   ├── b85656e3a0ecc1d4ae73285c3fa511e697d61991.nq.gz
│   ├── b8f8dda0ee82a6ea8c78cf95102e83e2308c342a.nq.gz
│   ├── b8fc5771088f333149e911719af1cc4e4c227ea4.nq.gz
│   ├── b9659e613e028a74c965c57da8b419643688dca1.nq.gz
│   ├── baedc226ba67d28854b4d188cd667dbc47457f1e.nq.gz
│   ├── bb1a17adc026dfc4a402919b4ac0b9187a9e77d8.nq.gz
│   ├── bc8bd719cfca6a987a83980fc7694feaa582dbdb.nq.gz
│   ├── bcc68fadad7abb30c616f77fdcd6c6d574cfc121.nq.gz
│   ├── bda0ce68ec60a66526906f82d28efb4425da6751.nq.gz
│   ├── c19f5cf6f8b5844dbcd4c11f779936c465dd5744.nq.gz
│   ├── c34f4d1b5105404617836d619879e7ce8aed3a52.nq.gz
│   ├── c7544d7df5c44b6460b8ee29a1bef526fc9e73a9.nq.gz
│   ├── c80c0e9740b6bfc59536a2d9c1b1cecc08dcd4f3.nq.gz
│   ├── c9a67ac1315ee9d3dff8191a6fe6fd1d7728a22a.nq.gz
│   ├── ca52e5a46b60f3012cd2f72252c44743e72a5998.nq.gz
│   ├── cbacc35a87912d73b95563f12cfb9125af1cfc1e.nq.gz
│   ├── cbdf486b95094f754978028fd5fc27d6d19cb855.nq.gz
│   ├── cccaecba4f9ffebe1cc39f32f5be4d46e4311229.nq.gz
│   ├── cdbb1c43086a9f8e8612b2d58e32feac422c7456.nq.gz
│   ├── d1fe8ec57c46cf00d712addeb48961cca910759a.nq.gz
│   ├── d4e00a2ec4e09097671eeb0fb1ee46770133a02f.nq.gz
│   ├── d66b29931fed6daa6376de746a2ea84b91f6aa99.nq.gz
│   ├── dc404968eeba35eb477043b33371ee6ba67aa7aa.nq.gz
│   ├── dd4583b258b447971a17302b205244551e02ae7b.nq.gz
│   ├── dd48b06b5aa5b7c19036c97297f1f275008e8386.nq.gz
│   ├── dde80faa4fcbb396fe5a9548582ed420d561d95a.nq.gz
│   ├── de4328c5e5280a5dfd04957dbb69a05b51de7ca2.nq.gz
│   ├── dec8a39c29528028ff8739055fa82a164d4d8e3e.nq.gz
│   ├── e0a48a4e182feaea0269c2ef1942927594b3c70c.nq.gz
│   ├── e2acb932f3dd82f389ec3b585fb5e1afa4448517.nq.gz
│   ├── e793bd1d2bb2b7e3b2889660cd80522f1208e72f.nq.gz
│   ├── ea1d49147a081ddba9e1f5a6ff8b53b07c6bda78.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ec8dc4b34facb309d2896ae6570b82c7b6b83206.nq.gz
│   ├── ee6679e3e1acfd9817840da4d063c52be07358ec.nq.gz
│   ├── f21a18da2e79f5e2ad0c64a310996157497a4fae.nq.gz
│   ├── f31d549008eb9b4d90935d3a80dde7eab14240ad.nq.gz
│   ├── f32305a0266432c50e8f149adc4f7a0feeb4fcca.nq.gz
│   ├── f4a44b0a2f8d9b2de18db58f2238d2b18f831f8b.nq.gz
│   ├── f4bcfc45fe1c7945e81c0dac3cf5343c906abafc.nq.gz
│   ├── f4d8c94b3675d52597405823b68cbf0a97cd1d0a.nq.gz
│   ├── f5cf83307fd879d0e68da2865f1fadf36297ebf1.nq.gz
│   ├── f91124fc06a9b4969cefd994e60d45df37d26873.nq.gz
│   ├── fb37f911a5be90555e73c3ad0d433eeeb40d48ff.nq.gz
│   ├── fd711d62a6b84c59021f5b6d857695206e549ab7.nq.gz
│   └── ff51787ade9a14e2a106aa2d217852ea970177ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 734b2c1f42e2efaafe04cbab9c61cfaa5dead9ad.nq.gz
├── filetree
│   └── 734b2c1f42e2efaafe04cbab9c61cfaa5dead9ad.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 142 files
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

[trifectatechfoundation/zlib-rs](https://github.com/trifectatechfoundation/zlib-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
