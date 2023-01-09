---
layout: post
aliases: ["/news/coreweekly-12-2021"]
title:  "PrestaShop Core Weekly - Week 12 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-03-29
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 22th to Sunday 28th of March 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear developers,

PrestaShop 1.7.7.3 is currently [being validated](https://github.com/PrestaShop/PrestaShop/issues/23465) by QA team.

Other releases are also expected to happen soon! [Email Alerts](https://github.com/PrestaShop/ps_emailalerts/pull/84) module v2.3.0 and [Share Buttons](https://github.com/PrestaShop/ps_sharebuttons/pull/49) module v2.1.1.

And the next public open source demo is going to happen on **next Wednesday [31st of March 2021, at 2pm CET](https://www.youtube.com/watch?v=UJ_XQs8trs4).**

The session will be kept in record on YouTube, so it can be watched later if this timeslot is not suitable for you.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [51 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-03-22..2021-03-28) have been created in the project repositories;
- [62 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-03-22..2021-03-28), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-03-22..2021-03-28) on the core;
- [63 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-03-22..2021-03-28) in the project repositories;
- [67 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-03-22..2021-03-28), including [50 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-03-22..2021-03-28).



## Code changes in the 'develop' branch


### Core
* [#23781](https://github.com/PrestaShop/PrestaShop/pull/23781): Updated JS Routing file. Thank you [@github-actions[bot]](https://github.com/apps/github-actions)


### Back office
* [#23752](https://github.com/PrestaShop/PrestaShop/pull/23752): Fixes issue with credit slip not downloading. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#23702](https://github.com/PrestaShop/PrestaShop/pull/23702): Introduce real product type field, by [@jolelievre](https://github.com/jolelievre)
* [#23687](https://github.com/PrestaShop/PrestaShop/pull/23687): Add Cover, Caption (with translation) and replace images to product v2 page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23684](https://github.com/PrestaShop/PrestaShop/pull/23684): Add sortable feature to product page v2 images dropzone, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23667](https://github.com/PrestaShop/PrestaShop/pull/23667): Product brand integration, by [@jolelievre](https://github.com/jolelievre)
* [#23581](https://github.com/PrestaShop/PrestaShop/pull/23581): Update combination inputs from list. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23292](https://github.com/PrestaShop/PrestaShop/pull/23292): Multistore header on migrated pages, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Front office
* [#23151](https://github.com/PrestaShop/PrestaShop/pull/23151): Remove microdata in html flow and replace by JSON-LD for classic theme. Thank you [@fdonnet](https://github.com/fdonnet)


### Installer
* [#23689](https://github.com/PrestaShop/PrestaShop/pull/23689): Change install demo datas string on install, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23543](https://github.com/PrestaShop/PrestaShop/pull/23543): BO password reset with maildev. Thank you [@SD1982](https://github.com/SD1982)


## Code changes in the '1.7.7.x' branch


### Core
* [#23722](https://github.com/PrestaShop/PrestaShop/pull/23722): Add missing license headers, by [@eternoendless](https://github.com/eternoendless)


### Front office
* [#23688](https://github.com/PrestaShop/PrestaShop/pull/23688): Fix display of color section on the add to cart modal on FO, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23740](https://github.com/PrestaShop/PrestaShop/pull/23740): Create message with only 35 characters for contact us test, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#907](https://github.com/PrestaShop/docs/pull/907): Remove pygments from GA workflow, by [@eternoendless](https://github.com/eternoendless)
* [#904](https://github.com/PrestaShop/docs/pull/904): Update hugo to 0.82, by [@eternoendless](https://github.com/eternoendless)
* [#903](https://github.com/PrestaShop/docs/pull/903): Add search tip, by [@eternoendless](https://github.com/eternoendless)
* [#900](https://github.com/PrestaShop/docs/pull/900): Update Localization Packs page, by [@matks](https://github.com/matks)
* [#893](https://github.com/PrestaShop/docs/pull/893): Update webservices information, by [@PierreRambaud](https://github.com/PierreRambaud)


### Currency selector
* [#24](https://github.com/PrestaShop/ps_currencyselector/pull/24): Migrated Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)
* [#23](https://github.com/PrestaShop/ps_currencyselector/pull/23): Bump prestashop/php-dev-tools from 2.2 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#22](https://github.com/PrestaShop/ps_currencyselector/pull/22): Bump friendsofphp/php-cs-fixer from 2.16.1 to 2.18.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer data privacy block module
* [#28](https://github.com/PrestaShop/ps_dataprivacy/pull/28): Fixed PHPStan, by [@Progi1984](https://github.com/Progi1984)
* [#27](https://github.com/PrestaShop/ps_dataprivacy/pull/27): Bump prestashop/php-dev-tools from 3.10 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#386](https://github.com/PrestaShop/ps_facetedsearch/pull/386): Added Coveralls, by [@Progi1984](https://github.com/Progi1984)
* [#385](https://github.com/PrestaShop/ps_facetedsearch/pull/385): Bump webpack from 5.27.2 to 5.28.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#384](https://github.com/PrestaShop/ps_facetedsearch/pull/384): Bump css-loader from 5.1.3 to 5.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#383](https://github.com/PrestaShop/ps_facetedsearch/pull/383): Bump @babel/preset-env from 7.13.10 to 7.13.12. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#382](https://github.com/PrestaShop/ps_facetedsearch/pull/382): Bump webpack from 5.27.1 to 5.27.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#381](https://github.com/PrestaShop/ps_facetedsearch/pull/381): Bump @babel/node from 7.13.10 to 7.13.12. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#379](https://github.com/PrestaShop/ps_facetedsearch/pull/379): Bump webpack from 5.26.3 to 5.27.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#40](https://github.com/PrestaShop/user-documentation-landing/pull/40): fix(deps): bump peaceiris/actions-gh-pages from v3 to v3.8.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Share Buttons module
* [#48](https://github.com/PrestaShop/ps_sharebuttons/pull/48): Bump version to 2.1.1. Thank you [@kpodemski](https://github.com/kpodemski)


### Customer reassurance block module
* [#156](https://github.com/PrestaShop/blockreassurance/pull/156): Bump webpack from 5.27.2 to 5.28.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#155](https://github.com/PrestaShop/blockreassurance/pull/155): Bump css-loader from 5.1.3 to 5.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#154](https://github.com/PrestaShop/blockreassurance/pull/154): Bump webpack from 5.27.1 to 5.27.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#153](https://github.com/PrestaShop/blockreassurance/pull/153): Bump webpack from 5.26.3 to 5.27.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#152](https://github.com/PrestaShop/blockreassurance/pull/152): Bump friendsofphp/php-cs-fixer from 2.18.2 to 2.18.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#79](https://github.com/PrestaShop/blockreassurance/pull/79): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Issues Bot
* [#14](https://github.com/PrestaShop/issuebot/pull/14): Change kanban names, by [@sowbiba](https://github.com/sowbiba)


### User documentation (Italian)
* [#2](https://github.com/PrestaShop/user-documentation-it/pull/2): Delete duplicate file, by [@Julievrz](https://github.com/Julievrz)


### Email Alerts module
* [#83](https://github.com/PrestaShop/ps_emailalerts/pull/83): Bump v2.3.0, by [@matks](https://github.com/matks)
* [#82](https://github.com/PrestaShop/ps_emailalerts/pull/82): Update README to add link for reporting bugs, by [@matks](https://github.com/matks)
* [#81](https://github.com/PrestaShop/ps_emailalerts/pull/81): Change prestashop compatibility version and add php-cs-fixer, by [@PierreRambaud](https://github.com/PierreRambaud)


### Cross-selling module
* [#26](https://github.com/PrestaShop/ps_crossselling/pull/26): Fixed PHPStan, by [@Progi1984](https://github.com/Progi1984)


### Auto Upgrade module
* [#391](https://github.com/PrestaShop/autoupgrade/pull/391): Wait For page to reload before putting it under maintenance on e2e tests, by [@boubkerbribri](https://github.com/boubkerbribri)


### Customer "Sign in" link module
* [#35](https://github.com/PrestaShop/ps_customersignin/pull/35): Hook module on reset. Thank you [@okom3pom](https://github.com/okom3pom)


### PrestaShop PHPStan extension
* [#23](https://github.com/PrestaShop/phpstan-prestashop/pull/23): Add extension into acceptance tests, by [@matks](https://github.com/matks)


### PrestaShop Specifications
* [#211](https://github.com/PrestaShop/prestashop-specs/pull/211): Multistore - edit specs for shop groups, by [@marionf](https://github.com/marionf)


## Where to start contributing?

What about [redirect a customer to product page or checkout after a successfull account creation](https://github.com/PrestaShop/PrestaShop/issues/18762)? This is a feature idea submitted 1 year ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@eternoendless](https://github.com/eternoendless), [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@github-actions[bot]](https://github.com/apps/github-actions), [@kpodemski](https://github.com/kpodemski), [@sowbiba](https://github.com/sowbiba), [@Julievrz](https://github.com/Julievrz), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@matks](https://github.com/matks), [@boubkerbribri](https://github.com/boubkerbribri), [@PierreRambaud](https://github.com/PierreRambaud), [@jolelievre](https://github.com/jolelievre), [@okom3pom](https://github.com/okom3pom), [@NeOMakinG](https://github.com/NeOMakinG), [@marionf](https://github.com/marionf), [@zuk3975](https://github.com/zuk3975), [@SD1982](https://github.com/SD1982), [@matthieu-rolland](https://github.com/matthieu-rolland), [@fdonnet](https://github.com/fdonnet)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
