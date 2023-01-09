---
layout: post
aliases: ["/news/coreweekly-18-2020"]
title:  "PrestaShop Core Weekly - Week 18 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-05-11
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 27th of April to Sunday 03rd of May 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [95 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-04-27..2020-05-03) have been created in the project repositories;
- [53 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-04-27..2020-05-03), including [13 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-04-27..2020-05-03) on the core;
- [58 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-04-27..2020-05-03) in the project repositories;
- [55 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-04-27..2020-05-03), including [46 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-04-27..2020-05-03).
        


## Code changes in the 'develop' branch


### Core
* [#18736](https://github.com/PrestaShop/PrestaShop/pull/18736): Address State field drop down is ordered by ID, instead of State Name. Thank you [@PululuK](https://github.com/PululuK)
* [#18531](https://github.com/PrestaShop/PrestaShop/pull/18531): Remove irrelevant die() and throw exception instead, by [@matks](https://github.com/matks)


### Back office
* [#18757](https://github.com/PrestaShop/PrestaShop/pull/18757): [BO] Fix bug on type='color' in renderOption. Thank you [@ramtin2025](https://github.com/ramtin2025)
* [#18184](https://github.com/PrestaShop/PrestaShop/pull/18184): Rework help-box making it reusable and more maintenable by regrouping markups, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17818](https://github.com/PrestaShop/PrestaShop/pull/17818): Suggest to have at least 2 payment methods, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch


### Core
* [#18851](https://github.com/PrestaShop/PrestaShop/pull/18851): Build assets for Beta, by [@jolelievre](https://github.com/jolelievre)
* [#18845](https://github.com/PrestaShop/PrestaShop/pull/18845): Add tag controller.service_arguments to PrestaShop controllers, by [@matks](https://github.com/matks)
* [#18201](https://github.com/PrestaShop/PrestaShop/pull/18201): Optimize the 1.7.7 translation catalog, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#18812](https://github.com/PrestaShop/PrestaShop/pull/18812): Fix invoices refresh when adding product in an order, by [@atomiix](https://github.com/atomiix)
* [#18580](https://github.com/PrestaShop/PrestaShop/pull/18580): In BO Product page, use ecotax excl. tax instead of tax incl., by [@matks](https://github.com/matks)
* [#17179](https://github.com/PrestaShop/PrestaShop/pull/17179): Fix free gift product in Order create page. Thank you [@zuk3975](https://github.com/zuk3975)


### Installer
* [#18834](https://github.com/PrestaShop/PrestaShop/pull/18834): Remove newsletter registration during installation, by [@PierreRambaud](https://github.com/PierreRambaud)


### Web services
* [#18859](https://github.com/PrestaShop/PrestaShop/pull/18859): Defined Currency Context if needed in WebService Context, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#18922](https://github.com/PrestaShop/PrestaShop/pull/18922): Functional tests - Delete not working test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18878](https://github.com/PrestaShop/PrestaShop/pull/18878): Functional tests - Change selectors for international pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18873](https://github.com/PrestaShop/PrestaShop/pull/18873): Functional tests - Change selectors for customers pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18870](https://github.com/PrestaShop/PrestaShop/pull/18870): Functional tests - Change selectors for customer services pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18866](https://github.com/PrestaShop/PrestaShop/pull/18866): Functional tests - Fix adding customer to voucher, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18862](https://github.com/PrestaShop/PrestaShop/pull/18862): Functional tests - Change selectors for shop parameters pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18849](https://github.com/PrestaShop/PrestaShop/pull/18849): Functional tests - Change selectors for catalog pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18843](https://github.com/PrestaShop/PrestaShop/pull/18843): Functional tests - Create edit view voucher in customer information page. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18840](https://github.com/PrestaShop/PrestaShop/pull/18840): Functional tests - Change selectors for advanced params pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18832](https://github.com/PrestaShop/PrestaShop/pull/18832): Functional tests - Change selectors orders pages, by [@boubkerbribri](https://github.com/boubkerbribri)


### Merge
* [#18836](https://github.com/PrestaShop/PrestaShop/pull/18836): Merge 1765 to 177, by [@sowbiba](https://github.com/sowbiba)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#523](https://github.com/PrestaShop/docs/pull/523): Initial form value improvement. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#520](https://github.com/PrestaShop/docs/pull/520): Replace http with https for README urls, by [@matks](https://github.com/matks)
* [#518](https://github.com/PrestaShop/docs/pull/518): Add note on strict typing, by [@eternoendless](https://github.com/eternoendless)
* [#517](https://github.com/PrestaShop/docs/pull/517): Replace gitter with Slack, by [@matks](https://github.com/matks)
* [#515](https://github.com/PrestaShop/docs/pull/515): Webservers. Thank you [@djodjo3](https://github.com/djodjo3)
* [#514](https://github.com/PrestaShop/docs/pull/514): Fix typo. Thank you [@aunhappy](https://github.com/aunhappy)
* [#506](https://github.com/PrestaShop/docs/pull/506): Updating scale section. Thank you [@djodjo3](https://github.com/djodjo3)
* [#501](https://github.com/PrestaShop/docs/pull/501): Update core changes for 1.7.7, by [@eternoendless](https://github.com/eternoendless)


### Theme customization
* [#26](https://github.com/PrestaShop/ps_themecusto/pull/26): Release 1.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25](https://github.com/PrestaShop/ps_themecusto/pull/25): Bump version to 1.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### The PrestaShop open source project
* [#35](https://github.com/PrestaShop/open-source/pull/35): Some fixes for slack Channels page, by [@matks](https://github.com/matks)
* [#34](https://github.com/PrestaShop/open-source/pull/34): Some fixes for slack README, by [@matks](https://github.com/matks)


### docker-templates
* [#7](https://github.com/PrestaShop/docker-templates/pull/7): New apache2 phpfpm stack. Thank you [@djodjo3](https://github.com/djodjo3)


### Wishlist block
* [#33](https://github.com/PrestaShop/blockwishlist/pull/33): Add wishlist lists page, styling it, add prettier and share modal, by [@NeOMakinG](https://github.com/NeOMakinG)


### Classic-rocket theme
* [#153](https://github.com/PrestaShop/classic-rocket/pull/153): add linkedin to compatible with new ps_socialfollow module. Thank you [@dosbiner](https://github.com/dosbiner)


### PrestaShop Specifications
* [#108](https://github.com/PrestaShop/prestashop-specs/pull/108): Create multistores specials cases specs, by [@marionf](https://github.com/marionf)
* [#104](https://github.com/PrestaShop/prestashop-specs/pull/104): Create specs to setup multistore, by [@marionf](https://github.com/marionf)


### mjml-theme-converter
* [#4](https://github.com/PrestaShop/mjml-theme-converter/pull/4): Add password generation link to guest_to_customer template, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### live-demo-devices
* [#4](https://github.com/PrestaShop/live-demo-devices/pull/4): Switch project on VueJS, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@jf-viguier](https://github.com/jf-viguier), [@boubkerbribri](https://github.com/boubkerbribri), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@PierreRambaud](https://github.com/PierreRambaud), [@Progi1984](https://github.com/Progi1984), [@jolelievre](https://github.com/jolelievre), [@ttoine](https://github.com/ttoine), [@djodjo3](https://github.com/djodjo3), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@sowbiba](https://github.com/sowbiba), [@aunhappy](https://github.com/aunhappy), [@atomiix](https://github.com/atomiix), [@NeOMakinG](https://github.com/NeOMakinG), [@ramtin2025](https://github.com/ramtin2025), [@PululuK](https://github.com/PululuK), [@dosbiner](https://github.com/dosbiner), [@shaffe-fr](https://github.com/shaffe-fr), [@marionf](https://github.com/marionf), [@matthieu-rolland](https://github.com/matthieu-rolland), [@zuk3975](https://github.com/zuk3975), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
