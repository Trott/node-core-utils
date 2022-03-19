# Changelog

## [1.28.0](https://github.com/Trott/node-core-utils/compare/v1.31.1...v1.28.0) (2022-03-19)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 10 and 15.

### Features

* add ncu-ci cigtm <jobid> ([#454](https://github.com/Trott/node-core-utils/issues/454)) ([c1dfbd0](https://github.com/Trott/node-core-utils/commit/c1dfbd0f57feb62c813205e2ff748d7d7db7f048))
* allow citgm job comparison ([#455](https://github.com/Trott/node-core-utils/issues/455)) ([336dc7f](https://github.com/Trott/node-core-utils/commit/336dc7fe399ca082da0f02d6dcec769f7d1cb069))
* allow to fixup everything into first commit with fixupAll ([4ad4a58](https://github.com/Trott/node-core-utils/commit/4ad4a58a9471d3fd4e27e3b19bae979d91916cef))
* automate creation of the first LTS release ([#514](https://github.com/Trott/node-core-utils/issues/514)) ([53e68b4](https://github.com/Trott/node-core-utils/commit/53e68b4737c59fae88c740330770f8245bde774b))
* check Actions and handle doc-only changes ([855f1d4](https://github.com/Trott/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* check CI failures before land ([#422](https://github.com/Trott/node-core-utils/issues/422)) ([75abd3a](https://github.com/Trott/node-core-utils/commit/75abd3a22eca92a48ceb28532c7311de5e8ebe67))
* check commits after the last ci run ([#69](https://github.com/Trott/node-core-utils/issues/69)) ([72a2034](https://github.com/Trott/node-core-utils/commit/72a2034adecbeb2873ef7c4d10a7760b6d1cb3e4))
* check fast-track approvals ([#588](https://github.com/Trott/node-core-utils/issues/588)) ([d0215d6](https://github.com/Trott/node-core-utils/commit/d0215d6bdcaa7ec087992dbc29ebcae15e81dff5))
* **cli:** prompt user when landing PR with several commits ([#572](https://github.com/Trott/node-core-utils/issues/572)) ([89925c3](https://github.com/Trott/node-core-utils/commit/89925c306728ba8147413b0ad622e55a6dd5475e))
* enable parsing citgm-nobuild jobs ([#458](https://github.com/Trott/node-core-utils/issues/458)) ([d4b189b](https://github.com/Trott/node-core-utils/commit/d4b189b167951dd8ca50849b6f4548e8b63cf41a))
* **git-node:** add git-node status ([ebc8fb2](https://github.com/Trott/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))
* handle unknown commands ([#387](https://github.com/Trott/node-core-utils/issues/387)) ([4ea4dfa](https://github.com/Trott/node-core-utils/commit/4ea4dfad069d7cb6eccdea28f514a2b67e153508))
* handle unmarked DEP0XXX tags during landing and release ([#420](https://github.com/Trott/node-core-utils/issues/420)) ([08bc3fc](https://github.com/Trott/node-core-utils/commit/08bc3fc4ea74c879f4791f83a56d73a681351ff2))
* implement autorebase for PRs with multiple commits ([17ea885](https://github.com/Trott/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* **land:** avoid landing on the wrong default branch ([#586](https://github.com/Trott/node-core-utils/issues/586)) ([48d4641](https://github.com/Trott/node-core-utils/commit/48d4641ffa9034e37f8d7b7890c6c7c95e14f15d))
* make --checkCI optionable for git-node-land ([#528](https://github.com/Trott/node-core-utils/issues/528)) ([b0be3dd](https://github.com/Trott/node-core-utils/commit/b0be3dd365005236c596396026d8dce9378306a6))
* make lint check opt-in ([b567c1e](https://github.com/Trott/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* merge update-v8 in the project ([#235](https://github.com/Trott/node-core-utils/issues/235)) ([969987b](https://github.com/Trott/node-core-utils/commit/969987be85385336a89aa71e229dd2ed3f72635e))
* prepare ncu for new README format ([#561](https://github.com/Trott/node-core-utils/issues/561)) ([6898338](https://github.com/Trott/node-core-utils/commit/6898338653c6edea657fd7e9a36fb3890fead0e1))
* set error code in some failure cases ([#443](https://github.com/Trott/node-core-utils/issues/443)) ([56d4931](https://github.com/Trott/node-core-utils/commit/56d49317787cde0807fb1549c1f190b498e9aa74))
* spawn the user's editor to edit commit messages ([811de87](https://github.com/Trott/node-core-utils/commit/811de87206806246a98033c60c5db2557d56da12))
* suggest `gh pr` commands to finish landing ([#583](https://github.com/Trott/node-core-utils/issues/583)) ([25b452d](https://github.com/Trott/node-core-utils/commit/25b452d61c49cf723be5ea2ae3b927b3878ad902))
* support NCU_VERBOSITY=debug environment variable ([4f84166](https://github.com/Trott/node-core-utils/commit/4f841663818ace8721af1c18212f1f5928e5ce46))
* support system proxy ([#408](https://github.com/Trott/node-core-utils/issues/408)) ([c6697de](https://github.com/Trott/node-core-utils/commit/c6697de07e67b4c3cffbea392003020c772fed4d))
* update CI requirements for landing pull requests ([#533](https://github.com/Trott/node-core-utils/issues/533)) ([ad3c76b](https://github.com/Trott/node-core-utils/commit/ad3c76b3af9e934ff3c3c6b7e44419f518a7bc84))


### Bug Fixes

* accommodate case changes in README header ([e8ef932](https://github.com/Trott/node-core-utils/commit/e8ef9329bf3fa23a64915da6d2b3741df5ce6a70))
* add missing comma in release commit title ([#403](https://github.com/Trott/node-core-utils/issues/403)) ([78f0b96](https://github.com/Trott/node-core-utils/commit/78f0b9606b5ff715810e7f5ebc96de20f2d4ddd1))
* add missing new line in changelog ([#591](https://github.com/Trott/node-core-utils/issues/591)) ([e7a95a4](https://github.com/Trott/node-core-utils/commit/e7a95a4ec4b166b9311c673f1d4617da4a13d2bc))
* allow opt-out of Fixes/Refs metadata ([#474](https://github.com/Trott/node-core-utils/issues/474)) ([df5c572](https://github.com/Trott/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* allow pending dependabot checks in PR checker ([829c68d](https://github.com/Trott/node-core-utils/commit/829c68dbfed0b56a0f56534aa1ca6de5a6289b30))
* also exclude backport-open label from branch diff ([#440](https://github.com/Trott/node-core-utils/issues/440)) ([af4c72c](https://github.com/Trott/node-core-utils/commit/af4c72c4ed2d9f47e19f1902925973bea8ae10ab))
* check missing config in Session ctor ([#426](https://github.com/Trott/node-core-utils/issues/426)) ([7dc544d](https://github.com/Trott/node-core-utils/commit/7dc544d106098576ddd66c85c733069cfdf3a787))
* **cli-separator:** negative value on a long text ([#553](https://github.com/Trott/node-core-utils/issues/553)) ([3e8b07d](https://github.com/Trott/node-core-utils/commit/3e8b07decef270b127b7e2584051b950c686114d))
* comply with markdown style guidelines ([13d7b2d](https://github.com/Trott/node-core-utils/commit/13d7b2dbb174a73f3f32010ab4b7396143bd986e))
* correct for new execGitNode syntax ([#433](https://github.com/Trott/node-core-utils/issues/433)) ([6d82a73](https://github.com/Trott/node-core-utils/commit/6d82a730dfc95d8dde2176f002fa89157503b93c))
* default date for release ([#419](https://github.com/Trott/node-core-utils/issues/419)) ([ecc7f0c](https://github.com/Trott/node-core-utils/commit/ecc7f0c233a630da0937d8009afc6c39aa46c29d))
* **deps:** revert to node-fetch ([#595](https://github.com/Trott/node-core-utils/issues/595)) ([e475060](https://github.com/Trott/node-core-utils/commit/e4750602c59ae40c06835a86da92782ff2693ecf))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://github.com/Trott/node-core-utils/issues/581)) ([f28ec2d](https://github.com/Trott/node-core-utils/commit/f28ec2d50ce68965a87ed61182660763bd642543))
* enforce default for non-confirmation prompts ([#415](https://github.com/Trott/node-core-utils/issues/415)) ([3e0f03d](https://github.com/Trott/node-core-utils/commit/3e0f03d15b377a43f91ed59776477b0aa1a3d8dd))
* ensure node-test-commit job id in daily-master ([#460](https://github.com/Trott/node-core-utils/issues/460)) ([de35935](https://github.com/Trott/node-core-utils/commit/de3593557e19c036b2fdec297dbfe11b580e5399))
* fetch first 100 check suites in PR checker ([e98d72e](https://github.com/Trott/node-core-utils/commit/e98d72ef49d32d8b8a0605cce222cb8aaab8c128))
* fetch most recent 100 commits ([#520](https://github.com/Trott/node-core-utils/issues/520)) ([3c862d1](https://github.com/Trott/node-core-utils/commit/3c862d1d298917287339b0d2d558b522bb2255cf))
* fixupAll flag should take precedence over autorebase ([#593](https://github.com/Trott/node-core-utils/issues/593)) ([b62fe29](https://github.com/Trott/node-core-utils/commit/b62fe296a0de54eb55d80992cb2e437448b06732))
* git node metadata arg passing ([#500](https://github.com/Trott/node-core-utils/issues/500)) ([55c780e](https://github.com/Trott/node-core-utils/commit/55c780e52f03ecf38fc74177f8ee0d1e950ffd8d))
* handle citgm failures better ([#497](https://github.com/Trott/node-core-utils/issues/497)) ([a429893](https://github.com/Trott/node-core-utils/commit/a4298938f84382588db3101dcf611d89f6f0f1e9))
* https://github.com/nodejs/node-core-utils/issues/324 ([855f1d4](https://github.com/Trott/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* https://github.com/nodejs/node-core-utils/issues/466 ([4b32ebc](https://github.com/Trott/node-core-utils/commit/4b32ebc99cbf9b750252cda81ca818b6e3754bd4))
* https://github.com/nodejs/node/issues/29770 ([855f1d4](https://github.com/Trott/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* https://github.com/nodejs/node/issues/32335 ([855f1d4](https://github.com/Trott/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* landing when no Jenkins CI has been run for PR ([#451](https://github.com/Trott/node-core-utils/issues/451)) ([d63301e](https://github.com/Trott/node-core-utils/commit/d63301e9ea18543ab1d5d4be7ead09ddae3ce74c))
* lint during the landing process ([#435](https://github.com/Trott/node-core-utils/issues/435)) ([de6d1e2](https://github.com/Trott/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* LTS release commit should contain codename ([#401](https://github.com/Trott/node-core-utils/issues/401)) ([37f4cc6](https://github.com/Trott/node-core-utils/commit/37f4cc6a814f4667333fc59563527925d7b03b16))
* **pr-checker:** shouldn't fail on SKIPPED ([a578cd7](https://github.com/Trott/node-core-utils/commit/a578cd739b785cdb6ac6c4358dda73d22a7ac690))
* prepare for one last README change ([#578](https://github.com/Trott/node-core-utils/issues/578)) ([ef1edc7](https://github.com/Trott/node-core-utils/commit/ef1edc78504ad3b26bb1889685f206a9ce575768))
* prevent duplicate and self-refs ([#478](https://github.com/Trott/node-core-utils/issues/478)) ([95300fd](https://github.com/Trott/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* print full command in case of failure ([#456](https://github.com/Trott/node-core-utils/issues/456)) ([5fe936f](https://github.com/Trott/node-core-utils/commit/5fe936ff7239528c67c1ef564c563dca92eec05d))
* properly handle failure to start CI ([48c306b](https://github.com/Trott/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* repo/path mismatch in v8 update ([#465](https://github.com/Trott/node-core-utils/issues/465)) ([57b7df8](https://github.com/Trott/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
* return value for validateLint ([#482](https://github.com/Trott/node-core-utils/issues/482)) ([e379e9f](https://github.com/Trott/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* spacing in warnForWrongBranch() ([#448](https://github.com/Trott/node-core-utils/issues/448)) ([d8c024d](https://github.com/Trott/node-core-utils/commit/d8c024d3fdbd0278cc56f746e527cb43fc8eaa03))
* throw on missing info during release prep ([#519](https://github.com/Trott/node-core-utils/issues/519)) ([223d075](https://github.com/Trott/node-core-utils/commit/223d075fc91f421c7f1201b691e9197767b8d465))
* undefined failures & JSON error ([2c0cf83](https://github.com/Trott/node-core-utils/commit/2c0cf834232867e0d0a40cf988ad111dafe17e25))
* update detection of changelog links ([#573](https://github.com/Trott/node-core-utils/issues/573)) ([44c6fc8](https://github.com/Trott/node-core-utils/commit/44c6fc878178af17def7b0e047fc5b155796f927))
* update detection of changelog links ([#587](https://github.com/Trott/node-core-utils/issues/587)) ([4cd1beb](https://github.com/Trott/node-core-utils/commit/4cd1beb07a0a9d44ca1d8dd9708a29929d566956))
* update detection of changelog links (take 2) ([#575](https://github.com/Trott/node-core-utils/issues/575)) ([e66ba17](https://github.com/Trott/node-core-utils/commit/e66ba171e81d77abcf38adc9f3bca966523e7b19))
* update for recent changelog format change ([#576](https://github.com/Trott/node-core-utils/issues/576)) ([8f1fa9c](https://github.com/Trott/node-core-utils/commit/8f1fa9c47f93c40ce7b80a375940bffcd6eabdf2))
* update proxy-agent to 5.0.0 ([#570](https://github.com/Trott/node-core-utils/issues/570)) ([3091f99](https://github.com/Trott/node-core-utils/commit/3091f99cca1683f29cf5cd4358738338fe013aba))
* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://github.com/Trott/node-core-utils/issues/565)) ([96d46ab](https://github.com/Trott/node-core-utils/commit/96d46ab0322aeea9fbf6dcd7121e8a87505e568c))
* **update-v8:** force-add all files after cloning V8 ([#549](https://github.com/Trott/node-core-utils/issues/549)) ([f23ff61](https://github.com/Trott/node-core-utils/commit/f23ff6166bdd774090269352ca9da56132c3d574))
* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://github.com/Trott/node-core-utils/issues/567)) ([8ccf184](https://github.com/Trott/node-core-utils/commit/8ccf184773f660cc1765f26af3103870729cb8b2))
* use 12 characters for commit SHAs ([#372](https://github.com/Trott/node-core-utils/issues/372)) ([a9c0676](https://github.com/Trott/node-core-utils/commit/a9c0676d0f64df5c8e86d7287f69381dc64049f2))
* use COMMIT_EDITMSG file name to edit commits ([2a23e37](https://github.com/Trott/node-core-utils/commit/2a23e3734dd3ac2326fee43ac0221924c36d9bf9))
* use git apply not system apply in v8 backport ([#432](https://github.com/Trott/node-core-utils/issues/432)) ([65fb311](https://github.com/Trott/node-core-utils/commit/65fb311a0fac380f4c74012d703a75ebe22f6508))
* use plaintext formatting in release commit ([#417](https://github.com/Trott/node-core-utils/issues/417)) ([8e6ac47](https://github.com/Trott/node-core-utils/commit/8e6ac47e0256f11bdc21262b644285299b8ff18a))
* **v8:** correct order of ternary ([#513](https://github.com/Trott/node-core-utils/issues/513)) ([6dab341](https://github.com/Trott/node-core-utils/commit/6dab341314966dea25d277e2bd79ef8d58b4a71b))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://github.com/Trott/node-core-utils/issues/471)) ([746e5e5](https://github.com/Trott/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* **v8:** use V8's main branch ([#555](https://github.com/Trott/node-core-utils/issues/555)) ([241055b](https://github.com/Trott/node-core-utils/commit/241055b22c89b0b89efa9aebb06ea41039eece9d))
* validate ncu-ci args ([#411](https://github.com/Trott/node-core-utils/issues/411)) ([dfe7adf](https://github.com/Trott/node-core-utils/commit/dfe7adf18e4bbeadb479482c5f36fe344a78292b))
* warn on whitespace during landing ([#438](https://github.com/Trott/node-core-utils/issues/438)) ([ae3aeb9](https://github.com/Trott/node-core-utils/commit/ae3aeb93f8368779b8b3a95cbd82841f7feae2ab))
* **wpt:** download files as buffer instead of text ([#535](https://github.com/Trott/node-core-utils/issues/535)) ([d6fad2a](https://github.com/Trott/node-core-utils/commit/d6fad2a20955a3b7a7eb1626289146609298dabb))
* **wpt:** order version keys alphabetically ([#536](https://github.com/Trott/node-core-utils/issues/536)) ([308982b](https://github.com/Trott/node-core-utils/commit/308982b9cd69c781e4fbd3eb8ed5e68b137a28ca))
* write file to the current folder ([#434](https://github.com/Trott/node-core-utils/issues/434)) ([5974797](https://github.com/Trott/node-core-utils/commit/59747973f681cca4dc4eb60d617638b0c194c137))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([dafcdd6](https://github.com/Trott/node-core-utils/commit/dafcdd69fad7e80ca3dea4c6387afe9d504c02c4))
* release 1.28.0 ([0044734](https://github.com/Trott/node-core-utils/commit/00447343615a111a18864e9c7192463b0a38f653))

### [1.31.1](https://www.github.com/nodejs/node-core-utils/compare/v1.31.0...v1.31.1) (2022-03-17)


### Bug Fixes

* comply with markdown style guidelines ([13d7b2d](https://www.github.com/nodejs/node-core-utils/commit/13d7b2dbb174a73f3f32010ab4b7396143bd986e))

## [1.31.0](https://www.github.com/nodejs/node-core-utils/compare/v1.30.1...v1.31.0) (2021-12-21)


### Features

* check fast-track approvals ([#588](https://www.github.com/nodejs/node-core-utils/issues/588)) ([d0215d6](https://www.github.com/nodejs/node-core-utils/commit/d0215d6bdcaa7ec087992dbc29ebcae15e81dff5))


### Bug Fixes

* allow pending dependabot checks in PR checker ([829c68d](https://www.github.com/nodejs/node-core-utils/commit/829c68dbfed0b56a0f56534aa1ca6de5a6289b30))
* fetch first 100 check suites in PR checker ([e98d72e](https://www.github.com/nodejs/node-core-utils/commit/e98d72ef49d32d8b8a0605cce222cb8aaab8c128))

### [1.30.1](https://www.github.com/nodejs/node-core-utils/compare/v1.30.0...v1.30.1) (2021-11-17)


### Bug Fixes

* **deps:** revert to node-fetch ([#595](https://www.github.com/nodejs/node-core-utils/issues/595)) ([e475060](https://www.github.com/nodejs/node-core-utils/commit/e4750602c59ae40c06835a86da92782ff2693ecf))
* fixupAll flag should take precedence over autorebase ([#593](https://www.github.com/nodejs/node-core-utils/issues/593)) ([b62fe29](https://www.github.com/nodejs/node-core-utils/commit/b62fe296a0de54eb55d80992cb2e437448b06732))

## [1.30.0](https://www.github.com/nodejs/node-core-utils/compare/v1.29.1...v1.30.0) (2021-11-08)


### Features

* **land:** avoid landing on the wrong default branch ([#586](https://www.github.com/nodejs/node-core-utils/issues/586)) ([48d4641](https://www.github.com/nodejs/node-core-utils/commit/48d4641ffa9034e37f8d7b7890c6c7c95e14f15d))
* spawn the user's editor to edit commit messages ([811de87](https://www.github.com/nodejs/node-core-utils/commit/811de87206806246a98033c60c5db2557d56da12))
* suggest `gh pr` commands to finish landing ([#583](https://www.github.com/nodejs/node-core-utils/issues/583)) ([25b452d](https://www.github.com/nodejs/node-core-utils/commit/25b452d61c49cf723be5ea2ae3b927b3878ad902))


### Bug Fixes

* add missing new line in changelog ([#591](https://www.github.com/nodejs/node-core-utils/issues/591)) ([e7a95a4](https://www.github.com/nodejs/node-core-utils/commit/e7a95a4ec4b166b9311c673f1d4617da4a13d2bc))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://www.github.com/nodejs/node-core-utils/issues/581)) ([f28ec2d](https://www.github.com/nodejs/node-core-utils/commit/f28ec2d50ce68965a87ed61182660763bd642543))
* update detection of changelog links ([#587](https://www.github.com/nodejs/node-core-utils/issues/587)) ([4cd1beb](https://www.github.com/nodejs/node-core-utils/commit/4cd1beb07a0a9d44ca1d8dd9708a29929d566956))
* use COMMIT_EDITMSG file name to edit commits ([2a23e37](https://www.github.com/nodejs/node-core-utils/commit/2a23e3734dd3ac2326fee43ac0221924c36d9bf9))

### [1.29.1](https://www.github.com/nodejs/node-core-utils/compare/v1.29.0...v1.29.1) (2021-10-31)


### Bug Fixes

* prepare for one last README change ([#578](https://www.github.com/nodejs/node-core-utils/issues/578)) ([ef1edc7](https://www.github.com/nodejs/node-core-utils/commit/ef1edc78504ad3b26bb1889685f206a9ce575768))

## [1.29.0](https://www.github.com/nodejs/node-core-utils/compare/v1.28.2...v1.29.0) (2021-10-28)


### Features

* **cli:** prompt user when landing PR with several commits ([#572](https://www.github.com/nodejs/node-core-utils/issues/572)) ([89925c3](https://www.github.com/nodejs/node-core-utils/commit/89925c306728ba8147413b0ad622e55a6dd5475e))


### Bug Fixes

* update detection of changelog links ([#573](https://www.github.com/nodejs/node-core-utils/issues/573)) ([44c6fc8](https://www.github.com/nodejs/node-core-utils/commit/44c6fc878178af17def7b0e047fc5b155796f927))
* update detection of changelog links (take 2) ([#575](https://www.github.com/nodejs/node-core-utils/issues/575)) ([e66ba17](https://www.github.com/nodejs/node-core-utils/commit/e66ba171e81d77abcf38adc9f3bca966523e7b19))
* update for recent changelog format change ([#576](https://www.github.com/nodejs/node-core-utils/issues/576)) ([8f1fa9c](https://www.github.com/nodejs/node-core-utils/commit/8f1fa9c47f93c40ce7b80a375940bffcd6eabdf2))
* update proxy-agent to 5.0.0 ([#570](https://www.github.com/nodejs/node-core-utils/issues/570)) ([3091f99](https://www.github.com/nodejs/node-core-utils/commit/3091f99cca1683f29cf5cd4358738338fe013aba))

### [1.28.2](https://www.github.com/nodejs/node-core-utils/compare/v1.28.1...v1.28.2) (2021-10-04)


### Bug Fixes

* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://www.github.com/nodejs/node-core-utils/issues/567)) ([8ccf184](https://www.github.com/nodejs/node-core-utils/commit/8ccf184773f660cc1765f26af3103870729cb8b2))

### [1.28.1](https://www.github.com/nodejs/node-core-utils/compare/v1.28.0...v1.28.1) (2021-09-25)


### Bug Fixes

* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://www.github.com/nodejs/node-core-utils/issues/565)) ([96d46ab](https://www.github.com/nodejs/node-core-utils/commit/96d46ab0322aeea9fbf6dcd7121e8a87505e568c))

## [1.28.0](https://www.github.com/nodejs/node-core-utils/compare/v1.27.2...v1.28.0) (2021-09-20)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 10 and 15.

### Features

* prepare ncu for new README format ([#561](https://www.github.com/nodejs/node-core-utils/issues/561)) ([6898338](https://www.github.com/nodejs/node-core-utils/commit/6898338653c6edea657fd7e9a36fb3890fead0e1))


### Bug Fixes

* **cli-separator:** negative value on a long text ([#553](https://www.github.com/nodejs/node-core-utils/issues/553)) ([3e8b07d](https://www.github.com/nodejs/node-core-utils/commit/3e8b07decef270b127b7e2584051b950c686114d))
* **v8:** use V8's main branch ([#555](https://www.github.com/nodejs/node-core-utils/issues/555)) ([241055b](https://www.github.com/nodejs/node-core-utils/commit/241055b22c89b0b89efa9aebb06ea41039eece9d))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([dafcdd6](https://www.github.com/nodejs/node-core-utils/commit/dafcdd69fad7e80ca3dea4c6387afe9d504c02c4))
* release 1.28.0 ([0044734](https://www.github.com/nodejs/node-core-utils/commit/00447343615a111a18864e9c7192463b0a38f653))

### [1.27.2](https://www.github.com/nodejs/node-core-utils/compare/v1.27.1...v1.27.2) (2021-07-03)


### Bug Fixes

* **update-v8:** force-add all files after cloning V8 ([#549](https://www.github.com/nodejs/node-core-utils/issues/549)) ([f23ff61](https://www.github.com/nodejs/node-core-utils/commit/f23ff6166bdd774090269352ca9da56132c3d574))

### [1.27.1](https://www.github.com/nodejs/node-core-utils/compare/v1.27.0...v1.27.1) (2021-06-10)


### Bug Fixes

* **pr-checker:** shouldn't fail on SKIPPED ([a578cd7](https://www.github.com/nodejs/node-core-utils/commit/a578cd739b785cdb6ac6c4358dda73d22a7ac690))

## [1.27.0](https://www.github.com/nodejs/node-core-utils/compare/v1.26.0...v1.27.0) (2021-02-26)


### Features

* update CI requirements for landing pull requests ([#533](https://www.github.com/nodejs/node-core-utils/issues/533)) ([ad3c76b](https://www.github.com/nodejs/node-core-utils/commit/ad3c76b3af9e934ff3c3c6b7e44419f518a7bc84))


### Bug Fixes

* **wpt:** download files as buffer instead of text ([#535](https://www.github.com/nodejs/node-core-utils/issues/535)) ([d6fad2a](https://www.github.com/nodejs/node-core-utils/commit/d6fad2a20955a3b7a7eb1626289146609298dabb))
* **wpt:** order version keys alphabetically ([#536](https://www.github.com/nodejs/node-core-utils/issues/536)) ([308982b](https://www.github.com/nodejs/node-core-utils/commit/308982b9cd69c781e4fbd3eb8ed5e68b137a28ca))

## [1.26.0](https://www.github.com/nodejs/node-core-utils/compare/v1.25.0...v1.26.0) (2021-02-08)


### Features

* automate creation of the first LTS release ([#514](https://www.github.com/nodejs/node-core-utils/issues/514)) ([53e68b4](https://www.github.com/nodejs/node-core-utils/commit/53e68b4737c59fae88c740330770f8245bde774b))
* make --checkCI optionable for git-node-land ([#528](https://www.github.com/nodejs/node-core-utils/issues/528)) ([b0be3dd](https://www.github.com/nodejs/node-core-utils/commit/b0be3dd365005236c596396026d8dce9378306a6))


### Bug Fixes

* accommodate case changes in README header ([e8ef932](https://www.github.com/nodejs/node-core-utils/commit/e8ef9329bf3fa23a64915da6d2b3741df5ce6a70))
* fetch most recent 100 commits ([#520](https://www.github.com/nodejs/node-core-utils/issues/520)) ([3c862d1](https://www.github.com/nodejs/node-core-utils/commit/3c862d1d298917287339b0d2d558b522bb2255cf))
* throw on missing info during release prep ([#519](https://www.github.com/nodejs/node-core-utils/issues/519)) ([223d075](https://www.github.com/nodejs/node-core-utils/commit/223d075fc91f421c7f1201b691e9197767b8d465))
* **v8:** correct order of ternary ([#513](https://www.github.com/nodejs/node-core-utils/issues/513)) ([6dab341](https://www.github.com/nodejs/node-core-utils/commit/6dab341314966dea25d277e2bd79ef8d58b4a71b))
* undefined failures & JSON error ([2c0cf83](https://www.github.com/nodejs/node-core-utils/commit/2c0cf834232867e0d0a40cf988ad111dafe17e25))

## [1.25.0](https://www.github.com/nodejs/node-core-utils/compare/v1.24.0...v1.25.0) (2020-09-29)


### Features

* allow to fixup everything into first commit with fixupAll ([4ad4a58](https://www.github.com/nodejs/node-core-utils/commit/4ad4a58a9471d3fd4e27e3b19bae979d91916cef))
* support NCU_VERBOSITY=debug environment variable ([4f84166](https://www.github.com/nodejs/node-core-utils/commit/4f841663818ace8721af1c18212f1f5928e5ce46))


### Bug Fixes

* git node metadata arg passing ([#500](https://www.github.com/nodejs/node-core-utils/issues/500)) ([55c780e](https://www.github.com/nodejs/node-core-utils/commit/55c780e52f03ecf38fc74177f8ee0d1e950ffd8d))
* handle citgm failures better ([#497](https://www.github.com/nodejs/node-core-utils/issues/497)) ([a429893](https://www.github.com/nodejs/node-core-utils/commit/a4298938f84382588db3101dcf611d89f6f0f1e9))

## [1.24.0](https://www.github.com/nodejs/node-core-utils/compare/v1.23.0...v1.24.0) (2020-08-21)


### Features

* check Actions and handle doc-only changes ([855f1d4](https://www.github.com/nodejs/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* implement autorebase for PRs with multiple commits ([17ea885](https://www.github.com/nodejs/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* make lint check opt-in ([b567c1e](https://www.github.com/nodejs/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* **git-node:** add git-node status ([ebc8fb2](https://www.github.com/nodejs/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))


### Bug Fixes

* allow opt-out of Fixes/Refs metadata ([#474](https://www.github.com/nodejs/node-core-utils/issues/474)) ([df5c572](https://www.github.com/nodejs/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* lint during the landing process ([#435](https://www.github.com/nodejs/node-core-utils/issues/435)) ([de6d1e2](https://www.github.com/nodejs/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* prevent duplicate and self-refs ([#478](https://www.github.com/nodejs/node-core-utils/issues/478)) ([95300fd](https://www.github.com/nodejs/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* properly handle failure to start CI ([48c306b](https://www.github.com/nodejs/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* return value for validateLint ([#482](https://www.github.com/nodejs/node-core-utils/issues/482)) ([e379e9f](https://www.github.com/nodejs/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://www.github.com/nodejs/node-core-utils/issues/471)) ([746e5e5](https://www.github.com/nodejs/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* repo/path mismatch in v8 update ([#465](https://www.github.com/nodejs/node-core-utils/issues/465)) ([57b7df8](https://www.github.com/nodejs/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
