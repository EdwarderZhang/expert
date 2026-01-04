# Changelog

## [0.1.0](https://github.com/EdwarderZhang/expert/compare/v0.1.0...v0.1.0) (2026-01-04)


### ⚠ BREAKING CHANGES

* add CLI flag handling ([#185](https://github.com/EdwarderZhang/expert/issues/185))

### Features

* add CLI flag handling ([#185](https://github.com/EdwarderZhang/expert/issues/185)) ([ba3c79b](https://github.com/EdwarderZhang/expert/commit/ba3c79b44c32cb58e34fcf9f98522e290845f947))
* epmdless clustering ([#205](https://github.com/EdwarderZhang/expert/issues/205)) ([e7fedfb](https://github.com/EdwarderZhang/expert/commit/e7fedfb7b3f1ccad764519095f1a0ffda13fbb6f))
* epmdless deployments ([#167](https://github.com/EdwarderZhang/expert/issues/167)) ([9a9307e](https://github.com/EdwarderZhang/expert/commit/9a9307ececd3ebc43004b2612a95e6930bbe0952))
* on the fly engine builds ([#24](https://github.com/EdwarderZhang/expert/issues/24)) ([86411a8](https://github.com/EdwarderZhang/expert/commit/86411a85e4b7988de19ba1e270bc8dfed0518044))


### Bug Fixes

* add lsp logging when failing to find an elixir executable ([#169](https://github.com/EdwarderZhang/expert/issues/169)) ([5299024](https://github.com/EdwarderZhang/expert/commit/5299024a0058bd5e2b245ee5f62c5d47fb566f0a))
* better handling of native&lt;-&gt;lsp conversions ([#34](https://github.com/EdwarderZhang/expert/issues/34)) ([024a773](https://github.com/EdwarderZhang/expert/commit/024a773f9c85e156b711b5d5ac61d47fda399a86))
* bring back completions for things defined in test files ([#32](https://github.com/EdwarderZhang/expert/issues/32)) ([5c59c0a](https://github.com/EdwarderZhang/expert/commit/5c59c0a5872ae57c38bcbfdc84b4228114cfaaae))
* clamp start_char for comletion prefix ([#239](https://github.com/EdwarderZhang/expert/issues/239)) ([bb933fc](https://github.com/EdwarderZhang/expert/commit/bb933fcea61e51b3b8d7e57939f5b0dc1a4647fa))
* Crash when typing english ([#742](https://github.com/EdwarderZhang/expert/issues/742)) ([d2eef17](https://github.com/EdwarderZhang/expert/commit/d2eef177c63f6215cd8fcfecf6498286351c6184)), closes [#741](https://github.com/EdwarderZhang/expert/issues/741)
* Current module not identified in defimpl ([#665](https://github.com/EdwarderZhang/expert/issues/665)) ([21755d2](https://github.com/EdwarderZhang/expert/commit/21755d2eb8d3246623b5e9ab536ccc4c75a639e8))
* disable shell sessions when fetching the PATH ([#177](https://github.com/EdwarderZhang/expert/issues/177)) ([f1adb72](https://github.com/EdwarderZhang/expert/commit/f1adb729d2d3942770f903bebeb3e31ba2dc8bf2))
* do not clamp character recvd from client ([#123](https://github.com/EdwarderZhang/expert/issues/123)) ([54c4d13](https://github.com/EdwarderZhang/expert/commit/54c4d13c866f47bfe9419ca2f6ec98d3be426779))
* don't convert to_lsp twice in server specific messages ([#190](https://github.com/EdwarderZhang/expert/issues/190)) ([66878ef](https://github.com/EdwarderZhang/expert/commit/66878ef5e831bab08267823efeda1fc944211e9b))
* don't sometimes hang ([fcdb73b](https://github.com/EdwarderZhang/expert/commit/fcdb73b18ea818c3b3b69f714ab944cd7923b18d))
* Edge case for module loading ([#738](https://github.com/EdwarderZhang/expert/issues/738)) ([ab04d6c](https://github.com/EdwarderZhang/expert/commit/ab04d6c88a62dc28dbc203f677c595077b10781d))
* elixir path discovery ([#248](https://github.com/EdwarderZhang/expert/issues/248)) ([9f1b681](https://github.com/EdwarderZhang/expert/commit/9f1b6810bf74029cd58d5fc6e217f8d7aee8ef7d))
* **engine:** handle failing build script ([#188](https://github.com/EdwarderZhang/expert/issues/188)) ([5319a41](https://github.com/EdwarderZhang/expert/commit/5319a418744c1a06662b9a41ca8e5e0e17f7632b))
* Erlang function calls in pipes were incorrectly formatted ([#476](https://github.com/EdwarderZhang/expert/issues/476)) ([c332e4e](https://github.com/EdwarderZhang/expert/commit/c332e4e051efe4ad4cd4e31c4aa4735855012e77)), closes [#475](https://github.com/EdwarderZhang/expert/issues/475)
* Exclude expert dependencies from completions based on project dependencies ([23d0a89](https://github.com/EdwarderZhang/expert/commit/23d0a89aa5476157e97cdfdc1e71d9f79bfd9e6f))
* fix release-all command ([6289ac0](https://github.com/EdwarderZhang/expert/commit/6289ac0e4a355ba376bbb7d5f66ef3f41b4817c8))
* fixup namespacing and packaging ([#29](https://github.com/EdwarderZhang/expert/issues/29)) ([adb1b53](https://github.com/EdwarderZhang/expert/commit/adb1b53efe1a3cbc1672aad329708029769b24ed))
* formatting format incorrectly when contain special character ([#252](https://github.com/EdwarderZhang/expert/issues/252)) ([d2c0799](https://github.com/EdwarderZhang/expert/commit/d2c0799f849f265d81d23ff3eeecc1b26bb85452))
* Function definition extractor chokes on macro functions ([#682](https://github.com/EdwarderZhang/expert/issues/682)) ([41b8fbb](https://github.com/EdwarderZhang/expert/commit/41b8fbb38923306092269d7ec22248008f28c9de)), closes [#680](https://github.com/EdwarderZhang/expert/issues/680)
* give proper argument to `TaskQueue.add/2` in Server.handle_message ([#791](https://github.com/EdwarderZhang/expert/issues/791)) ([9bdfe4f](https://github.com/EdwarderZhang/expert/commit/9bdfe4f48defc4b5ee92d392333808c3b428dc23))
* handle string ids in requests ([#120](https://github.com/EdwarderZhang/expert/issues/120)) ([fcdb73b](https://github.com/EdwarderZhang/expert/commit/fcdb73b18ea818c3b3b69f714ab944cd7923b18d))
* include erlang source files when packaging engine ([7fea806](https://github.com/EdwarderZhang/expert/commit/7fea806783e2b0b470d75ea80675374d0debb385))
* Invalid reads for requests that contain multi-byte characters ([#661](https://github.com/EdwarderZhang/expert/issues/661)) ([9f8d4be](https://github.com/EdwarderZhang/expert/commit/9f8d4be1d77d89d6f039462564d11cc16e480bf5))
* let the system figure out the elixir version for the project ([#162](https://github.com/EdwarderZhang/expert/issues/162)) ([b1245d2](https://github.com/EdwarderZhang/expert/commit/b1245d26c3498045f634260a51c0cef81c7d653a))
* make sure asdf shims are in the PATH ([#87](https://github.com/EdwarderZhang/expert/issues/87)) ([ad14175](https://github.com/EdwarderZhang/expert/commit/ad141759eda036b93312c5d675c0d7d02182a95f))
* Module suggestion was incorrect for files with multiple periods ([#705](https://github.com/EdwarderZhang/expert/issues/705)) ([7f01fba](https://github.com/EdwarderZhang/expert/commit/7f01fbad12872d037580ba95a8cbbb1d8e1e80a5)), closes [#703](https://github.com/EdwarderZhang/expert/issues/703)
* nil.__struct__/0 is undefined when receiving shutdown ([#250](https://github.com/EdwarderZhang/expert/issues/250)) ([96704fa](https://github.com/EdwarderZhang/expert/commit/96704faf06f881e94559a354b2e0837cd950b79a))
* **nix:** use eval release command ([#199](https://github.com/EdwarderZhang/expert/issues/199)) ([1d832f8](https://github.com/EdwarderZhang/expert/commit/1d832f8f6949dbd9a5cf06e58ffb4c6440edb410))
* Non-string test names crash exunit indexer ([#676](https://github.com/EdwarderZhang/expert/issues/676)) ([ae0e48a](https://github.com/EdwarderZhang/expert/commit/ae0e48ac0ca1d8b5ce106e198fcd97926783a718)), closes [#675](https://github.com/EdwarderZhang/expert/issues/675)
* properly log when engine fails to initialize ([#244](https://github.com/EdwarderZhang/expert/issues/244)) ([221081b](https://github.com/EdwarderZhang/expert/commit/221081bf888651693c7aa584d7ada8bf63cbeb63))
* properly set the mix env when building expert ([279fb40](https://github.com/EdwarderZhang/expert/commit/279fb40d1012cfa834274378bf7825f72f1c243d))
* remove erts from extra_applications ([#202](https://github.com/EdwarderZhang/expert/issues/202)) ([70730c2](https://github.com/EdwarderZhang/expert/commit/70730c262070868efa6aa427a2b34b855a2f82df))
* remove escape sequences from PATH in fish ([#237](https://github.com/EdwarderZhang/expert/issues/237)) ([ceb72e7](https://github.com/EdwarderZhang/expert/commit/ceb72e70d45a942d0bb75a57274497199de3ed5f))
* Resolve doesn't recognize zero-arg defs as functions ([#606](https://github.com/EdwarderZhang/expert/issues/606)) ([28ac14d](https://github.com/EdwarderZhang/expert/commit/28ac14dcecdcbb84a2f3c33d47d545cf85d1f84e)), closes [#604](https://github.com/EdwarderZhang/expert/issues/604)
* revert "feat: epmdless deployments ([#167](https://github.com/EdwarderZhang/expert/issues/167))" ([#180](https://github.com/EdwarderZhang/expert/issues/180)) ([989bfaf](https://github.com/EdwarderZhang/expert/commit/989bfaf124145a1f4440e414d4e61b1c69792cb4))
* revert dev server ([#48](https://github.com/EdwarderZhang/expert/issues/48)) ([ca4d9c6](https://github.com/EdwarderZhang/expert/commit/ca4d9c6a8d01c26e8ed34add3a8f0bc86db2fb9d))
* stop sending genlsp datastructures to engine ([#31](https://github.com/EdwarderZhang/expert/issues/31)) ([ec153eb](https://github.com/EdwarderZhang/expert/commit/ec153eb2e52b2b84e1db1a39d5ec1b26869d0401))
* Stutter when completing inside string interpolations ([#464](https://github.com/EdwarderZhang/expert/issues/464)) ([c78221a](https://github.com/EdwarderZhang/expert/commit/c78221a9f0fe5aa3808a503d5ebce8dad8bd2241)), closes [#462](https://github.com/EdwarderZhang/expert/issues/462)
* support Fish shell's space-separated PATH format ([#172](https://github.com/EdwarderZhang/expert/issues/172)) ([42c0425](https://github.com/EdwarderZhang/expert/commit/42c0425daa4dd721b36dce6a4144d432f08bd30c))
* trim any quotes wrapping PATH when elixir is managed by mise ([#82](https://github.com/EdwarderZhang/expert/issues/82)) ([1200234](https://github.com/EdwarderZhang/expert/commit/120023453de71808cbd69c6dc8d7a85df3584c86))
* trim PATH returned by shell ([#213](https://github.com/EdwarderZhang/expert/issues/213)) ([02a3e80](https://github.com/EdwarderZhang/expert/commit/02a3e8002abd45f4bb86f622b4dc24cc09a25ade))
* use correct build directory when namespacing expert ([c70ef83](https://github.com/EdwarderZhang/expert/commit/c70ef83ef87ea8a68c2b1a9e725774ea0a38e815))
* use dynamic registrations and start project node asynchronously ([#30](https://github.com/EdwarderZhang/expert/issues/30)) ([7d6defd](https://github.com/EdwarderZhang/expert/commit/7d6defdb5ae007182dd422e92514e4a11f7121d2))
* use project directory when building engine ([#203](https://github.com/EdwarderZhang/expert/issues/203)) ([8e7a066](https://github.com/EdwarderZhang/expert/commit/8e7a066d7c8b2e3f2962406d22dde34abacbc3e8))
* utf8_prefix should take into account empty lines ([#164](https://github.com/EdwarderZhang/expert/issues/164)) ([5d45a04](https://github.com/EdwarderZhang/expert/commit/5d45a042460658a834c336c568daf5845936372a))


### Miscellaneous Chores

* release as 0.1.0 ([0f21fbb](https://github.com/EdwarderZhang/expert/commit/0f21fbb9fc8ac7b9c7d7105b26981f7d0a06a32b))

## Unreleased
No changes yet
