# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.1.1](https://github.com/RobBrazier/Laravel_Piwik/compare/4.1.0...4.1.1)

### Merged

- Migrate to GitHub actions and use SonarQube + remove 7.3 from built php versions as it's deprecated [`#102`](https://github.com/RobBrazier/Laravel_Piwik/pull/102)

## [4.1.0](https://github.com/RobBrazier/Laravel_Piwik/compare/4.0.0...4.1.0) - 2021-09-10

### Commits

- Upgrade dependencies and fix linting issues [`c99f6cb`](https://github.com/RobBrazier/Laravel_Piwik/commit/c99f6cb166898e0f415ffb4605213f5d93fc99d5)
- - Added new AuthToken function for Matomos V4 api, which is allowing multiple auth tokens per user. [`a101e27`](https://github.com/RobBrazier/Laravel_Piwik/commit/a101e276331ccaf9dd683c703f60e9d02203e05b)
- fix publishing pipeline [`ff1c817`](https://github.com/RobBrazier/Laravel_Piwik/commit/ff1c8176c5b2539ed41d11e9fa095b7ad1234e0a)
- fix integration tests [`b569cf6`](https://github.com/RobBrazier/Laravel_Piwik/commit/b569cf6a7384f5254744a0599c8785e8bd1dbe92)

## [4.0.0](https://github.com/RobBrazier/Laravel_Piwik/compare/3.3.1...4.0.0) - 2020-09-21

### Commits

- Remove checks for unsupported PHP versions (5.6, 7.0 and 7.1) [`03b54a7`](https://github.com/RobBrazier/Laravel_Piwik/commit/03b54a73cfe8aac0b902f9d8c1dfc9a29aae6c3a)
- Add extra to composer.json for Laravel 8 support [`8b6b52d`](https://github.com/RobBrazier/Laravel_Piwik/commit/8b6b52d968aa329c2c00dbd08946ebf063bcc2ac)
- Add php 7.4 checks [`5882f18`](https://github.com/RobBrazier/Laravel_Piwik/commit/5882f187b9a7a1c2bed1012d7f8fbba6fa80bf3f)
- Add laravel 7 and 8 CI checks [`2a349b0`](https://github.com/RobBrazier/Laravel_Piwik/commit/2a349b0345e63247924b86e998093572b6d88343)
- guzzle7 [`136ce58`](https://github.com/RobBrazier/Laravel_Piwik/commit/136ce58729029f6a7d3ebb328508c9b02075e08a)

## [3.3.1](https://github.com/RobBrazier/Laravel_Piwik/compare/3.3.0...3.3.1) - 2019-10-01

### Commits

- use Illuminate\Support\Arr instead of helper methods [`2e98e25`](https://github.com/RobBrazier/Laravel_Piwik/commit/2e98e25b344394efe3dd77979572a74adb9628ec)
- add generated api docs index.html [`ba4836c`](https://github.com/RobBrazier/Laravel_Piwik/commit/ba4836c91c727c6a16e0edf75436915911652593)
- add phpdoc block to getUsersManager() in Piwik.php [`2ea7f45`](https://github.com/RobBrazier/Laravel_Piwik/commit/2ea7f4546c2bbea9943fbf934ee2d1c19eb130f2)
- update versions [`e6d97cf`](https://github.com/RobBrazier/Laravel_Piwik/commit/e6d97cfa366d70c52f44229c8aee514d4b1748d6)
- update versions in README.md [`a4f394d`](https://github.com/RobBrazier/Laravel_Piwik/commit/a4f394da6b9e7fffb02a87594c70dbe6a7eab546)
- fix missed array_dot -&gt; Arr::dot change [`e952c2e`](https://github.com/RobBrazier/Laravel_Piwik/commit/e952c2e7e7eafc8101fc4d640db210eac8dcaafa)

## [3.3.0](https://github.com/RobBrazier/Laravel_Piwik/compare/3.2.0...3.3.0) - 2019-08-24

### Merged

- Complete Semaphore CI v2 configuration [`#88`](https://github.com/RobBrazier/Laravel_Piwik/pull/88)

### Commits

- add unit tests and phpdocs to UsersManagerModule [`f98c884`](https://github.com/RobBrazier/Laravel_Piwik/commit/f98c8848e6e991cf3cd252108e017607cb487cab)
- added usermanager [`e3c116e`](https://github.com/RobBrazier/Laravel_Piwik/commit/e3c116ec845d997044d54048f23cb8a35f33556c)
- reorder publish steps [`b8946f5`](https://github.com/RobBrazier/Laravel_Piwik/commit/b8946f58d264b01e3734012e469720b06e79d56c)
- add github release script [`d9d9765`](https://github.com/RobBrazier/Laravel_Piwik/commit/d9d976554d86456defc29cc323860d92bd80b62f)
- fix some codeclimate issues and skip gh-pages branch [`b28a423`](https://github.com/RobBrazier/Laravel_Piwik/commit/b28a4237ddc01430421dfdcc62c4fc817f6091cb)
- Update README.md [`e4625ff`](https://github.com/RobBrazier/Laravel_Piwik/commit/e4625ffbaba0240fe307fabfa5ba9e3c9fdc8478)
- Update 02_API_Docs.md [`5d40ff1`](https://github.com/RobBrazier/Laravel_Piwik/commit/5d40ff1ca143b1d363eb3542c678aa2a7f7e61de)
- Remove absolute urls to API Docs from docs [`7654990`](https://github.com/RobBrazier/Laravel_Piwik/commit/76549908783c6dfcff08437073d9ac4089bfa03b)
- skip building gh-pages branch [`56de7b6`](https://github.com/RobBrazier/Laravel_Piwik/commit/56de7b65745808de416b419a1cc00dbd4d625519)
- Update README.md [`97ca225`](https://github.com/RobBrazier/Laravel_Piwik/commit/97ca225c74db7342ccaa8c389fbe65fb77dc745c)
- add more tags to sami api docs generation [`3ce630a`](https://github.com/RobBrazier/Laravel_Piwik/commit/3ce630a6abc7e4dff5d4496159b5bc5461b7f253)
- Removed CI and Waffle from README [`afc2dcb`](https://github.com/RobBrazier/Laravel_Piwik/commit/afc2dcb2d00724c3cdb57d0039e6c6b3ba4da704)
- force sami to return successfully [`59aaed3`](https://github.com/RobBrazier/Laravel_Piwik/commit/59aaed3492da606f78257fdecec63b3789ec37fc)
- change composer.json [`b502ab5`](https://github.com/RobBrazier/Laravel_Piwik/commit/b502ab50c91ed4f86a0fcc1f9dca912b214b0c08)
- create build directory for api docs to copy to [`81b1535`](https://github.com/RobBrazier/Laravel_Piwik/commit/81b15354d64e24c1d437faed693cc1989f414f5f)

## [3.2.0](https://github.com/RobBrazier/Laravel_Piwik/compare/3.1.0...3.2.0) - 2018-07-17

### Commits

- #85 add ContentsModule [`981f470`](https://github.com/RobBrazier/Laravel_Piwik/commit/981f470d6aa0822ae0814a53ad9dafa1bcdf9c27)
- Update version in README.md [`7bbfe11`](https://github.com/RobBrazier/Laravel_Piwik/commit/7bbfe11f2545cf38c41ffb4d76bd33f5304abc0a)
- update email [`af955a0`](https://github.com/RobBrazier/Laravel_Piwik/commit/af955a0e07be41896f3b36470fb5298c2ca271ba)
- Fix Contents phpdocs [`8c3712b`](https://github.com/RobBrazier/Laravel_Piwik/commit/8c3712b1cc5529af1f3d3ab9a1100c2d46256f00)
- Add link to 3.2.0 API Docs [`e21aac2`](https://github.com/RobBrazier/Laravel_Piwik/commit/e21aac206cecf7137c71bc2299d0dd38f110ae9d)
- update version in composer.json [`227a97e`](https://github.com/RobBrazier/Laravel_Piwik/commit/227a97ee9b255b12655474b7c7fbba259de5f241)
- fix api docs link for 3.1.0 [`44ff948`](https://github.com/RobBrazier/Laravel_Piwik/commit/44ff948b21f91a4c732d5f20e7e3d88c06070279)

## [3.1.0](https://github.com/RobBrazier/Laravel_Piwik/compare/3.0.1...3.1.0) - 2018-03-09

### Merged

- Feature/jenkins [`#56`](https://github.com/RobBrazier/Laravel_Piwik/pull/56)
- switch to jenkins [`#55`](https://github.com/RobBrazier/Laravel_Piwik/pull/55)

### Commits

- switch to go-task as runner and format for PSR2 [`b5e9e62`](https://github.com/RobBrazier/Laravel_Piwik/commit/b5e9e62f99a2467f14d382664bc77b323fcecfb2)
- Apply fixes from StyleCI [`27dd691`](https://github.com/RobBrazier/Laravel_Piwik/commit/27dd691c73a34b322bf9e3045df62b1c8613752e)
- use common scripts and update README [`945500a`](https://github.com/RobBrazier/Laravel_Piwik/commit/945500a24a7b5aa03e698a9e92025bfc8587aae6)
- #80 add SitesManager.addSite and fix some documentation [`21a9612`](https://github.com/RobBrazier/Laravel_Piwik/commit/21a96120ca63c736868da6187396214205bbca69)
- fix code style [`0d28721`](https://github.com/RobBrazier/Laravel_Piwik/commit/0d28721dc40d2a323abc5154ff970003919c4346)
- clean up scripts [`bd9be80`](https://github.com/RobBrazier/Laravel_Piwik/commit/bd9be80529348b370714d76aa313528a403b9b17)
- Remove jenkinsfile [`acaa698`](https://github.com/RobBrazier/Laravel_Piwik/commit/acaa698f650808de97424a8c0ce1eb9a8d661031)
- ditch sonarqube due to unreliability of sonarcloud.io [`533b840`](https://github.com/RobBrazier/Laravel_Piwik/commit/533b8409e49e1b60c699ed9b7e6b3ef663a2eeef)
- fix some codeclimate stuff [`31dbd36`](https://github.com/RobBrazier/Laravel_Piwik/commit/31dbd36bd4867067ff98ff4339c10f5126afd2ea)
- remove duplication from Taskfile.yml [`04de8a3`](https://github.com/RobBrazier/Laravel_Piwik/commit/04de8a3893b168de6c6d361d1a4553f93e88f5aa)
- add netlify deployment task to publish_docs [`934ff50`](https://github.com/RobBrazier/Laravel_Piwik/commit/934ff5048da1020979675fd9b26226133b128fd2)
- exclude some checks [`ca3eef5`](https://github.com/RobBrazier/Laravel_Piwik/commit/ca3eef54a71d6af2f12edafd7b21d047bbf27245)
- add contributing guidelines [`8cab7c7`](https://github.com/RobBrazier/Laravel_Piwik/commit/8cab7c78cf2ff0990074a7a31b98e3f07aa0caec)
- calculate pull request number [`4b91a2e`](https://github.com/RobBrazier/Laravel_Piwik/commit/4b91a2e957cfb93206a73f721a06e633e621b23c)
- add codeclimate qa script [`1535295`](https://github.com/RobBrazier/Laravel_Piwik/commit/15352957c994265fce16bfea079314071978b5dc)
- fix chown not working with integration [`cad3797`](https://github.com/RobBrazier/Laravel_Piwik/commit/cad37973c00d6784a96b1d258dd9c0cf4d029c60)
- restore file owner after scripts run [`b1388c7`](https://github.com/RobBrazier/Laravel_Piwik/commit/b1388c739118c5627ce3d35dbbf8918b65001517)
- fix deploy permissions when publishing documentation [`47b8244`](https://github.com/RobBrazier/Laravel_Piwik/commit/47b8244ac058615d134c023dfedd14786e24d7fc)
- apply more code style fixes [`d2a22f9`](https://github.com/RobBrazier/Laravel_Piwik/commit/d2a22f97be19f68119bd540adb0d61e39fc85e71)
- ci fixes [`2a9406d`](https://github.com/RobBrazier/Laravel_Piwik/commit/2a9406df3b079841aff90dffc366af889203c604)
- update sonar scripts [`b734c58`](https://github.com/RobBrazier/Laravel_Piwik/commit/b734c580b06db1e9e8333190b20e5e38fada8b6e)
- update phpdocs for new method [`3c17ed7`](https://github.com/RobBrazier/Laravel_Piwik/commit/3c17ed7403d60cf2a301dd1d4f96dfbd2ec9da62)
- fix group not being retrieved [`bba7d08`](https://github.com/RobBrazier/Laravel_Piwik/commit/bba7d08e965f21be757169ab99c7b1b7bac36141)
- set -x fixes [`b544a44`](https://github.com/RobBrazier/Laravel_Piwik/commit/b544a4465ae9f3ed8789e9f4f29048ea4bedadc6)
- move auth tokens to properties [`d465660`](https://github.com/RobBrazier/Laravel_Piwik/commit/d4656607a879effbd9cef3b9c3fb5b39652f8d4d)
- widen sami api docs generation tag criteria [`bfe51db`](https://github.com/RobBrazier/Laravel_Piwik/commit/bfe51db2334c917c56c25caaa5f0c5c38888febc)
- code style fixes [`2043b33`](https://github.com/RobBrazier/Laravel_Piwik/commit/2043b33b5d44fea8fa2d5016adedcd19ce58c1eb)
- add develop branch to sami [`aee895a`](https://github.com/RobBrazier/Laravel_Piwik/commit/aee895ac909a7130c903f1066a619a2e417fbcc5)
- increment version and update docs [`5e696ce`](https://github.com/RobBrazier/Laravel_Piwik/commit/5e696cef6df921c42cf6c49769f57e1be47c9e7b)
- add redirect to old documentation [`4003311`](https://github.com/RobBrazier/Laravel_Piwik/commit/40033110573b5e087a8f1509f1f5202bee606b5c)
- update Jenkinsfile to add netlify credentials [`ba9d8df`](https://github.com/RobBrazier/Laravel_Piwik/commit/ba9d8dfe874bdd46cd059e407ce7f4d55ff71420)
- move .ci-env removal to docstasks [`10c0043`](https://github.com/RobBrazier/Laravel_Piwik/commit/10c0043e9cf85a9271a4471e4b75b459c215b12f)
- fix env vars for semaphore [`0baa316`](https://github.com/RobBrazier/Laravel_Piwik/commit/0baa316658dbd560c1243e3fcd52825d7b477a30)
- update README.md [`5daa3dd`](https://github.com/RobBrazier/Laravel_Piwik/commit/5daa3ddd6ade56434d132b29124413c508ac2929)
- add missing semicolon to .sami.php [`bc9e97b`](https://github.com/RobBrazier/Laravel_Piwik/commit/bc9e97bfff869a0ae9efb5cc817d9f22910e6b6c)
- code style fixes [`4b92fd1`](https://github.com/RobBrazier/Laravel_Piwik/commit/4b92fd1eb852a97868dbab66c24812c03f4102db)
- remove unused env vars from setup.sh [`46af637`](https://github.com/RobBrazier/Laravel_Piwik/commit/46af637f46745fc7cac9d9cde0d868edd00d8aa0)
- update ci scripts submodule [`9cd8c24`](https://github.com/RobBrazier/Laravel_Piwik/commit/9cd8c2405875960b9f68c641079978ce0aa0716e)
- fix sonar command substitution [`6e42829`](https://github.com/RobBrazier/Laravel_Piwik/commit/6e42829f4f9f2227e826a83ae836cb389d912a40)
- replace env vars in sonar-project.properties [`a11724d`](https://github.com/RobBrazier/Laravel_Piwik/commit/a11724d4fd14e83489046c2b5e779e62e411156e)
- get repo slug [`c2b5339`](https://github.com/RobBrazier/Laravel_Piwik/commit/c2b53393a1d3eda60a1ba8e6fc296524063887bc)
- print environment variables [`789f33c`](https://github.com/RobBrazier/Laravel_Piwik/commit/789f33c94893c1e64aee45f4187c38ca7c83b9eb)
- remove develop branch from .sami.php [`b7459b2`](https://github.com/RobBrazier/Laravel_Piwik/commit/b7459b2d0363d054ae17719403d782f85b6274e0)
- styleci fixes [`e34cb28`](https://github.com/RobBrazier/Laravel_Piwik/commit/e34cb28d3c15e80155410291a171fafc5d80e1f8)
- add install to unit tests [`5ed1d0b`](https://github.com/RobBrazier/Laravel_Piwik/commit/5ed1d0b68354877fddfe79f08d080d823741c805)
- view env for qa step [`05080c8`](https://github.com/RobBrazier/Laravel_Piwik/commit/05080c8ea0fd30597f0566f18eed42d5552c5dbe)
- print environment variables [`579660d`](https://github.com/RobBrazier/Laravel_Piwik/commit/579660d7d7929579412c5b05eb31796ade17b8ec)

## [3.0.1](https://github.com/RobBrazier/Laravel_Piwik/compare/3.0.0...3.0.1) - 2017-08-17

### Merged

- optimise dockerfiles [`#48`](https://github.com/RobBrazier/Laravel_Piwik/pull/48)

### Commits

- fix sonar issues [`330aa7c`](https://github.com/RobBrazier/Laravel_Piwik/commit/330aa7cfcce331ceadd847355e24a29d5f258713)
- rename curl_timeout to http_timeout [`45065e2`](https://github.com/RobBrazier/Laravel_Piwik/commit/45065e250fca0c1ae9adb7cc42a10af37384ec81)
- increment version [`46f4e46`](https://github.com/RobBrazier/Laravel_Piwik/commit/46f4e468f8b68df09d738dc89290aeeb0afa19ba)
- add sonar badges [`2836ffb`](https://github.com/RobBrazier/Laravel_Piwik/commit/2836ffb59714eeb42f354e599de1ac9439289d99)
- update site id for integration test [`888040f`](https://github.com/RobBrazier/Laravel_Piwik/commit/888040f7b534754657d39496b8b3526eb831bca4)
- update phpunit.xml [`dea76ef`](https://github.com/RobBrazier/Laravel_Piwik/commit/dea76ef45a12915e746e595a250e7c82c6810d63)
- update readme to use codacy badges [`62daf28`](https://github.com/RobBrazier/Laravel_Piwik/commit/62daf28cacd43a33a3ea67a2f223a278ab2c3346)
- remove unnecessary whitespace [`f99a7e4`](https://github.com/RobBrazier/Laravel_Piwik/commit/f99a7e4f11d24cf9f26c5e01458ec6930e5500a4)
- remove serialised php coverage report [`bfa6485`](https://github.com/RobBrazier/Laravel_Piwik/commit/bfa64852929d8825332cbbc1ddb557d5ca088884)
- add license badge [`6aab8d9`](https://github.com/RobBrazier/Laravel_Piwik/commit/6aab8d9b7498c378522a4587d46ad985b38fb471)

## [3.0.0](https://github.com/RobBrazier/Laravel_Piwik/compare/2.1.3...3.0.0) - 2017-05-19

### Merged

- 35 increase phpdoc detail [`#37`](https://github.com/RobBrazier/Laravel_Piwik/pull/37)
- 33 update documentation [`#34`](https://github.com/RobBrazier/Laravel_Piwik/pull/34)

### Commits

- initial draft of v3.0.0 [`6704d79`](https://github.com/RobBrazier/Laravel_Piwik/commit/6704d795b81995bcf6a5b40f4e1859736524b0ab)
- correctly configure config tag and use orchestra phpunit testcase [`eb3043b`](https://github.com/RobBrazier/Laravel_Piwik/commit/eb3043b09438f7036a3372365edf7cc084ecc95b)
- improve test coverage and start Piwik class refactoring [`9d83c82`](https://github.com/RobBrazier/Laravel_Piwik/commit/9d83c828e3bae8efb460e8b25045bcce512c180a)
- stabilise tests [`421e568`](https://github.com/RobBrazier/Laravel_Piwik/commit/421e568a32bc11f8afa9b0873544fbb5d06d1748)
- add xml parsing support [`4ff82aa`](https://github.com/RobBrazier/Laravel_Piwik/commit/4ff82aad16a7ff3d72883d5dd4df29362cfed89c)
- improve unit test coverage and remove service provider from scope [`49d2b16`](https://github.com/RobBrazier/Laravel_Piwik/commit/49d2b160bc5df54cc1cdee785ad187283d5fcea9)
- add more unit tests [`08b5e6e`](https://github.com/RobBrazier/Laravel_Piwik/commit/08b5e6e920045ef9cf51971cda672e662414e1ec)
- increase module test coverage [`4fd9a21`](https://github.com/RobBrazier/Laravel_Piwik/commit/4fd9a2190b04c42ed009c090f3aa4fb49833272d)
- increase module test coverage [`a951e48`](https://github.com/RobBrazier/Laravel_Piwik/commit/a951e488b3924717a7e81f04c9b59f20c8b5210a)
- add tests to cover actions and api modules [`3718201`](https://github.com/RobBrazier/Laravel_Piwik/commit/3718201daaffddd34c478097f09c990ef265917d)
- Scrutinizer Auto-Fixes [`f6b837c`](https://github.com/RobBrazier/Laravel_Piwik/commit/f6b837c6c99969378efffb1fdcd9088865069927)
- update composer.lock [`911fa2a`](https://github.com/RobBrazier/Laravel_Piwik/commit/911fa2a22481bb87ea86179ccdfce19f4f3b7e42)
- add phpdoc comments [`9f0777b`](https://github.com/RobBrazier/Laravel_Piwik/commit/9f0777b9763cbabf308490d6948e1a25d94efdf0)
- Scrutinizer Auto-Fixes [`1fecb94`](https://github.com/RobBrazier/Laravel_Piwik/commit/1fecb944a5c15295d6adee5182098fbfc161e48b)
- remove xml parser [`d3fd28d`](https://github.com/RobBrazier/Laravel_Piwik/commit/d3fd28d917e1e74bfc653c22138f31ee9b986b71)
- remove username and password [`fed3270`](https://github.com/RobBrazier/Laravel_Piwik/commit/fed3270f2a4734ac955c3f8864ae90ef7b22348b)
- fix phpunit file loading errors [`182a555`](https://github.com/RobBrazier/Laravel_Piwik/commit/182a555f976cb86715fdd92b3c5671e99623a397)
- fix scrutinizer issues [`88e2c1f`](https://github.com/RobBrazier/Laravel_Piwik/commit/88e2c1f5d917c26a30792c14cdcb1d4a736bdb9f)
- remove composer console bloat and fix readme formatting [`0a64270`](https://github.com/RobBrazier/Laravel_Piwik/commit/0a64270049fbcc62f290324e178f02c411aafad1)
- update ci scripts and integration config [`3e0161b`](https://github.com/RobBrazier/Laravel_Piwik/commit/3e0161be01c513ac96b8eb09625e0d47b500da10)
- fix new issues [`49e6a3f`](https://github.com/RobBrazier/Laravel_Piwik/commit/49e6a3f55058c99e49c9d26984c935a40d0f895a)
- fix concatenation issues and add another testcase to Url [`86fb174`](https://github.com/RobBrazier/Laravel_Piwik/commit/86fb17417e210fbcdf8186a6a69f12eb09616610)
- switch xml dependency from require-dev [`7d20945`](https://github.com/RobBrazier/Laravel_Piwik/commit/7d20945a8ea2cbabaa5cab6046886e4fa6998cec)
- rename short variable [`fb8c195`](https://github.com/RobBrazier/Laravel_Piwik/commit/fb8c1959ae4b10285370102d1b839e810eeaee45)
- fix loose comparison of format [`e1cea88`](https://github.com/RobBrazier/Laravel_Piwik/commit/e1cea88d45db5335cb6bb50fbd7c9fac0a5e1138)
- phpunit debugging on ci [`d23ed18`](https://github.com/RobBrazier/Laravel_Piwik/commit/d23ed180faa7a49821560deb7220a68da9276a5e)
- phpunit debugging on ci [`18f4469`](https://github.com/RobBrazier/Laravel_Piwik/commit/18f446914acfe7ca5fad37a2c14c47fade34b71d)
- move prestissimo install location [`63fff41`](https://github.com/RobBrazier/Laravel_Piwik/commit/63fff4134b3d54cb4def906896d861594923dec8)
- cut integration by 8 seconds and remove git dependency [`ab5354d`](https://github.com/RobBrazier/Laravel_Piwik/commit/ab5354db171a8dc1d7c317ea1eeb88c1371790ef)
- move coverage.xml location [`f9ed8af`](https://github.com/RobBrazier/Laravel_Piwik/commit/f9ed8af53c78fa1839cabbdb86a3d2e227451cfc)
- remove dev dependencies for integration [`5ad5323`](https://github.com/RobBrazier/Laravel_Piwik/commit/5ad5323e319117d05f90b02af3a53fce7ecb35c7)
- remove xml parser [`3720e23`](https://github.com/RobBrazier/Laravel_Piwik/commit/3720e23517d9b08e79b668381190e3eeb37506a5)
- use correct scrutinizer image [`a86cb23`](https://github.com/RobBrazier/Laravel_Piwik/commit/a86cb23107cde81f5fa6d06c4479a0378edf5833)
- switch from scrutinizer to codacy [`d840d60`](https://github.com/RobBrazier/Laravel_Piwik/commit/d840d60492b2e92d5612ced96e72d88d6ecb9c60)
- switch back to phpunit [`0151eca`](https://github.com/RobBrazier/Laravel_Piwik/commit/0151eca2288afe61901f8771e33534b355a841a6)
- fix codacy issue [`e703699`](https://github.com/RobBrazier/Laravel_Piwik/commit/e7036998979a027ce3e43c719db204c3b6dfad6f)
- switch to codecov.io coverage [`cb6a38b`](https://github.com/RobBrazier/Laravel_Piwik/commit/cb6a38b42972b0af42d87216f0e63c07bfefe6ae)
- remove dev dependencies for integration [`907788b`](https://github.com/RobBrazier/Laravel_Piwik/commit/907788b74af27ea4bf6bb2abb34bb765d36efc8e)
- remove dev dependencies for integration [`fb0b262`](https://github.com/RobBrazier/Laravel_Piwik/commit/fb0b262d8e172bee05d337d214d59262032f043a)
- composer prefer dist [`713a692`](https://github.com/RobBrazier/Laravel_Piwik/commit/713a6929c96cd4d51b5fb587b7b562acefdf7f30)
- update semaphore project [`ac2fa5c`](https://github.com/RobBrazier/Laravel_Piwik/commit/ac2fa5c25eecf6a1733e67b95d194fa2314c1f43)
- update sami config [`f20dccc`](https://github.com/RobBrazier/Laravel_Piwik/commit/f20dccc79f9c1e721de8ca6c9714b05560d1e07b)
- phpunit debugging on ci [`8bbfdb9`](https://github.com/RobBrazier/Laravel_Piwik/commit/8bbfdb9400ef0910bb27f2d76dc802817cc6f990)
- re-run ci [`e7c2471`](https://github.com/RobBrazier/Laravel_Piwik/commit/e7c2471d4d194481105ab487e5dcd601291a275b)
- remove dev dependencies for integration [`bb8bcca`](https://github.com/RobBrazier/Laravel_Piwik/commit/bb8bcca63f36176b70bef4e7f8f35e6d26824c4e)
- update sami config [`b6a20af`](https://github.com/RobBrazier/Laravel_Piwik/commit/b6a20afb0ce0a62b36d399dd775b2f4930f58107)
- update sami config [`c5f7487`](https://github.com/RobBrazier/Laravel_Piwik/commit/c5f748721b11052de345a3418f4cfe61766e6e74)
- update sami config [`ea21c5f`](https://github.com/RobBrazier/Laravel_Piwik/commit/ea21c5f1a1316af79515be34617010309757957d)
- update sami config [`070aadb`](https://github.com/RobBrazier/Laravel_Piwik/commit/070aadbe931f4b23f12827e701b5d04b36518d8d)
- update sami config to include current branch [`d7fb461`](https://github.com/RobBrazier/Laravel_Piwik/commit/d7fb461ec604fb672188bf4e5418cb54f410fff9)
- add prestissimo for faster composer installs [`a7bdee5`](https://github.com/RobBrazier/Laravel_Piwik/commit/a7bdee58be50fd2004c252d32b331932715287a1)

## [2.1.3](https://github.com/RobBrazier/Laravel_Piwik/compare/2.1.2...2.1.3) - 2017-04-22

### Commits

- add dockerfiles [`8cbb05a`](https://github.com/RobBrazier/Laravel_Piwik/commit/8cbb05a7df122c938797ffbd79c2b31fbcb327d1)
- use guzzle instead of curl and use scrutinizer-ci [`b9474da`](https://github.com/RobBrazier/Laravel_Piwik/commit/b9474da0a50602de6dcaffc27f7f1e50eb5a82ab)
- improve dependency stability [`efc010a`](https://github.com/RobBrazier/Laravel_Piwik/commit/efc010abc7b1f510991850d6333d7d5260869569)
- add docker integration tests [`3332d64`](https://github.com/RobBrazier/Laravel_Piwik/commit/3332d643e89bba60c93a9b1482819eb16518e436)
- increase debugging on integration and increase test timeout [`2081dfb`](https://github.com/RobBrazier/Laravel_Piwik/commit/2081dfb28d94a8eeb080017169829369fc7a786f)
- use local plugin source [`76fbe64`](https://github.com/RobBrazier/Laravel_Piwik/commit/76fbe6401f43cc22938b2d6340df8959d491c0e4)
- docker script updates [`3eed8a2`](https://github.com/RobBrazier/Laravel_Piwik/commit/3eed8a2286a98ff6f7fb67f7226fdd0a26e9d2f7)
- remove extra phpunit binary [`b2ae140`](https://github.com/RobBrazier/Laravel_Piwik/commit/b2ae140de86b7772af86b3b29243b61e1e3962f0)
- add integration check [`02b8843`](https://github.com/RobBrazier/Laravel_Piwik/commit/02b8843a060dd9720e18daf851926b3280d7c0b0)
- revert to guzzle 5 to allow php 5.4 support [`1bf300d`](https://github.com/RobBrazier/Laravel_Piwik/commit/1bf300d30bc540047276c62815e92fd3a036165e)
- use non-flat badges for consistency [`b899c68`](https://github.com/RobBrazier/Laravel_Piwik/commit/b899c68fcb3913fd7047ce6bdc32c0039350f132)
- update guzzle client [`a194e02`](https://github.com/RobBrazier/Laravel_Piwik/commit/a194e02063c5be6f0c2c026779b046c9b8fe960f)
- run update before requiring local package [`fbcce5f`](https://github.com/RobBrazier/Laravel_Piwik/commit/fbcce5f225f3ef125b80d76fb250fcbc25be64a9)
- revert php 5.4 changes and remove php 5.4 support (laravel 5.1 onwards only supports 5.5+ anyway) [`7625086`](https://github.com/RobBrazier/Laravel_Piwik/commit/762508614f46c2af33cca3b50f89a5f6c1adb562)
- use semaphore build badge [`13f2a45`](https://github.com/RobBrazier/Laravel_Piwik/commit/13f2a4578de4790e3d6c49929895b551fe78a72c)
- phpunit older version to support php 5.4 [`539ec5c`](https://github.com/RobBrazier/Laravel_Piwik/commit/539ec5c8d1b1bac7be94647ec3409ce79747200d)
- update piwik site id [`867710a`](https://github.com/RobBrazier/Laravel_Piwik/commit/867710adf9b70ae50805dd36e44206de2b2da5f2)
- restrict illuminate support version further [`4f5381a`](https://github.com/RobBrazier/Laravel_Piwik/commit/4f5381a8c20582964a7664fbfa1090f2fb2a4acc)
- add waffle.io badge [`f418868`](https://github.com/RobBrazier/Laravel_Piwik/commit/f4188682cd8d5270918fae872aedf9057fa36e69)

## [2.1.2](https://github.com/RobBrazier/Laravel_Piwik/compare/2.1.1...2.1.2) - 2016-08-20

### Commits

- #11 - add custom date ranges and refactor a bit [`6890ca2`](https://github.com/RobBrazier/Laravel_Piwik/commit/6890ca2e65a7c144d910e5cca5a187611389e341)
- #11 - update config.php to include format of custom range [`f1e1717`](https://github.com/RobBrazier/Laravel_Piwik/commit/f1e17176a8039d730c53388b6d4066f6caee22c0)
- #11 - update readme.md [`0608206`](https://github.com/RobBrazier/Laravel_Piwik/commit/060820618960246489081725ebb575888989d523)

## [2.1.1](https://github.com/RobBrazier/Laravel_Piwik/compare/2.1.0...2.1.1) - 2015-12-09

### Commits

- update tests [`9c3674d`](https://github.com/RobBrazier/Laravel_Piwik/commit/9c3674d0bcbca20c91614bcb6a371373493daf1d)
- fix domnodelist error [`05cee23`](https://github.com/RobBrazier/Laravel_Piwik/commit/05cee23aded188f5537441e6f7cbfda6c59f6bee)
- increment version [`827850e`](https://github.com/RobBrazier/Laravel_Piwik/commit/827850e8dcae9ec8b73cbde877ab0c1511c31c17)
- Revert "changed name" [`9315232`](https://github.com/RobBrazier/Laravel_Piwik/commit/931523257774f5edc9139877b17b384051003b86)
- changed name [`97310a8`](https://github.com/RobBrazier/Laravel_Piwik/commit/97310a896cc84d14d3b7996f3c0edd0b4a7f10bf)
- In case of "search", there's no page_title [`42b1efa`](https://github.com/RobBrazier/Laravel_Piwik/commit/42b1efa87199a942d550a977bc0517e85818fae8)
- updated packagist description [`97502d6`](https://github.com/RobBrazier/Laravel_Piwik/commit/97502d63ac99d072bdaa0912315ae6bcc7412e2e)

## [2.1.0](https://github.com/RobBrazier/Laravel_Piwik/compare/2.0.1...2.1.0) - 2015-04-10

### Commits

- Laravel 5 Package [`2b271dc`](https://github.com/RobBrazier/Laravel_Piwik/commit/2b271dc5b671b07995bd5aa0743ccfcbc0417f57)
- moved laravel 5 version to 2.1 [`ea912fd`](https://github.com/RobBrazier/Laravel_Piwik/commit/ea912fdf140fe59958e0a2681ba0c0b03b7a6412)
- updated documentation [`92b13db`](https://github.com/RobBrazier/Laravel_Piwik/commit/92b13db0bcc547e1d7df0c8b16c7e82bdea1ad9d)
- removed coveralls as code coverage doesn't work particularly well [`6f39c36`](https://github.com/RobBrazier/Laravel_Piwik/commit/6f39c36f38e6ccb33b0555f3520c0dfa7c424f20)
- Add coveralls after-script to travis-ci [`c284b4f`](https://github.com/RobBrazier/Laravel_Piwik/commit/c284b4f7751928ac362e84de1ccb5fb3315b4fe0)
- Switch from coveralls to codeclimate [`1d97c93`](https://github.com/RobBrazier/Laravel_Piwik/commit/1d97c934df7eb453cd8f2ec554feb49d0932a8e4)
- fix after_script [`5a8ee16`](https://github.com/RobBrazier/Laravel_Piwik/commit/5a8ee16b554a9282e06fbe6d0b5f66642d751774)
- re-read coveralls documentation and switched to php-coveralls composer package implementation [`7b276a2`](https://github.com/RobBrazier/Laravel_Piwik/commit/7b276a21d97b5466b5d8c0b3c1c213840c758b38)
- updated documentation [`5e69e14`](https://github.com/RobBrazier/Laravel_Piwik/commit/5e69e1421c7d7f0479255565b97a93493f34336c)
- updated documentation [`d985803`](https://github.com/RobBrazier/Laravel_Piwik/commit/d985803c74701d1504e10cdf6b14095ab363fbe3)
- removed coveralls as code coverage doesn't work particularly well [`501e9ea`](https://github.com/RobBrazier/Laravel_Piwik/commit/501e9ea3b4a1ffba8130cfa599aedeca6469b440)
- Added coveralls and travis status images to readme [`eca109d`](https://github.com/RobBrazier/Laravel_Piwik/commit/eca109d25572d0c64ddfee927585a4f7971fb6dc)
- Added Gemfile and test_helper.rb to try and get coveralls working [`33506a1`](https://github.com/RobBrazier/Laravel_Piwik/commit/33506a15bec87ee04d1b7c760c695a198392abce)
- moved laravel 5 version to 2.1 [`9e6e9ff`](https://github.com/RobBrazier/Laravel_Piwik/commit/9e6e9ff06a38c42f4b00a4c0f22f9fc89b1f238b)
- Add coveralls to help fixing test coverage [`e98cded`](https://github.com/RobBrazier/Laravel_Piwik/commit/e98cdedfeb44548e3b70cfa8f427144da25d3a1b)
- updated documentation [`fb91125`](https://github.com/RobBrazier/Laravel_Piwik/commit/fb91125a712a2a6ea88b7696c1d25900c72d7527)
- updated documentation [`1922677`](https://github.com/RobBrazier/Laravel_Piwik/commit/19226770128e591fb630a80792881216bb00a409)

## 2.0.1 - 2014-04-22

### Commits

- First Commit [`de342f6`](https://github.com/RobBrazier/Laravel_Piwik/commit/de342f6ec2d6c6ee824a754ff7cca0417357f83a)
- started docs [`3f1000c`](https://github.com/RobBrazier/Laravel_Piwik/commit/3f1000cb4e1fd5317c6a46aa41f38b67137f6af5)
- added the rest of the documentation [`19c0f79`](https://github.com/RobBrazier/Laravel_Piwik/commit/19c0f79aeca3cd59accda8dca96a9e3eab3e5a6a)
- Completed tests and did a bit of cleaning up [`a9138f1`](https://github.com/RobBrazier/Laravel_Piwik/commit/a9138f1e78730658e5e23fa3aee312947991f532)
- Added Travis-CI and started tests [`9468ca6`](https://github.com/RobBrazier/Laravel_Piwik/commit/9468ca6972a0c09c024358304ad4e3b0c4acce88)
- still attempting to fix documentation [`43caf82`](https://github.com/RobBrazier/Laravel_Piwik/commit/43caf82773d555428054e53c89ec4e56ac634120)
- Composer updates [`c159509`](https://github.com/RobBrazier/Laravel_Piwik/commit/c1595098ec69f658a44191d054540be04647f674)
- added documentation pages for methods [`235986d`](https://github.com/RobBrazier/Laravel_Piwik/commit/235986d9cd451266ef1d2e97ce315da174b485d5)
- Docs: added actions & downloads - checking styling [`364f5ec`](https://github.com/RobBrazier/Laravel_Piwik/commit/364f5ec497f64c60ad0e75a1c92941cf2828beef)
- attempt to fix code examples [`ea636d7`](https://github.com/RobBrazier/Laravel_Piwik/commit/ea636d7d2462dbc1e47cefd1f88744764e898062)
- Documentation installation instructions [`9b91678`](https://github.com/RobBrazier/Laravel_Piwik/commit/9b91678185cc4088979abf2b4e19042c2902d19f)
- Documentation installation formatting [`4eb4a91`](https://github.com/RobBrazier/Laravel_Piwik/commit/4eb4a9187d0350dc1d3726972eec8900d776eadb)
- Docs: re-added laravel 3 installation [`353e337`](https://github.com/RobBrazier/Laravel_Piwik/commit/353e337c216f3cab3049597f77c55ca4e0cf84e1)
- removed installation for Laravel 3 to debug [`4205355`](https://github.com/RobBrazier/Laravel_Piwik/commit/4205355bd1fce7096c19bec4ad462649322e1100)
- added Laravel 3 Installation [`6e86939`](https://github.com/RobBrazier/Laravel_Piwik/commit/6e86939645f68151df28ebe7e845a2d0a3b01416)
- README Update [`65ac072`](https://github.com/RobBrazier/Laravel_Piwik/commit/65ac072eea25fc2d9de74a9d39caa1e0c31a2fe7)
- Docs: fixed the custom code block [`afb653d`](https://github.com/RobBrazier/Laravel_Piwik/commit/afb653d321fa68190966c6b17478b7447bade1da)
- Docs: Final code block edits [`80f056d`](https://github.com/RobBrazier/Laravel_Piwik/commit/80f056dcc16335099d08bddf5bdae6e2b0e297e2)
- Docs: Index ToC tree [`c2022cf`](https://github.com/RobBrazier/Laravel_Piwik/commit/c2022cfb2b9fec770fb202be2023872256071551)
- Docs: index modifications & description [`3dea0a5`](https://github.com/RobBrazier/Laravel_Piwik/commit/3dea0a5105633ba10fadf95376a800eed4abd30a)
- README update [`2b3f3d7`](https://github.com/RobBrazier/Laravel_Piwik/commit/2b3f3d7d5c72e945702a7b55a0ef3138871df8e8)
- fixed composer fail for travis and incremented version number to 2.0.1 [`c50e6a5`](https://github.com/RobBrazier/Laravel_Piwik/commit/c50e6a589f1276ac46c6a1d2883afa5313076a86)
- removed unnecessary phpunit script and re-added hhvm [`9f1791e`](https://github.com/RobBrazier/Laravel_Piwik/commit/9f1791eaf525fa3bf740354234f7fe65541509c1)
- removed mockery from dependencies, as it isn't used anymore [`ea4c80f`](https://github.com/RobBrazier/Laravel_Piwik/commit/ea4c80f132b74d35733f86f063b61f7aefb3ad4d)
- DOCS - I give up with the syntax highlighting... just leave it as default [`645629c`](https://github.com/RobBrazier/Laravel_Piwik/commit/645629c4148ec289281f909c9eec016cbf614330)
- code blocks try #5 (this doesn't work locally) [`b88f369`](https://github.com/RobBrazier/Laravel_Piwik/commit/b88f369c45cfe67af68f714108688aafdd126f47)
- still working on code blocks ... [`044f566`](https://github.com/RobBrazier/Laravel_Piwik/commit/044f5661161d0a803605b739f90b2b681ddeeb12)
- BUGFIX: Parameter $period not works in method Piwik::custom. [`74ee8ab`](https://github.com/RobBrazier/Laravel_Piwik/commit/74ee8abb54ff4b5cb5b7d865ad083a4fccb8b34f)
- I give up... hhvm gone again [`3de6593`](https://github.com/RobBrazier/Laravel_Piwik/commit/3de659358a2b859e0cb6c28f801020cf9f52f28b)
- Fixed use statement [`94114e4`](https://github.com/RobBrazier/Laravel_Piwik/commit/94114e4b2d7b4f5321cf6392c2b8be64a284048f)
- Fix slash in composer.json [`54b79ad`](https://github.com/RobBrazier/Laravel_Piwik/commit/54b79ade21f2cdd09b3a5cbc386cd8e1ae0543fa)
- Updated composer.json support to 4.1 [`ef1f2c0`](https://github.com/RobBrazier/Laravel_Piwik/commit/ef1f2c04b5005f4bda9894a959eea900ae6d8ed7)
- Docs: modified links to be more correct [`e0777cd`](https://github.com/RobBrazier/Laravel_Piwik/commit/e0777cdf30bd9d8f9a1d616bf37f64c476a85b83)
- fix get_apikey() method [`2479316`](https://github.com/RobBrazier/Laravel_Piwik/commit/247931608676444e44399fcedbfb1e69b3b68bbc)
- Fix typo in README.md [`9b9ef2b`](https://github.com/RobBrazier/Laravel_Piwik/commit/9b9ef2b5e05d77df659edd54117de1acba627556)
- README edits [`69992ed`](https://github.com/RobBrazier/Laravel_Piwik/commit/69992ed7de5e2d5752b6bbd28ae6056731186e76)
- API Key bug fix [`2ed76fc`](https://github.com/RobBrazier/Laravel_Piwik/commit/2ed76fc9bdc8114b93ede35753e05af9ace0d4e9)
- Initial commit [`90ec95b`](https://github.com/RobBrazier/Laravel_Piwik/commit/90ec95b6b6706da1889a47cb9c44deb646c620d1)
- change requires to php 5.4+ [`488e920`](https://github.com/RobBrazier/Laravel_Piwik/commit/488e9204f6715e6ed5271ce969788c22bd26af05)
- removed hhvm for the meantime due to timeouts in travis [`496c17b`](https://github.com/RobBrazier/Laravel_Piwik/commit/496c17b10d55a77b16fdd0498c2156df871527dd)
- Added php 5.5 and HHVM [`aab20c0`](https://github.com/RobBrazier/Laravel_Piwik/commit/aab20c0b9a75a1b410e321c0fa5ede930397a36b)
- README edits [`9bb3f5c`](https://github.com/RobBrazier/Laravel_Piwik/commit/9bb3f5cd841f1cc4dad827a95a2174fc711b8f78)
- README update [`d1b400a`](https://github.com/RobBrazier/Laravel_Piwik/commit/d1b400ad323658d84247877191aea100c164ace2)
- README updates [`4769df7`](https://github.com/RobBrazier/Laravel_Piwik/commit/4769df75f1b0afb91a71524a372515d6d19e2ac7)
- README update [`06dddc6`](https://github.com/RobBrazier/Laravel_Piwik/commit/06dddc6ee7b65ccb7bc1bb7d14984810e3226858)
- removed unnecessary phpunit script and re-added hhvm + php 5.6 [`cda0681`](https://github.com/RobBrazier/Laravel_Piwik/commit/cda0681ef2f969741172315589e4980c62bdf31d)
- added Laravel 3 Installation to index [`1c186ed`](https://github.com/RobBrazier/Laravel_Piwik/commit/1c186eddeefd5094ae932b7b5379f1547f4927d4)
