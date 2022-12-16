---
layout: post
aliases: ["/news/coreweekly-14-2021"]
title:  "PrestaShop Core Weekly - Week 14 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-04-12
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 5th to Sunday 11th of April 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [54 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-04-05..2021-04-11) have been created in the project repositories;
- [44 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-04-05..2021-04-11), including [10 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-04-05..2021-04-11) on the core;
- [76 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-04-05..2021-04-11) in the project repositories;
- [54 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-04-05..2021-04-11), including [41 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-04-05..2021-04-11).
        


## Code changes in the 'develop' branch


### Core
* [#23834](https://github.com/PrestaShop/PrestaShop/pull/23834): Remove code related to CACHE_FILE_MODULES_LIST, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23742](https://github.com/PrestaShop/PrestaShop/pull/23742): Fixed the quantity calculation of packs when containing product variations. Thank you [@theodiablo](https://github.com/theodiablo)
* [#21751](https://github.com/PrestaShop/PrestaShop/pull/21751): Show out of stock label on listing pages : Configuration & Display in FrontOffice, by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#23967](https://github.com/PrestaShop/PrestaShop/pull/23967): Fix role in combination list, by [@jolelievre](https://github.com/jolelievre)
* [#23943](https://github.com/PrestaShop/PrestaShop/pull/23943): Improve compatibility in legacy code for new product_type field, by [@jolelievre](https://github.com/jolelievre)
* [#23921](https://github.com/PrestaShop/PrestaShop/pull/23921): Attributes list api for combinations filtering. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23913](https://github.com/PrestaShop/PrestaShop/pull/23913): Get categories tree query and endpoint. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23907](https://github.com/PrestaShop/PrestaShop/pull/23907): Enable header toolbar buttons to be disabled and use it for Add an Order, by [@matks](https://github.com/matks)
* [#23894](https://github.com/PrestaShop/PrestaShop/pull/23894): Multistore dropdown in configuration forms, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#23877](https://github.com/PrestaShop/PrestaShop/pull/23877): Refacto product command builder, by [@jolelievre](https://github.com/jolelievre)
* [#23856](https://github.com/PrestaShop/PrestaShop/pull/23856): Fix for issue where log controller would crash in dev mode. Declare variable severityMessage. Thank you [@Prestaworks](https://github.com/Prestaworks)
* [#23846](https://github.com/PrestaShop/PrestaShop/pull/23846): Fix options is undefined on right-sidebar of default theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23812](https://github.com/PrestaShop/PrestaShop/pull/23812): Edit combination modal, by [@jolelievre](https://github.com/jolelievre)
* [#23794](https://github.com/PrestaShop/PrestaShop/pull/23794): List attribute groups CQRS query using Doctrine EntityRepository, by [@jolelievre](https://github.com/jolelievre)
* [#23672](https://github.com/PrestaShop/PrestaShop/pull/23672): Add photoswipe to zoom on images on product page v2, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23330](https://github.com/PrestaShop/PrestaShop/pull/23330): New Product Page JavaScript model, by [@jolelievre](https://github.com/jolelievre)


### Front office
* [#23903](https://github.com/PrestaShop/PrestaShop/pull/23903): No image available in German: fix typo. Thank you [@lmeyer1](https://github.com/lmeyer1)
* [#23760](https://github.com/PrestaShop/PrestaShop/pull/23760): Fix uses of #fff instead of $white in the classic and new-theme scss, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23946](https://github.com/PrestaShop/PrestaShop/pull/23946): Separate error messages on Installation test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23938](https://github.com/PrestaShop/PrestaShop/pull/23938): Add some missing scenarios on customer block test. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23931](https://github.com/PrestaShop/PrestaShop/pull/23931): Add composer validate check to CI. Thank you [@mvorisek](https://github.com/mvorisek)


## Code changes in the '1.7.7.x' branch


### Core
* [#23925](https://github.com/PrestaShop/PrestaShop/pull/23925): Set locale to null when empty, by [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### Customer reassurance block module
* [#168](https://github.com/PrestaShop/blockreassurance/pull/168): Bump @babel/core from 7.13.14 to 7.13.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#167](https://github.com/PrestaShop/blockreassurance/pull/167): Bump mini-css-extract-plugin from 1.4.0 to 1.4.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#166](https://github.com/PrestaShop/blockreassurance/pull/166): Bump webpack from 5.30.0 to 5.31.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#396](https://github.com/PrestaShop/ps_facetedsearch/pull/396): Bump @babel/preset-env from 7.13.12 to 7.13.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#395](https://github.com/PrestaShop/ps_facetedsearch/pull/395): Bump @babel/core from 7.13.14 to 7.13.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#394](https://github.com/PrestaShop/ps_facetedsearch/pull/394): Bump webpack from 5.30.0 to 5.31.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#926](https://github.com/PrestaShop/docs/pull/926): Add `notice tips` override pdf tpls in module exemple. Thank you [@PululuK](https://github.com/PululuK)
* [#922](https://github.com/PrestaShop/docs/pull/922): Improve ` How to backup PrestaShop` doc. Thank you [@PululuK](https://github.com/PululuK)
* [#920](https://github.com/PrestaShop/docs/pull/920): Fix `actionOrderStatusPostUpdate` notice tips. Thank you [@PululuK](https://github.com/PululuK)
* [#919](https://github.com/PrestaShop/docs/pull/919): Improve `actionFrontControllerSetVariables` doc. Thank you [@PululuK](https://github.com/PululuK)
* [#918](https://github.com/PrestaShop/docs/pull/918): Fix little error in install-without-data image on How To Migrate to PrestaShop, by [@matks](https://github.com/matks)
* [#916](https://github.com/PrestaShop/docs/pull/916): Add `NumberMinMaxFilterType` code exemple. Thank you [@PululuK](https://github.com/PululuK)
* [#915](https://github.com/PrestaShop/docs/pull/915): Add `YesAndNoChoiceType` code exemple. Thank you [@PululuK](https://github.com/PululuK)
* [#914](https://github.com/PrestaShop/docs/pull/914): Add details about actionOrderStatusPostUpdate. Thank you [@RomainMazB](https://github.com/RomainMazB)


### User documentation landing page
* [#44](https://github.com/PrestaShop/user-documentation-landing/pull/44): fix(deps): bump core-js from 3.10.0 to 3.10.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Wire payment module
* [#61](https://github.com/PrestaShop/ps_wirepayment/pull/61): Bump prestashop/php-dev-tools from 3.4 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop Specifications
* [#207](https://github.com/PrestaShop/prestashop-specs/pull/207): Add specs for the order status page, by [@marionf](https://github.com/marionf)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@jolelievre](https://github.com/jolelievre), [@dependabot[bot]](https://github.com/apps/dependabot), [@PululuK](https://github.com/PululuK), [@eternoendless](https://github.com/eternoendless), [@boubkerbribri](https://github.com/boubkerbribri), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@mvorisek](https://github.com/mvorisek), [@atomiix](https://github.com/atomiix), [@zuk3975](https://github.com/zuk3975), [@matks](https://github.com/matks), [@lmeyer1](https://github.com/lmeyer1), [@matthieu-rolland](https://github.com/matthieu-rolland), [@RomainMazB](https://github.com/RomainMazB), [@PierreRambaud](https://github.com/PierreRambaud), [@Prestaworks](https://github.com/Prestaworks), [@NeOMakinG](https://github.com/NeOMakinG), [@theodiablo](https://github.com/theodiablo), [@marionf](https://github.com/marionf), [@Progi1984](https://github.com/Progi1984)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

