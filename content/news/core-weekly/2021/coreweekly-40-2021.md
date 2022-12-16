---
layout: post
aliases: ["/news/coreweekly-40-2021"]
title:  "PrestaShop Core Weekly - Week 40 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-10-12
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 4th to Sunday 10th of October 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

In case you did not see it, [PrestaShop 1.7.8.0](https://build.prestashop.com/news/prestashop-1-7-8-0-available/) was released last week!

Of course, we always recommended using the latest available version of the [1-Click Upgrade module](https://github.com/PrestaShop/autoupgrade) when upgrading. However, if you are upgrading your shop to 1.7.8 from a version prior to **1.7.6**, make sure the module is updated to version 4.12.0 or later.

As usual, it is recommended to be careful before starting to update your website to the latest version:

- Backup your database and your files
- Test the update on a testing or pre production server
- If everything is fine, then update on the production environment

If you notice issues with PrestaShop 1.7.8.0, you can [report it on GitHub](https://github.com/PrestaShop/PrestaShop/issues) and go even further by submitting a [pull request](https://github.com/PrestaShop/PrestaShop/compare) to help fix it!

Now that 1.7.8.0 is out, we look forward to the future! Do you want to know more about it? Check what [@eternoendless](https://github.com/eternoendless) presented during the 9th [PrestaShop Public Demo](https://www.youtube.com/watch?v=x37-QOockEo&t=155s)!


## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop): [1.7.8.0](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.8.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [65 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-10-04..2021-10-10) have been created in the project repositories;
- [94 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-10-04..2021-10-10), including [14 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-10-04..2021-10-10) on the core;
- [99 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-10-04..2021-10-10) in the project repositories;
- [106 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-10-04..2021-10-10), including [77 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-10-04..2021-10-10).
        


## Code changes in the 'develop' branch


### Core
* [#26057](https://github.com/PrestaShop/PrestaShop/pull/26057): Update 1.8 into 8.0 version. Thank you [@PrestaEdit](https://github.com/PrestaEdit)
* [#25916](https://github.com/PrestaShop/PrestaShop/pull/25916): PHPStan (Level 1) on classes/, by [@Progi1984](https://github.com/Progi1984)
* [#25245](https://github.com/PrestaShop/PrestaShop/pull/25245): Remove Theme & Modules Catalog and PrestaTrust calls, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#26118](https://github.com/PrestaShop/PrestaShop/pull/26118): Change material-icons library causing a too long install, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#26086](https://github.com/PrestaShop/PrestaShop/pull/26086): Create CommandAccessor component which will be used by the command builders services, by [@jolelievre](https://github.com/jolelievre)
* [#26081](https://github.com/PrestaShop/PrestaShop/pull/26081): Switch new-theme to esbuild-loader from babel-loader and add webpack-dev-server, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#26055](https://github.com/PrestaShop/PrestaShop/pull/26055): Add placeholders in product settings page. Thank you [@okom3pom](https://github.com/okom3pom)
* [#26042](https://github.com/PrestaShop/PrestaShop/pull/26042): Allow # ° ... for credit slip prefix. Thank you [@okom3pom](https://github.com/okom3pom)
* [#25775](https://github.com/PrestaShop/PrestaShop/pull/25775): Fixed import of macros for infotip use in multistore mode, by [@Progi1984](https://github.com/Progi1984)
* [#25686](https://github.com/PrestaShop/PrestaShop/pull/25686): Use editable customer and avoid loading unnecessary data. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25291](https://github.com/PrestaShop/PrestaShop/pull/25291): Show error delete product on order page admin. Thank you [@ytilotti](https://github.com/ytilotti)
* [#25066](https://github.com/PrestaShop/PrestaShop/pull/25066): Removed links in employee menu & Added hook for adding links, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#25857](https://github.com/PrestaShop/PrestaShop/pull/25857): Fetch and set logo image size inside template. Thank you [@Oksydan](https://github.com/Oksydan)
* [#25834](https://github.com/PrestaShop/PrestaShop/pull/25834): Fix the StoreController and add missing data, by [@kpodemski](https://github.com/kpodemski)
* [#25395](https://github.com/PrestaShop/PrestaShop/pull/25395): Fix revisiting order confirmation and guest to customer conversion in FO. Thank you [@Hlavtox](https://github.com/Hlavtox)


### Installer
* [#26126](https://github.com/PrestaShop/PrestaShop/pull/26126): Do not use md5 password for fixtures, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests
* [#26148](https://github.com/PrestaShop/PrestaShop/pull/26148): Delete module catalog page, and add test checking its access, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#26138](https://github.com/PrestaShop/PrestaShop/pull/26138): Properly copy property content instead of the whole directory when copying it into gcloud, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#26122](https://github.com/PrestaShop/PrestaShop/pull/26122): Revert changes on the smtp server to fix nightly tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#26120](https://github.com/PrestaShop/PrestaShop/pull/26120): Fix selectors for Sql manager page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#26116](https://github.com/PrestaShop/PrestaShop/pull/26116): Functional tests - Refacto Shop Parameters > Order Settings tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#26112](https://github.com/PrestaShop/PrestaShop/pull/26112): Functional tests - Refacto shop parameters general. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#26110](https://github.com/PrestaShop/PrestaShop/pull/26110): Fix selectors for db backup page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#26079](https://github.com/PrestaShop/PrestaShop/pull/26079): Fixing titles, steps and comments on FO tests, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.8.x' branch


### Core
* [#26085](https://github.com/PrestaShop/PrestaShop/pull/26085): Update changelog for 1780 RC1 Build6, by [@sowbiba](https://github.com/sowbiba)


### Front office
* [#25903](https://github.com/PrestaShop/PrestaShop/pull/25903): Fixed preview of product in frontoffice, by [@Progi1984](https://github.com/Progi1984)


## Code changes in modules, themes & tools


### New 8.0.0 Front-office theme
* [#65](https://github.com/PrestaShop/theme-refacto/pull/65): Update readme in order to precise which branch to use, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#64](https://github.com/PrestaShop/theme-refacto/pull/64): Kick unused variables, moove some forms styles and use badge instead of custom flags style, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#63](https://github.com/PrestaShop/theme-refacto/pull/63): Adjust custom style so its easier to comment it, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#62](https://github.com/PrestaShop/theme-refacto/pull/62): Change colors, font sizes because of new mockups, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#59](https://github.com/PrestaShop/theme-refacto/pull/59): Change theme name in config, by [@NeOMakinG](https://github.com/NeOMakinG)


### QA nightly results
* [#63](https://github.com/PrestaShop/QANightlyResults/pull/63): Release new version for the download links, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#62](https://github.com/PrestaShop/QANightlyResults/pull/62): Fix downloads links, by [@PierreRambaud](https://github.com/PierreRambaud)


### Customer reassurance block module
* [#287](https://github.com/PrestaShop/blockreassurance/pull/287): Bump webpack from 5.57.1 to 5.58.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#286](https://github.com/PrestaShop/blockreassurance/pull/286): Bump mini-css-extract-plugin from 2.4.1 to 2.4.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#285](https://github.com/PrestaShop/blockreassurance/pull/285): Bump webpack-cli from 4.8.0 to 4.9.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#284](https://github.com/PrestaShop/blockreassurance/pull/284): Bump @babel/core from 7.15.5 to 7.15.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#283](https://github.com/PrestaShop/blockreassurance/pull/283): Bump webpack from 5.56.1 to 5.57.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#282](https://github.com/PrestaShop/blockreassurance/pull/282): Bump mini-css-extract-plugin from 2.3.0 to 2.4.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#281](https://github.com/PrestaShop/blockreassurance/pull/281): Bump webpack from 5.56.0 to 5.56.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#279](https://github.com/PrestaShop/blockreassurance/pull/279): Bump webpack from 5.55.1 to 5.56.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#524](https://github.com/PrestaShop/ps_facetedsearch/pull/524): Bump webpack from 5.57.1 to 5.58.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#523](https://github.com/PrestaShop/ps_facetedsearch/pull/523): Bump @babel/core from 7.15.5 to 7.15.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#522](https://github.com/PrestaShop/ps_facetedsearch/pull/522): Bump @babel/node from 7.15.4 to 7.15.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#521](https://github.com/PrestaShop/ps_facetedsearch/pull/521): Bump @babel/preset-env from 7.15.6 to 7.15.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#520](https://github.com/PrestaShop/ps_facetedsearch/pull/520): Bump webpack from 5.56.1 to 5.57.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#519](https://github.com/PrestaShop/ps_facetedsearch/pull/519): Bump webpack from 5.56.0 to 5.56.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#518](https://github.com/PrestaShop/ps_facetedsearch/pull/518): Bump webpack from 5.55.1 to 5.56.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation sources
* [#1174](https://github.com/PrestaShop/docs/pull/1174): Backport PR 1153 to 1.7.x, by [@matks](https://github.com/matks)
* [#1173](https://github.com/PrestaShop/docs/pull/1173): Backport PR 1160 to 8.x, by [@matks](https://github.com/matks)
* [#1172](https://github.com/PrestaShop/docs/pull/1172): Backport PR 1155 to 8.x, by [@matks](https://github.com/matks)
* [#1171](https://github.com/PrestaShop/docs/pull/1171): Update "themes" section for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1170](https://github.com/PrestaShop/docs/pull/1170): Update "FAQ", "scale", "testing" and "webservice" sections for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1169](https://github.com/PrestaShop/docs/pull/1169): Update "development" section for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1168](https://github.com/PrestaShop/docs/pull/1168): Update "contribute" section for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1167](https://github.com/PrestaShop/docs/pull/1167): Update "basics" section for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1166](https://github.com/PrestaShop/docs/pull/1166): Update 1.7.x nginx template. Thank you [@juangiordana](https://github.com/juangiordana)
* [#1155](https://github.com/PrestaShop/docs/pull/1155): Fix Classic translation system documentation. Thank you [@zou-simon](https://github.com/zou-simon)
* [#1118](https://github.com/PrestaShop/docs/pull/1118): Explain Form Theme and project progress, by [@matks](https://github.com/matks)


### PrestaShop Specifications
* [#241](https://github.com/PrestaShop/prestashop-specs/pull/241): Update multistore special cases, by [@marionf](https://github.com/marionf)


### Docker images
* [#278](https://github.com/PrestaShop/docker/pull/278): Update base images and nightly images, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#276](https://github.com/PrestaShop/docker/pull/276): Add 1.7.8.0. Thank you [@okom3pom](https://github.com/okom3pom)


### User documentation landing page
* [#138](https://github.com/PrestaShop/user-documentation-landing/pull/138): fix(deps): bump core-js from 3.18.1 to 3.18.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### stylelint configuration
* [#23](https://github.com/PrestaShop/stylelint-config/pull/23): Bump ansi-regex from 5.0.0 to 5.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#22](https://github.com/PrestaShop/stylelint-config/pull/22): Bump stylelint-config-twbs-bootstrap from 2.2.3 to 2.2.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Catalog statistics module
* [#19](https://github.com/PrestaShop/statscatalog/pull/19): Updated composer dependencies, by [@Progi1984](https://github.com/Progi1984)


### Core Weekly Generator tool
* [#106](https://github.com/PrestaShop/core-weekly-generator/pull/106): Add psssst to repository list, by [@matks](https://github.com/matks)


### Issues Bot
* [#26](https://github.com/PrestaShop/issuebot/pull/26): Make InstallationId configurable, by [@sowbiba](https://github.com/sowbiba)


### Auto Upgrade module
* [#417](https://github.com/PrestaShop/autoupgrade/pull/417): Remove useless message. Thank you [@okom3pom](https://github.com/okom3pom)
* [#416](https://github.com/PrestaShop/autoupgrade/pull/416): Don't hide expert mode when major chanel selected. Thank you [@okom3pom](https://github.com/okom3pom)
* [#402](https://github.com/PrestaShop/autoupgrade/pull/402): Add suppliers sql upgrade, by [@atomiix](https://github.com/atomiix)


### Search Bar module
* [#38](https://github.com/PrestaShop/ps_searchbar/pull/38): Add upgrade script to clean a file from classic core theme, by [@jolelievre](https://github.com/jolelievre)


### Prestashop Shop Creator
* [#7](https://github.com/PrestaShop/prestashop-shop-creator/pull/7): Fix excessive number of images per product. Thank you [@davidglezz](https://github.com/davidglezz)


### GDPR module
* [#108](https://github.com/PrestaShop/psgdpr/pull/108): Update logo and short description, by [@Julievrz](https://github.com/Julievrz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@NeOMakinG](https://github.com/NeOMakinG), [@PierreRambaud](https://github.com/PierreRambaud), [@dependabot[bot]](https://github.com/apps/dependabot), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@boubkerbribri](https://github.com/boubkerbribri), [@marionf](https://github.com/marionf), [@okom3pom](https://github.com/okom3pom), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@sowbiba](https://github.com/sowbiba), [@juangiordana](https://github.com/juangiordana), [@jolelievre](https://github.com/jolelievre), [@Progi1984](https://github.com/Progi1984), [@PrestaEdit](https://github.com/PrestaEdit), [@zou-simon](https://github.com/zou-simon), [@Oksydan](https://github.com/Oksydan), [@kpodemski](https://github.com/kpodemski), [@atomiix](https://github.com/atomiix), [@Hlavtox](https://github.com/Hlavtox), [@ytilotti](https://github.com/ytilotti), [@davidglezz](https://github.com/davidglezz), [@Julievrz](https://github.com/Julievrz)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

