---
layout: post
aliases: ["/news/coreweekly-06-2021"]
title:  "PrestaShop Core Weekly - Week 6 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-02-15
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 8th to Sunday 14th of February 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Last Friday maintainer [@pululuk](https://github.com/pululuk), helped by [@sowbiba](https://github.com/sowbiba) and many others built the ZIP archive for [PrestaShop 1.7.7.2](https://github.com/PrestaShop/PrestaShop/issues/22783) and delivered it to QA team for validation. This is the second time a PrestaShop release is built by someone who is not an employee of PrestaShop company! Congratulations [@pululuk](https://github.com/pululuk)!

Another interesting news: thanks to the [awesome work](https://github.com/PrestaShop/autoupgrade/pull/377) of [@atomiix](https://github.com/atomiix), the upgrades between PrestaShop versions using the autoupgrade module are now being run every night and results can be looked at in the [Nightly build dashboard](https://nightly.prestashop.com/)

In the meantime, [@NeOMakinG](https://github.com/NeOMakinG) also upgraded the [jQuery version to v3.5 for Classic Theme and default Back Office theme](https://github.com/PrestaShop/PrestaShop/pull/23122).

The next step for release 1.7.7.2 is now QA validation. Release is expected to happen at the latest on next Monday (22th of February).

## Releases

* [autoupgrade](https://github.com/PrestaShop/autoupgrade) module: [v4.12.0](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.12.0)
* [ps_linklist](https://github.com/PrestaShop/ps_linklist) module: [v4.0.0](https://github.com/PrestaShop/ps_linklist/releases/tag/v4.0.0)
* [ps_searchbar](https://github.com/PrestaShop/ps_searchbar) module: [v2.0.2](https://github.com/PrestaShop/ps_searchbar/releases/tag/v2.0.2)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [75 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-02-08..2021-02-14) have been created in the project repositories;
- [52 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-02-08..2021-02-14), including [10 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-02-08..2021-02-14) on the core;
- [76 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-02-08..2021-02-14) in the project repositories;
- [86 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-02-08..2021-02-14), including [76 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-02-08..2021-02-14).



## Code changes in the 'develop' branch


### Core
* [#23210](https://github.com/PrestaShop/PrestaShop/pull/23210): Fix wrong namespace path, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23200](https://github.com/PrestaShop/PrestaShop/pull/23200): Add constant visibility in all classes of src, by [@matks](https://github.com/matks)
* [#23184](https://github.com/PrestaShop/PrestaShop/pull/23184): Updated JS Routing & package-lock.json in new-theme files. Thank you [@github-actions[bot]](https://github.com/apps/github-actions)
* [#23122](https://github.com/PrestaShop/PrestaShop/pull/23122): Update jQuery on classic, FO core and default BO theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23118](https://github.com/PrestaShop/PrestaShop/pull/23118): Remove statslive module, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23094](https://github.com/PrestaShop/PrestaShop/pull/23094): Add ISBN and UPC to combinations data. Thank you [@Hlavtox](https://github.com/Hlavtox)


### Back office
* [#23205](https://github.com/PrestaShop/PrestaShop/pull/23205): Cast productSupplier reference to string. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23180](https://github.com/PrestaShop/PrestaShop/pull/23180): Set combinations attributes closed by default if combinations > 0, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23179](https://github.com/PrestaShop/PrestaShop/pull/23179): Move stock related classes to Stock namespace. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23177](https://github.com/PrestaShop/PrestaShop/pull/23177): Init switches when adding new customization on product page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23173](https://github.com/PrestaShop/PrestaShop/pull/23173): Hide category tree by default on product page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23136](https://github.com/PrestaShop/PrestaShop/pull/23136): Up status select padding to avoid text getting under arrow, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23072](https://github.com/PrestaShop/PrestaShop/pull/23072): Fix help modal BO responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23069](https://github.com/PrestaShop/PrestaShop/pull/23069): Fix sidebar visibility when hidden by default on default theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23043](https://github.com/PrestaShop/PrestaShop/pull/23043): Translations: Add catalogue and tree providers, by [@sowbiba](https://github.com/sowbiba)
* [#22277](https://github.com/PrestaShop/PrestaShop/pull/22277): Introduce UpdateCombinationFromListCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21527](https://github.com/PrestaShop/PrestaShop/pull/21527): Simplify translations form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Front office
* [#23175](https://github.com/PrestaShop/PrestaShop/pull/23175): Remove redundant operation in ProductController, by [@eternoendless](https://github.com/eternoendless)
* [#23056](https://github.com/PrestaShop/PrestaShop/pull/23056): Change classic selectors to js prefixed selectors, by [@NeOMakinG](https://github.com/NeOMakinG)


### Web services
* [#23081](https://github.com/PrestaShop/PrestaShop/pull/23081): Fix the combination's disappearance from Cart when it's updated by WS. Thank you [@fabiovannini](https://github.com/fabiovannini)


### Tests
* [#23217](https://github.com/PrestaShop/PrestaShop/pull/23217): Rename behat.yml into integration.yml, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch


### Core
* [#23224](https://github.com/PrestaShop/PrestaShop/pull/23224): Update PrestaShop's composer dependencies, by [@atomiix](https://github.com/atomiix)
* [#23220](https://github.com/PrestaShop/PrestaShop/pull/23220): Update composer versions of native modules for 1.7.7.2, by [@matks](https://github.com/matks)
* [#22682](https://github.com/PrestaShop/PrestaShop/pull/22682): Fix warning/errors from upgrade scripts, by [@atomiix](https://github.com/atomiix)


### Back office
* [#23078](https://github.com/PrestaShop/PrestaShop/pull/23078): Fixed missing APE/SIRET Code in BackOffice Order View, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#22528](https://github.com/PrestaShop/PrestaShop/pull/22528): Better handle aliases with space in search, by [@atomiix](https://github.com/atomiix)


### Tests
* [#23129](https://github.com/PrestaShop/PrestaShop/pull/23129): Add test - Enable/Disable demo mode. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22875](https://github.com/PrestaShop/PrestaShop/pull/22875): Rename default account var name, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#865](https://github.com/PrestaShop/docs/pull/865): Fix link to testing introduction. Thank you [@Paddimir](https://github.com/Paddimir)
* [#862](https://github.com/PrestaShop/docs/pull/862): Update information on displayCarrierExtraContent hook. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#860](https://github.com/PrestaShop/docs/pull/860): Fix return error in execute method. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#855](https://github.com/PrestaShop/docs/pull/855): Add page about users, login and secure_key, by [@matks](https://github.com/matks)


### PrestaShop PHPStan extension
* [#8](https://github.com/PrestaShop/phpstan-prestashop/pull/8): Add PrestaShop as author in composer.json, by [@matks](https://github.com/matks)
* [#5](https://github.com/PrestaShop/phpstan-prestashop/pull/5): Add ClassConstantsMustHaveVisibilityRule, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#385](https://github.com/PrestaShop/autoupgrade/pull/385): Fix get_matrix returning the same value twice, by [@atomiix](https://github.com/atomiix)
* [#384](https://github.com/PrestaShop/autoupgrade/pull/384): Update GCP secret keys, by [@atomiix](https://github.com/atomiix)
* [#383](https://github.com/PrestaShop/autoupgrade/pull/383): Fix phpstan, by [@atomiix](https://github.com/atomiix)
* [#382](https://github.com/PrestaShop/autoupgrade/pull/382): Replace Travis (deprecated) badge by GitHub Action Upgrade badge, by [@matks](https://github.com/matks)
* [#381](https://github.com/PrestaShop/autoupgrade/pull/381): Release 4.12.0, by [@matks](https://github.com/matks)
* [#380](https://github.com/PrestaShop/autoupgrade/pull/380): Bump v4.12.0, by [@matks](https://github.com/matks)


### Customer reassurance block module
* [#128](https://github.com/PrestaShop/blockreassurance/pull/128): Bump @babel/core from 7.12.13 to 7.12.16. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#127](https://github.com/PrestaShop/blockreassurance/pull/127): Bump mini-css-extract-plugin from 1.3.5 to 1.3.6. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#126](https://github.com/PrestaShop/blockreassurance/pull/126): Bump css-loader from 5.0.1 to 5.0.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#125](https://github.com/PrestaShop/blockreassurance/pull/125): Bump sass-loader from 11.0.0 to 11.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#124](https://github.com/PrestaShop/blockreassurance/pull/124): Bump sass-loader from 10.1.1 to 11.0.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#123](https://github.com/PrestaShop/blockreassurance/pull/123): Bump webpack from 5.20.2 to 5.21.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#333](https://github.com/PrestaShop/ps_facetedsearch/pull/333): Bump @babel/core from 7.12.13 to 7.12.16. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#332](https://github.com/PrestaShop/ps_facetedsearch/pull/332): Bump @babel/node from 7.12.13 to 7.12.16. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#331](https://github.com/PrestaShop/ps_facetedsearch/pull/331): Bump @babel/preset-env from 7.12.13 to 7.12.16. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#330](https://github.com/PrestaShop/ps_facetedsearch/pull/330): Bump mocha from 8.2.1 to 8.3.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#329](https://github.com/PrestaShop/ps_facetedsearch/pull/329): Bump @babel/cli from 7.12.13 to 7.12.16. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#328](https://github.com/PrestaShop/ps_facetedsearch/pull/328): Bump css-loader from 5.0.1 to 5.0.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#327](https://github.com/PrestaShop/ps_facetedsearch/pull/327): Bump sass-loader from 11.0.0 to 11.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#326](https://github.com/PrestaShop/ps_facetedsearch/pull/326): Bump sass-loader from 10.1.1 to 11.0.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#325](https://github.com/PrestaShop/ps_facetedsearch/pull/325): Bump webpack from 5.20.2 to 5.21.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Links list module
* [#112](https://github.com/PrestaShop/ps_linklist/pull/112): Bump prestashop/php-dev-tools from 3.4 to 3.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#111](https://github.com/PrestaShop/ps_linklist/pull/111): Fix license headers, by [@matks](https://github.com/matks)
* [#110](https://github.com/PrestaShop/ps_linklist/pull/110): Release 4.0.0, by [@matks](https://github.com/matks)
* [#65](https://github.com/PrestaShop/ps_linklist/pull/65): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Search Bar module
* [#32](https://github.com/PrestaShop/ps_searchbar/pull/32): Release v2.0.2, by [@atomiix](https://github.com/atomiix)
* [#31](https://github.com/PrestaShop/ps_searchbar/pull/31): Uninstall module used on PS 1.6 before using this one, by [@atomiix](https://github.com/atomiix)


### Dashboard Activity module
* [#24](https://github.com/PrestaShop/dashactivity/pull/24): Bump version to v2.1.0, update min core compatibility, by [@matks](https://github.com/matks)


### User documentation landing page
* [#25](https://github.com/PrestaShop/user-documentation-landing/pull/25): chore(deps-dev): bump sass from 1.32.6 to 1.32.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#24](https://github.com/PrestaShop/user-documentation-landing/pull/24): fix(deps): bump actions/cache from v2 to v2.1.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Core Weekly Generator tool
* [#75](https://github.com/PrestaShop/core-weekly-generator/pull/75): Add PS modules registry, by [@matks](https://github.com/matks)
* [#74](https://github.com/PrestaShop/core-weekly-generator/pull/74): Don't use thanks message for bots, by [@PierreRambaud](https://github.com/PierreRambaud)


### Wishlist block module
* [#98](https://github.com/PrestaShop/blockwishlist/pull/98): Add a message and fix error when on multishop. Thank you [@pablopolyte](https://github.com/pablopolyte)


### Banner module
* [#29](https://github.com/PrestaShop/ps_banner/pull/29): Release 2.1.1 - again, by [@matks](https://github.com/matks)
* [#28](https://github.com/PrestaShop/ps_banner/pull/28): Release 2.1.1, by [@matks](https://github.com/matks)
* [#24](https://github.com/PrestaShop/ps_banner/pull/24): Add UI test to ps banner module, by [@boubkerbribri](https://github.com/boubkerbribri)


### Customer "Sign in" link module
* [#33](https://github.com/PrestaShop/ps_customersignin/pull/33): Release 2.0.4, by [@matks](https://github.com/matks)


### Prestashop UI Kit
* [#133](https://github.com/PrestaShop/prestashop-ui-kit/pull/133): Export every methods of the UIKit, by [@NeOMakinG](https://github.com/NeOMakinG)


### Shopping cart module
* [#74](https://github.com/PrestaShop/ps_shoppingcart/pull/74): Improve project files, by [@Progi1984](https://github.com/Progi1984)


### LocalizationFiles
* [#5](https://github.com/PrestaShop/LocalizationFiles/pull/5): Translate Ukrainian locale from Russian to Ukrainian. Thank you [@rakvium](https://github.com/rakvium)


## Where to start contributing?

What about [fixing a success message that is incorrect](https://github.com/PrestaShop/PrestaShop/issues/21867) and is displayed when a search alias is created from the Back Office? This is a bug report submitted three months ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Paddimir](https://github.com/Paddimir), [@matks](https://github.com/matks), [@Hlavtox](https://github.com/Hlavtox), [@jf-viguier](https://github.com/jf-viguier), [@atomiix](https://github.com/atomiix), [@dependabot[bot]](https://github.com/apps/dependabot), [@PierreRambaud](https://github.com/PierreRambaud), [@zuk3975](https://github.com/zuk3975), [@github-actions[bot]](https://github.com/apps/github-actions), [@NeOMakinG](https://github.com/NeOMakinG), [@pablopolyte](https://github.com/pablopolyte), [@eternoendless](https://github.com/eternoendless), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@fabiovannini](https://github.com/fabiovannini), [@Progi1984](https://github.com/Progi1984), [@sowbiba](https://github.com/sowbiba), [@boubkerbribri](https://github.com/boubkerbribri), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@rakvium](https://github.com/rakvium), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
