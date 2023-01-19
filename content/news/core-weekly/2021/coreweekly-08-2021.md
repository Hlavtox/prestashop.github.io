---
layout: post
aliases: ["/news/coreweekly-08-2021"]
title:  "PrestaShop Core Weekly - Week 8 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-03-02
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 22th to Sunday 28th of February 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Last week, the maintainers team held again a video conferencing for the project public demonstrations session, streamed live on [YouTube](https://youtu.be/JBvJgoo-rLg).

The version 2.0.0 of module blockwishlist is now [complete](https://github.com/PrestaShop/blockwishlist/pull/77). This is a wide rework of the module capacities and codebase, and it will be compatible with PrestaShop 1.7.6 and newer versions.

The release has not been done yet and should follow soon.

Finally the kanban for `1.7.7` branch is not empty yet, it still contains unresolved regressions reported on versions 1.7.7.0 and 1.7.7.1. The next batch of bugfixes for 1.7.7 will be delivered in patch version 1.7.7.3, which is scheduled to be delivered within [the next 6 weeks](https://devdocs.prestashop.com/1.7/project/release/minor-release-lifecycle/).


## A quick update about PrestaShop's GitHub issues and pull requests:

- [85 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-02-22..2021-02-28) have been created in the project repositories;
- [69 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-02-22..2021-02-28), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-02-22..2021-02-28) on the core;
- [74 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-02-22..2021-02-28) in the project repositories;
- [77 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-02-22..2021-02-28), including [68 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-02-22..2021-02-28).



## Code changes in the 'develop' branch


### Core
* [#23310](https://github.com/PrestaShop/PrestaShop/pull/23310): Remove unusable code in OrderSlip::getOrdersSlipProducts(). Thank you [@PululuK](https://github.com/PululuK)
* [#23295](https://github.com/PrestaShop/PrestaShop/pull/23295): Update Smarty to v3.1.39, by [@matks](https://github.com/matks)
* [#23269](https://github.com/PrestaShop/PrestaShop/pull/23269): Fix nightly autoupgrade - issue with Cookie destruction, by [@atomiix](https://github.com/atomiix)


### Back office
* [#23374](https://github.com/PrestaShop/PrestaShop/pull/23374): BO: Remove unused variable. Thank you [@idnovate](https://github.com/idnovate)
* [#23363](https://github.com/PrestaShop/PrestaShop/pull/23363): Implement DeleteVirtualProductFile command. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23362](https://github.com/PrestaShop/PrestaShop/pull/23362): Modify namespace related to VirtualProductFile. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23293](https://github.com/PrestaShop/PrestaShop/pull/23293): Improve naming of the Hook Collector in Symfony debug bar, by [@matks](https://github.com/matks)
* [#23223](https://github.com/PrestaShop/PrestaShop/pull/23223): Update TinyMCE and some plugins to 4.9.11, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23105](https://github.com/PrestaShop/PrestaShop/pull/23105): Refacto notification and user pan on mobile, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21553](https://github.com/PrestaShop/PrestaShop/pull/21553): Simplify email form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Front office
* [#23353](https://github.com/PrestaShop/PrestaShop/pull/23353): Fix classic theme images width, accessibilty and some lighthouse improvements, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23309](https://github.com/PrestaShop/PrestaShop/pull/23309): Add ID field in global template vars. Thank you [@PululuK](https://github.com/PululuK)


### Installer
* [#20843](https://github.com/PrestaShop/PrestaShop/pull/20843): Fix maximum compatible PHP version and error wordings, by [@eternoendless](https://github.com/eternoendless)


### Tests
* [#23408](https://github.com/PrestaShop/PrestaShop/pull/23408): Fix Log test and delete duplicated identifiers in Nightly, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23385](https://github.com/PrestaShop/PrestaShop/pull/23385): Fix sanity tests on GA, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23375](https://github.com/PrestaShop/PrestaShop/pull/23375): Fix nightly errrors- Fix Password reminder test on FO, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22932](https://github.com/PrestaShop/PrestaShop/pull/22932): FO password reminder test with maildev. Thank you [@SD1982](https://github.com/SD1982)
* [#22902](https://github.com/PrestaShop/PrestaShop/pull/22902): Adding address grid test. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


## Code changes in the '1.7.7.x' branch


### Core
* [#23343](https://github.com/PrestaShop/PrestaShop/pull/23343): Make autoloader suffix reproducible, by [@atomiix](https://github.com/atomiix)


### Back office
* [#23142](https://github.com/PrestaShop/PrestaShop/pull/23142): Check if an order status has the same name in Add/Edit, by [@Progi1984](https://github.com/Progi1984)
* [#23040](https://github.com/PrestaShop/PrestaShop/pull/23040): Fixed missing DNI Number in BackOffice Order View, by [@Progi1984](https://github.com/Progi1984)
* [#22920](https://github.com/PrestaShop/PrestaShop/pull/22920): Prevent adding out of stock products in Create order page, by [@Progi1984](https://github.com/Progi1984)
* [#22791](https://github.com/PrestaShop/PrestaShop/pull/22791): BO - Order Page - Set an error message when the payment method is invalid, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#23410](https://github.com/PrestaShop/PrestaShop/pull/23410): Fix nightly 25/02/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23382](https://github.com/PrestaShop/PrestaShop/pull/23382): Fix nightly - Add reset Step in 'Default Pack Stock Management'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23359](https://github.com/PrestaShop/PrestaShop/pull/23359): Fix nightly errrors - Delete duplicates on selectors names, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23238](https://github.com/PrestaShop/PrestaShop/pull/23238): Add test - Quick view product on FO. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#875](https://github.com/PrestaShop/docs/pull/875): Fixed CI, by [@Progi1984](https://github.com/Progi1984)
* [#874](https://github.com/PrestaShop/docs/pull/874): Fixed Build CI, by [@Progi1984](https://github.com/Progi1984)
* [#873](https://github.com/PrestaShop/docs/pull/873): Improve render of WebServices table, by [@Progi1984](https://github.com/Progi1984)
* [#869](https://github.com/PrestaShop/docs/pull/869): Little improvements for nginx config, by [@matks](https://github.com/matks)
* [#867](https://github.com/PrestaShop/docs/pull/867): Migrate Travis CI to GitHub Actions, by [@Progi1984](https://github.com/Progi1984)


### Customer reassurance block module
* [#139](https://github.com/PrestaShop/blockreassurance/pull/139): Bump css-loader from 5.0.2 to 5.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#138](https://github.com/PrestaShop/blockreassurance/pull/138): Bump mini-css-extract-plugin from 1.3.8 to 1.3.9. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#137](https://github.com/PrestaShop/blockreassurance/pull/137): Bump webpack from 5.24.1 to 5.24.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#136](https://github.com/PrestaShop/blockreassurance/pull/136): Bump webpack from 5.24.0 to 5.24.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#135](https://github.com/PrestaShop/blockreassurance/pull/135): Bump webpack from 5.23.0 to 5.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#134](https://github.com/PrestaShop/blockreassurance/pull/134): Bump @babel/core from 7.12.17 to 7.13.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#350](https://github.com/PrestaShop/ps_facetedsearch/pull/350): Bump css-loader from 5.0.2 to 5.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#349](https://github.com/PrestaShop/ps_facetedsearch/pull/349): Bump webpack from 5.24.1 to 5.24.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#348](https://github.com/PrestaShop/ps_facetedsearch/pull/348): Bump mockery/mockery from 1.3.3 to 1.3.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#347](https://github.com/PrestaShop/ps_facetedsearch/pull/347): Bump @babel/preset-env from 7.13.0 to 7.13.5. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#346](https://github.com/PrestaShop/ps_facetedsearch/pull/346): Bump webpack from 5.24.0 to 5.24.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#345](https://github.com/PrestaShop/ps_facetedsearch/pull/345): Bump webpack from 5.23.0 to 5.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#344](https://github.com/PrestaShop/ps_facetedsearch/pull/344): Bump @babel/cli from 7.12.17 to 7.13.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#343](https://github.com/PrestaShop/ps_facetedsearch/pull/343): Bump @babel/register from 7.12.13 to 7.13.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#342](https://github.com/PrestaShop/ps_facetedsearch/pull/342): Bump @babel/preset-env from 7.12.17 to 7.13.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#341](https://github.com/PrestaShop/ps_facetedsearch/pull/341): Bump @babel/core from 7.12.17 to 7.13.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#340](https://github.com/PrestaShop/ps_facetedsearch/pull/340): Bump @babel/node from 7.12.17 to 7.13.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop PHPStan extension
* [#10](https://github.com/PrestaShop/phpstan-prestashop/pull/10): Refactor tests/data folder, by [@matks](https://github.com/matks)


### Product Comments module
* [#98](https://github.com/PrestaShop/productcomments/pull/98): Bump simplePagination.js from `e32c66e` to `da97104`. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#34](https://github.com/PrestaShop/user-documentation-landing/pull/34): chore(deps-dev): bump eslint-config-prettier from 8.0.0 to 8.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#33](https://github.com/PrestaShop/user-documentation-landing/pull/33): fix(deps): bump nuxt from 2.15.1 to 2.15.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#32](https://github.com/PrestaShop/user-documentation-landing/pull/32): fix(deps): bump actions/setup-node from v2.1.2 to v2.1.5. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#31](https://github.com/PrestaShop/user-documentation-landing/pull/31): chore(deps-dev): bump eslint-config-prettier from 6.15.0 to 8.0.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#30](https://github.com/PrestaShop/user-documentation-landing/pull/30): fix(deps): bump nuxt from 2.15.0 to 2.15.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Docker images
* [#255](https://github.com/PrestaShop/docker/pull/255): Release 1772, by [@matks](https://github.com/matks)


### PrestaShop modules registry
* [#444](https://github.com/PrestaShop/PrestaShop-modules/pull/444): Remove modules, by [@Progi1984](https://github.com/Progi1984)


### Decimal
* [#14](https://github.com/PrestaShop/decimal/pull/14): Added Build Workflow for Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Prestashop UI Kit
* [#137](https://github.com/PrestaShop/prestashop-ui-kit/pull/137): Fix radio buttons html validations, by [@NeOMakinG](https://github.com/NeOMakinG)


### Custom text module
* [#53](https://github.com/PrestaShop/ps_customtext/pull/53): Implement call to hook filterHtmlContent on modules HTML. Thank you [@elburgl69](https://github.com/elburgl69)


### PrestaShop Specifications
* [#189](https://github.com/PrestaShop/prestashop-specs/pull/189): Create Your-vouchers.md. Thank you [@MatShir](https://github.com/MatShir)
* [#102](https://github.com/PrestaShop/prestashop-specs/pull/102): Blockwishlist functional specifications. Thank you [@lolath-presta](https://github.com/lolath-presta)


### GDPR module
* [#106](https://github.com/PrestaShop/psgdpr/pull/106): Improve logs table performances. Thank you [@PululuK](https://github.com/PululuK)


### Wishlist block module
* [#77](https://github.com/PrestaShop/blockwishlist/pull/77): Introduce new version of blockwishlist module compatible with PS 1.7, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Main menu module
* [#36](https://github.com/PrestaShop/ps_mainmenu/pull/36): Removed condition to display thumb. Thank you [@mikayilsrt](https://github.com/mikayilsrt)


## Where to start contributing?

What about improving [how notifications in the Back Office](https://github.com/PrestaShop/PrestaShop/issues/9550) are marked 'read' ? This is a bug report submitted three years ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@boubkerbribri](https://github.com/boubkerbribri), [@matks](https://github.com/matks), [@PierreRambaud](https://github.com/PierreRambaud), [@idnovate](https://github.com/idnovate), [@zuk3975](https://github.com/zuk3975), [@NeOMakinG](https://github.com/NeOMakinG), [@atomiix](https://github.com/atomiix), [@PululuK](https://github.com/PululuK), [@SD1982](https://github.com/SD1982), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@elburgl69](https://github.com/elburgl69), [@MatShir](https://github.com/MatShir), [@eternoendless](https://github.com/eternoendless), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@mikayilsrt](https://github.com/mikayilsrt), [@lolath-presta](https://github.com/lolath-presta)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
