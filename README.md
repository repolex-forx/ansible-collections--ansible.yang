# Repolex Knowledge Graph of ansible-collections/ansible.yang

RDF knowledge graph data for [ansible-collections/ansible.yang](https://github.com/ansible-collections/ansible.yang), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.yang
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4bca06af5d1ad6e89782c27cec005482a3805f85
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4bca06af5d1ad6e89782c27cec005482a3805f85
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ce632e2902f86c983c4b8e5b98aebbb6c547477.nq.gz
│   ├── 0d0fd821c1ca0c5e13532209dd653b458d196e3f.nq.gz
│   ├── 0ecfa3eb627e3aa7ab0d4e7565b42ea818e12349.nq.gz
│   ├── 1043a10c75caccf3290f6852af4dca04a4232875.nq.gz
│   ├── 10b13a56321805c30eb6b63233bd4e5930695360.nq.gz
│   ├── 110b79550d9b3172f2777abd9e80aced7b8f79cf.nq.gz
│   ├── 171d2284b01ea7b80e477308a505d4d074b9143e.nq.gz
│   ├── 196b5f554510fabcede48263eadda87dd4add8b9.nq.gz
│   ├── 1a94180d4434ba8ed2c309621a2477b5398beca0.nq.gz
│   ├── 1c65ef5d5b62eab5313e5964c9c823392f05cf72.nq.gz
│   ├── 20e7d8842f7cab32b9110155ffab8b3f651c6dd9.nq.gz
│   ├── 218b4c19d68718f2b49d58c0735facb771b26c1a.nq.gz
│   ├── 2437afbdedd8bfc295f4c194b237b21645480987.nq.gz
│   ├── 265507bd1a7a75f2662c175b0bdf0a0c60538069.nq.gz
│   ├── 2ae3996ed8b2700d3691d428f6d837cc6072f572.nq.gz
│   ├── 2eab3d4d58d5417aab5a428e318b6b93001ea25e.nq.gz
│   ├── 3006d2d657ea7c4ead76eeac6d5657cf9916fc36.nq.gz
│   ├── 32128cb11dbc44b95247c1d82ebe4fa8b3f40659.nq.gz
│   ├── 33e747b4997dfc5639825a4e3adca815924b255e.nq.gz
│   ├── 37a5f7253b2766fb81f8cfa7c1f07ac9b3f03cdb.nq.gz
│   ├── 390b63aa06a682d89c0ba17f7abe34d8f743400f.nq.gz
│   ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
│   ├── 3d1601e5842dab66eff09cdf110141fb2f8bfbff.nq.gz
│   ├── 3ed97de3c2c75a461bc4f115f9533464ee900d65.nq.gz
│   ├── 3ffb26f44f34c53a706d9130d42f8ca090bb3267.nq.gz
│   ├── 408f1cc9d089b7b35c2072582c665cf74dc35906.nq.gz
│   ├── 427db7913bc6ca1e6e93cf0e01cdbc95511660c6.nq.gz
│   ├── 42b89727d62c943957c70e273d84a36674959b19.nq.gz
│   ├── 4836271bcd314b6d33bd15526ab0843e6bdeaa44.nq.gz
│   ├── 4b791e37efa1108e0a46c863c600b22ce6e177c3.nq.gz
│   ├── 4bf4426c983c7eced5c42c6b430dfd6a373e314f.nq.gz
│   ├── 4c1ee1a5369b855ea87229053e36e78151c29b6f.nq.gz
│   ├── 4d849c9f1763895590b55b5bebb8b19e5f2142ea.nq.gz
│   ├── 540abd8abcef759e0aa808ac24fadbcfea94ca76.nq.gz
│   ├── 590477678e17fdf288ff68403d5d3af23e0e2c9d.nq.gz
│   ├── 593e277992cea0b859ca03e1409990e5cc11b85e.nq.gz
│   ├── 5e5a3cc4df68b7c622b8b5542576eaca7a5c9029.nq.gz
│   ├── 5f0f7f566c93097e5d6df640762767cff5e208bc.nq.gz
│   ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
│   ├── 68556934b41cbc9c9e27e4860318abadc7e8550e.nq.gz
│   ├── 6ada631cb033ad64d354e7da222063ba4897c1ae.nq.gz
│   ├── 6d1296395ed943a2c3b33454d5b52fcab069fd7a.nq.gz
│   ├── 6dbb1aa3975b9933c82059312843e0b406a818fc.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 749fac42616b905198181f597527dd0c2d3db8d1.nq.gz
│   ├── 7b286da9e9c02fbb9c19a41d8295b8d2aae3bafd.nq.gz
│   ├── 7b95e890b5925e46984c495acc51df59d96455a1.nq.gz
│   ├── 7bab234abae85ffb47808c4d89bc6242929414d9.nq.gz
│   ├── 7c3e0fbb7012fd77928f90651a2324df9ed82ca8.nq.gz
│   ├── 7cd0cb203136017549831cf09b23d83f2e49e317.nq.gz
│   ├── 7db2473f1ae026b8f45ce37bf9776395a98b1ee5.nq.gz
│   ├── 7ed78a2a7f9e9d9402c2a1b50f7f345c94e48672.nq.gz
│   ├── 7f70b903816761288693f57d6a30016794689bdb.nq.gz
│   ├── 80a7373916debbcee984273d339cae651cadb520.nq.gz
│   ├── 815e3ad1c2b2de8b04aa47853c555b4a0d1f9233.nq.gz
│   ├── 867f3273b99496de6693c2cb87c105eae653f486.nq.gz
│   ├── 86d22be3a6c22f868b69d8e92968a636805303a0.nq.gz
│   ├── 87ae453106434bb8bf5f05c32db743cf992ff64c.nq.gz
│   ├── 8d9bb70b834cffd1056efa08377df15e82928036.nq.gz
│   ├── 8e68aa3ec801b174874ea29f387635ce82446cc0.nq.gz
│   ├── 8e71ff82600215fe1d8dabfaa00841fc237631dc.nq.gz
│   ├── 9237b107ee216ef05ef5d67d1648354c9d26f956.nq.gz
│   ├── 928d0b7c3755cd41947ecae9d11a3ce8d4d4749b.nq.gz
│   ├── 93e06d1ece6e941fc4003d31eb48485363fbd154.nq.gz
│   ├── 95ddf3253e4a8048d100406f3c5eb55dafb9d8c4.nq.gz
│   ├── 970e94ce4d6ed16c20b418cc5c7d7468e9afdad3.nq.gz
│   ├── 978c78eb5bd015e572361b801d4b3dff12006116.nq.gz
│   ├── 9c6f00dfd108aea240c79262bb00206061d7ef4e.nq.gz
│   ├── a12ad6f0e046aa4819d51341acfa3b5c910d7c13.nq.gz
│   ├── a7b2d4a5d8f6e0c508274fcb1c5913c216010be1.nq.gz
│   ├── a7fec4d3d0685b04863c51100f66b02dd2f69a9a.nq.gz
│   ├── a9c7df89b0cd817857f7f4d8825c985c87baa7d1.nq.gz
│   ├── aa1de3131f6a780d1766f887efa0c5677f90f432.nq.gz
│   ├── abe36fd0373256d392e9f8d5f36072d2b03321d5.nq.gz
│   ├── aced77a179222827951f785b9e8d71f364ed7250.nq.gz
│   ├── b120bfa32ad22c4f930298e31ddfdca78d613d81.nq.gz
│   ├── b6da50db3e19c7a0dd266524f77df5b45e0d782b.nq.gz
│   ├── b8d06999b99c8149061ac7475a7c9c1e402d573c.nq.gz
│   ├── ba03ffbe52083fcfff7e167b2855742bca16988f.nq.gz
│   ├── ba0ade4d3edb505428b0d27072fd82517721f17d.nq.gz
│   ├── bd3b1f25c1773f88aaaf25d3c0663b0569b40264.nq.gz
│   ├── c0a4788aae4a891b87a689bb999c4db3fd11bc70.nq.gz
│   ├── c3d9d8bf31284191d1d56e3362773baa2cf2b529.nq.gz
│   ├── c4d1b7456f3c5e4ea068cf784cbce8b4ee85cb84.nq.gz
│   ├── c891bea2afeb8bdfb1c71ceb8fa8a4c931a0bf45.nq.gz
│   ├── c977817416cc1f89492ad3a0b35cce754f8185aa.nq.gz
│   ├── cc5bc0ea52cff7ec14543238dc790959313fb396.nq.gz
│   ├── cc89171c747f89210bc975e68d41917388e3e1d1.nq.gz
│   ├── ccf12932b55e223cab13aa9a721fded0b926ee4b.nq.gz
│   ├── cf060d2b236a23990c15bab9f913ae6695f3958f.nq.gz
│   ├── cfb34e1ec71f548eef13fa94089f8e9ac29fb48c.nq.gz
│   ├── d12c1efe28855cdc80e307a52f723a465d57920b.nq.gz
│   ├── d3f31214a9d060bd64f1ad4528d7cf520b075553.nq.gz
│   ├── dc7f399498a710a48aae78f434bb10b804202d5c.nq.gz
│   ├── e03264bbdfea245d5f093dcdd08f17aee6b572a2.nq.gz
│   ├── e3e5966e40943337d9c5a64a67fb543c55caaa6c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95eea55531183678a5e088f4e2c8f77e08a830b.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── ecde68437767fdca6faecb75b9429059968bc9eb.nq.gz
│   ├── ee58fa3ab0042120d5607b8713d21fa0ba845895.nq.gz
│   ├── eeb39b604256bdda6b0ac9acc1e165179c0f8585.nq.gz
│   ├── efce966314f7c78dad7f14527cef4443c4acec32.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f39ecf662f67ca3889d40bfc69b9898500e202f4.nq.gz
│   ├── f50de4926c1b64d0ad96390719b0f8c9349646b4.nq.gz
│   ├── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
│   ├── fe4e17619ebe184bc00d7fd48f01131f0956404b.nq.gz
│   ├── fe84f1b159b74c66ef26d82166307401dcd51dce.nq.gz
│   ├── fedc50a824921628767b6c41f27e52e7ff9824d6.nq.gz
│   ├── ff2586abe976ed614eea2b4793ceee4e8c30fb7f.nq.gz
│   ├── ff29fb466860c5426a493757d8e71388e040f792.nq.gz
│   └── fff562de909b74bb35dc049541319b4f1f02f11b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4bca06af5d1ad6e89782c27cec005482a3805f85.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 121 files
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

[ansible-collections/ansible.yang](https://github.com/ansible-collections/ansible.yang)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
