# Repolex Knowledge Graph of jaredpalmer/tsdx

RDF knowledge graph data for [jaredpalmer/tsdx](https://github.com/jaredpalmer/tsdx), parsed by [repolex](https://repolex.ai).

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
lexq download jaredpalmer/tsdx
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 5b1aa0d67788bfb5ae46e6845e2e4e07c1c73e99
│   │   │   └── chunk-001.nq.gz
│   │   └── 64c50943905c983c98613944d50c20565efe6691
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 64c50943905c983c98613944d50c20565efe6691.nq.gz
│   └── repolex
│       └── 64c50943905c983c98613944d50c20565efe6691
│           └── chunk-001.nq.gz
└── blob
    ├── 017ed7fc625af8b2092d23d0c9a230dfeaa939c8.nq.gz
    ├── 0466183af6ac8a9f74ced8fe1d8bcbf6c85dce5e.nq.gz
    ├── 0605722ff1c34e04003b1d8c666de134d31c4f91.nq.gz
    ├── 070a0e96a85b35955921e1f34d9d5fb394c343c7.nq.gz
    ├── 093f8f28ae87b17d49a116249ce4607b4ed70f1e.nq.gz
    ├── 0a21afc94c2b49d6aa8a29b59b5fc21d651e198d.nq.gz
    ├── 0a394b5648c5675463f5c0a5633699e11830436b.nq.gz
    ├── 0abb9556d83038c11821d2ad6a3290d1f3e53a38.nq.gz
    ├── 0b055a4c5f9751d8d444fd464d5a02d3cd448ef0.nq.gz
    ├── 0db79be85e8c4a7091f0e3efbad40afc089bc7fc.nq.gz
    ├── 0ebf6e65e1dc243b2b331b0a8f232b98cddb9042.nq.gz
    ├── 0f3ceed712716c2e026468d72a2dca6a68680de0.nq.gz
    ├── 1206e34f0c8f3cb11c02684a67193733a9d0f37e.nq.gz
    ├── 134273f32b80e247117d408dc5a100298f6c2414.nq.gz
    ├── 13959e9e9f0b31b3eb5fbed486318909c4fde926.nq.gz
    ├── 148b1e4c0c6e0fe2218efe720bc5359fe01538ab.nq.gz
    ├── 14fbb03823f3fa17963be6d3701b86f96a75e58e.nq.gz
    ├── 17281bc0e9d79c8489b95da35b40572b696d0f19.nq.gz
    ├── 18a857bd9c85f264461d675e8fb51a520a687152.nq.gz
    ├── 18d99216c0bc098fd1e49c8f2509a4801a1ce383.nq.gz
    ├── 190837ce6a946289fd20160cb10d0df9de0dbb72.nq.gz
    ├── 19f82bd55ec341038ff33c04d93dc7762d5f604a.nq.gz
    ├── 1b403293a279ff50d4ae27209825bca239d6ea2d.nq.gz
    ├── 1c0291bd547249042ed7e3a10ea6d6bd73ea9942.nq.gz
    ├── 1c4970a49c89218a509d3776d6bcb82ad81e7af7.nq.gz
    ├── 1db53ccd94d1fa6cd53e013c6439445c89cac786.nq.gz
    ├── 1dd4684d0c451f0731ef357b19ccc70d18aa8064.nq.gz
    ├── 1dd784ca04037785827807b5ea521959c2da2d6e.nq.gz
    ├── 1e1ccd206e4293d82895681f281c293ed48f8c72.nq.gz
    ├── 1e2e4fd9cc4639ced6142bd2cb525571e8cdc8b5.nq.gz
    ├── 1f88d1ab1a4f21731229799819945d865cd598b7.nq.gz
    ├── 1fbdfca663a58cda4c7b75f34e22994e763e8fc7.nq.gz
    ├── 1fd11ffcd31d85f034642ce5481b9c238d74f629.nq.gz
    ├── 20b67006d1c972c7772e33cad22bfe613b443c1f.nq.gz
    ├── 2368900a8f626dcd25092f2e1e119028fddfe9bf.nq.gz
    ├── 2375096f988496ef40b826b3749031d7338dd2b0.nq.gz
    ├── 23d99f2047a9c5a1cd6a7f9add2889c6862440be.nq.gz
    ├── 251f1f554da7af4d6f0be51939b621de5015b0ad.nq.gz
    ├── 261c4f755efa7bccd5af9c238b3591c5eec0b03c.nq.gz
    ├── 2697c2df32e44927f69b2a92b855e6c1c5f2a594.nq.gz
    ├── 27f439c059e4a2365513e70928f385d32332e4a2.nq.gz
    ├── 29851286a3747afbe484e145b1a1d6f63668df48.nq.gz
    ├── 29a9e1e097059899872f8d2fe9007c3eef5993d2.nq.gz
    ├── 29ae5f2e49d36f64bdf5a53ae5759f557f8f37c7.nq.gz
    ├── 2c85b2d99197d012afeee53de2f5360f3ec98195.nq.gz
    ├── 2cd9e2d4872e85686a84034217dc171d1e3981eb.nq.gz
    ├── 2dca52fe013dd8c0540954a6d7b6fd13828afd6c.nq.gz
    ├── 2e4fb8f9a5ad4a273f42ec4e329fe640cd1fff54.nq.gz
    ├── 2f047930570088724f0cdc3598b0699a9e3532a0.nq.gz
    ├── 2f9cff2f125e86d3bc8cffc1c80c7c06f9ba709a.nq.gz
    ├── 32563255767d93f533081c08d2fa22d4c8d12246.nq.gz
    ├── 33c7ef5073ecf1e45d5b2ba9e29a79a2b7f9dd63.nq.gz
    ├── 357e436548f165eaf4e5042411d8f982d1c07ca6.nq.gz
    ├── 36101d13ad520e180b9b9f1de91a1fa88a5a21fd.nq.gz
    ├── 37d921372e53279717a09eb8171c4c90a58329b2.nq.gz
    ├── 3a5c23d07e915e01ca05fb1f77c1bb9a253f7c5e.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bf8c80b6692d54192d4677dcbb4695f67a843da.nq.gz
    ├── 3e25719d7adeb90aad43ef2fe2e4ce7b5decd168.nq.gz
    ├── 3e94c821f3caf91d32a69dacb87d46dac9ec076e.nq.gz
    ├── 3e9f7e64aacd6281a96438708eabf035820fec55.nq.gz
    ├── 3f53a7083e841febe8accfcdf88c1f0b5ef36ce4.nq.gz
    ├── 41333a7376af556e492996e59aa604904a0720ea.nq.gz
    ├── 41e6dad1505dde28ffafc52c03d0eef7ab174ba0.nq.gz
    ├── 4278d97e16a81cbb7861ba573d65abcd8d26ef02.nq.gz
    ├── 43e06792a87634ae8656f47ff7d3ff93f8ebf1a0.nq.gz
    ├── 4487cc09d95e836aabdcd58997eb825209a09ad7.nq.gz
    ├── 4494998c7045a767b775242bbe1445abaa7d7cd6.nq.gz
    ├── 46b77c994865ff965e344f8694a77420ccc1325c.nq.gz
    ├── 48b33231e0c4a44d0fc57fa8debec4767b6fb51f.nq.gz
    ├── 4964f43a3c61ef4c23e6740f9b50138b248fb606.nq.gz
    ├── 4c9d7c35a40d3a214d791e42c2756ae3906ff785.nq.gz
    ├── 4d3bf87404e29b27df47d82997b0e1f4c6832df8.nq.gz
    ├── 4ec8269cdab633b6ce1963adbb110261daa31cac.nq.gz
    ├── 4f157a077999e5463ae0c6932311f06b7bbe646d.nq.gz
    ├── 4f6ddd8928acec9df9c50f0234fea7bc8c77a74d.nq.gz
    ├── 50350ac2a38226f573fb3abdc37aae9a9464de61.nq.gz
    ├── 50c8163f8b1c5bb7f4254c187521ce108be18cdf.nq.gz
    ├── 511f50b8978622dad319eaef939a3cbcf3473b9f.nq.gz
    ├── 51c83342c5e9aabc80dde88d5b0bbdf4916be99f.nq.gz
    ├── 535e4b7c98945caea9a0a507a0f461b13b343459.nq.gz
    ├── 547e772e3d72f85431f8f25f36a5e60e95bbef3f.nq.gz
    ├── 549e2626e22629214122c75d0a5ca62251321d56.nq.gz
    ├── 55e5de128a98bb04a87834a855fb89a760db5f4a.nq.gz
    ├── 587e4ec7aec54ca7894daa54538d67aefe8541f7.nq.gz
    ├── 5d51e42353622d1f79e525f9e14d23d6dc563853.nq.gz
    ├── 6021cda3e1d9aadb3b142521ab1a97242dc8750b.nq.gz
    ├── 61ea2c9dabee77ac4dbd8d3c501c02ee8e3514d3.nq.gz
    ├── 623127f60ae9af852543a06bc209b8adb795df50.nq.gz
    ├── 627aeee88f0d3a4a71707e7a7563940962d7b3c9.nq.gz
    ├── 639f22f266cbb955f860c13b2f34dee5de4371f3.nq.gz
    ├── 64df4453becb1600701dff129cc4c70a69989790.nq.gz
    ├── 65a8af7b4047d17a27e17543dd4977f652965542.nq.gz
    ├── 6954a3bd05ef3404bf16c10e29d25523302dce03.nq.gz
    ├── 6978989b40bf3df7834ccd99ee642bdb3dd3dbe0.nq.gz
    ├── 6a6ee8983ba34700ac27ffecaea6a696f1fe6ff4.nq.gz
    ├── 6b02c7eae1a3a877c724deaabaf6d9c5220ec9c9.nq.gz
    ├── 6b596eb54cce02af51be26a0e6e06f0cb15e2c09.nq.gz
    ├── 6bf847bb59efe1345294abde7f3033559341f165.nq.gz
    ├── 6d182ff235978618fa39659f3034a380f487b884.nq.gz
    ├── 6f81a6d410bf66e9935cce97201230fb51fa8bc5.nq.gz
    ├── 6ff07ff6cad3a8eead96392e0294f4c3792fdf61.nq.gz
    ├── 70263d54042eadf099e1edd2321d65c0e76e40cd.nq.gz
    ├── 7129bb14f2a2ece85040c85d22ef5bc2eb006060.nq.gz
    ├── 73387c60e736897662f08ab83e3c72d9af248c71.nq.gz
    ├── 73a94aba1285bc4484947bc0e224de608d549bb9.nq.gz
    ├── 76bc183f30ac257ea6063ad7570d1232a48c5d13.nq.gz
    ├── 77a8e933b220175eb46cfa792e0c5a2de91a364b.nq.gz
    ├── 77ce3682f45d3893cb1ec8db2176321bf7a49fb9.nq.gz
    ├── 791d54b6cc12f6e28ed1efc28d1b38eb181952a7.nq.gz
    ├── 7a76df426bd3b6e54752a584a69096d7a3075808.nq.gz
    ├── 7ab8ee5a150661b9cf3f7e6819985a077acf39e9.nq.gz
    ├── 7b16277c1d90d080bdafb05aaaac8b9d2d73a27a.nq.gz
    ├── 7c739c4ec5f48fb40a90d3a1f68697f6503f9217.nq.gz
    ├── 7d077e35389ac614fa287263709efa6ec48d6b55.nq.gz
    ├── 7ef21ac59ff727233008e13bb78e3927094faf5d.nq.gz
    ├── 86999b600f9edb9c09530b1cb72df324f4a94b7b.nq.gz
    ├── 871a05c3010ff986a494430f32651dc96d18f8b2.nq.gz
    ├── 8796653a5585921dc25b4e2f324de1b07ea3bcf0.nq.gz
    ├── 886ee128e46909855c3bc041be4ed8208d77b915.nq.gz
    ├── 8b72362eaa7b73ddad7ff3a3c51a13e6bd51a730.nq.gz
    ├── 8ceb5505b5c82e42a0a3702b8dcbc271600c026e.nq.gz
    ├── 8d2bef0639bd7b138bc4844ca1bf08c8a2591e63.nq.gz
    ├── 8d883d5ad20c85bca8c43fa29080783eb2834c34.nq.gz
    ├── 8dd5cddd7ecaa8571d0413e7d04f7f29d58d5371.nq.gz
    ├── 8dd6f47578076735dbf496e20abbe8eb61553e85.nq.gz
    ├── 8df77828de528fad057ecae945254a8f117bcaa2.nq.gz
    ├── 91ce0a5e58e381dfea7e6c2f5acc8ed6b41f06e5.nq.gz
    ├── 93eb55df4e9a18cf120c44a96e873f0bf34b3636.nq.gz
    ├── 94232cc961495577ec39dfeafe495d054bb2e3f6.nq.gz
    ├── 9474104db54b2f40ee0007e0437faeaea3c0779c.nq.gz
    ├── 969a70a4a125473e735f1f75d47fb24186b97ae1.nq.gz
    ├── 97a32651d48b2758318bf638eb127d8f97268ae7.nq.gz
    ├── 97b9b5ca3836de2149fbbdd0e512a253e895993f.nq.gz
    ├── 9898395031f5a3d8a7f7ef0445ff4c97015d40f5.nq.gz
    ├── 98be9e794e5bf4bdcce3f2076fae6d309df91e6a.nq.gz
    ├── 98c45705251f7c6eb7342309ab714e9a5e35938c.nq.gz
    ├── 9a3fd1e2e0f12eab85656d478cdb9a569170f54a.nq.gz
    ├── 9b4b65aded999af6e8a3d23f80b2981291ff915d.nq.gz
    ├── 9cd3924d8afd8f1c3c5cca68f0fbac01bfa75990.nq.gz
    ├── 9cde3388ca0d86e8e69ad2ccc63b237fbaec6c10.nq.gz
    ├── 9db92b7032f2f8a23cf306a7b57c982617f592ce.nq.gz
    ├── 9e442e40f18231fcd8a4367ab0490a44388541d2.nq.gz
    ├── 9e6ca168e55b70b311be137ada8e3a97a0dafb8f.nq.gz
    ├── 9febdeee4abac940d167a5e8073b4300c6d29a82.nq.gz
    ├── a33e7587def3f5019ca8bafe8e117c49f6787412.nq.gz
    ├── a36cb6ebef65185be57196b38f7667f2896eac7c.nq.gz
    ├── a50960f5ca54d3f7ec4c32378f5b037ccff30dde.nq.gz
    ├── a5e84ab66736bae0467da6acb2b82ce319b34fd5.nq.gz
    ├── a6cbd6da215a4120e0cdeed47d9f0dfbaec439fc.nq.gz
    ├── a91d55856f7b919a80c9e0ee3c1275b570243c94.nq.gz
    ├── a93bfc1676dab6472e368708973f5b1795435875.nq.gz
    ├── ac4f03896925f51d5628c40c61abbc4ae74728f9.nq.gz
    ├── acea7088aa7d5a5c3df8637e412516384cb50fad.nq.gz
    ├── ad040107f449118ce4d78f701f98dbaacf840c22.nq.gz
    ├── ad55615e4d70a7d872f2bdfa8e192e4049a50f6d.nq.gz
    ├── ad8a3c9befed5a59835d8c865ac5dedb0b4d9c17.nq.gz
    ├── af27ae37d48bb9f4ad964e22c20fb9f82befeab1.nq.gz
    ├── b04a49dc39cbfb5473a29eebd75b7b931a7846d0.nq.gz
    ├── b0c6b7f3318510811ea9d088dd11a1fcd33af087.nq.gz
    ├── b0f764913b3ba7b11b5416705550c6239ec9716e.nq.gz
    ├── b184199fe84753df814ae90938d5a2b92a1e1236.nq.gz
    ├── b1e42b698b8c57b412550f5e3b893889611dae92.nq.gz
    ├── b1f8350b4ef0baa8e10c8fa39a6971adba9ecceb.nq.gz
    ├── b3a4dab9d480d28ee185ae39e68943ca401267ba.nq.gz
    ├── b639b0f8f3d504459674c03877321902b7e936b3.nq.gz
    ├── b6e9b85d3122f7a16cd78763ff8beaff1f31e7ec.nq.gz
    ├── b71198afb82acced67993e3f324399832ef331e0.nq.gz
    ├── b73570f62dab83ae29aab0420f5dc26b51f44d38.nq.gz
    ├── b75b6a4cbef3a0636797b8da337744f2dcf718b2.nq.gz
    ├── b7a1d3c2ac8470d0f16d0f01d968d043a9a105d0.nq.gz
    ├── b95a8e4a7295deb67460eafed749a4b7e1c389f4.nq.gz
    ├── ba37a8b3ba9ed1a28f4989e6e0a67b88562a75f0.nq.gz
    ├── ba3c055ed8513c31a341bd81325b6f2da339d28a.nq.gz
    ├── bb0179011be4a032a972fb41025a5d6b6e0d9d48.nq.gz
    ├── bfd75cf3f3447c57ee93d11993a073fad8f98e95.nq.gz
    ├── bffd68c1d48b23002b1e04fec7be92181c0ab9ff.nq.gz
    ├── c09ca252e884abfcb547e7ce59479c1aa2c57808.nq.gz
    ├── c09e915a839c98133b366856abcdccc9abb3b97a.nq.gz
    ├── c0dcbc3b0bd8c7006e312023f26827eae55434a5.nq.gz
    ├── c0de22055cdc519024efcc4b1c564305190249f7.nq.gz
    ├── c39fb5316e589b5151462e2d8fff0740975f39fa.nq.gz
    ├── c3ee72b81c070a64ecaa16ef84171bfe64bd4eab.nq.gz
    ├── c5f36b4614e714410ffdce15fd025089b25e41f4.nq.gz
    ├── c7bfec273bf3e69b2e2f9109abda915c5039360e.nq.gz
    ├── c7f2b1ed4aaef562e9afcaef2955baade92826be.nq.gz
    ├── c87c0de332674d8506fd4c6da3e4ea3a5ab98879.nq.gz
    ├── c97fbb66c1be4c871ba6062ccc3515bc5a2fae05.nq.gz
    ├── c9b0399eb9104a098bfa72675a71cd75b6fd2618.nq.gz
    ├── ca87516863d457808f2a444d8e009752cf1c22bd.nq.gz
    ├── cba1aec08c38930cdd4b030684fca364696967f8.nq.gz
    ├── ccd16e4b94ffe043678cfab06ba3b3575b52bf5e.nq.gz
    ├── ce69daf6ba96cf3d8352ed0a7035d28ea51e5eb2.nq.gz
    ├── cec536c2aef32fa128c9fc74713d879901865a6e.nq.gz
    ├── cf1ac4a9f9e90f380bf3fe51c09cea99503a26bf.nq.gz
    └── d008aa1e688791fe5ae94e39e9ed4419e26f02f7.nq.gz

9 directories, 200 files
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

[jaredpalmer/tsdx](https://github.com/jaredpalmer/tsdx)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
