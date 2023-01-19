---
layout: post
aliases: ["/news/coreweekly-35-2020"]
title:  "PrestaShop Core Weekly - Week 35 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-08-31
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 24th to Sunday 30th of August 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

The [1.7.7.0 Beta 2 build](https://github.com/PrestaShop/PrestaShop/issues/18647#issuecomment-672940163) has been validated by QA team. The test campaign contained 414 manual tests, and
- 90% are successfull (373)
- 3% cannot be run in current context (blocked) (12)
- 7% are failing (29)

Since the 7% failing tests are not blocking issues, we will be able to deliver the build publicly and open the second beta period for 1.7.7.0.

_Update: The beta 2 build [has been delivered](https://build.prestashop.com/news/prestashop-1-7-7-0-beta2-release/) as scheduled!_


## A quick update about PrestaShop's GitHub issues and pull requests:

- [75 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-08-24..2020-08-30) have been created in the project repositories;
- [74 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-08-24..2020-08-30), including [16 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-08-24..2020-08-30) on the core;
- [73 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-08-24..2020-08-30) in the project repositories;
- [63 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-08-24..2020-08-30), including [52 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-08-24..2020-08-30).



## Code changes in the 'develop' branch


### Core
* [#20717](https://github.com/PrestaShop/PrestaShop/pull/20717): Fix private final method. Thank you [@mvorisek](https://github.com/mvorisek)
* [#18787](https://github.com/PrestaShop/PrestaShop/pull/18787): Add compatibility to PHP 7.4, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#20742](https://github.com/PrestaShop/PrestaShop/pull/20742):  Add $delta_quantity to hookActionUpdateQuantity(). Thank you [@Sinepel](https://github.com/Sinepel)
* [#20554](https://github.com/PrestaShop/PrestaShop/pull/20554): Add manufacturer to UpdateProductBasicInformationCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20106](https://github.com/PrestaShop/PrestaShop/pull/20106): Multistore: assign a color to a shop, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Front office
* [#20721](https://github.com/PrestaShop/PrestaShop/pull/20721): Add property free_shipping to presented cart to ease FO usage. Thank you [@awitkutarahil](https://github.com/awitkutarahil)


### Installer
* [#20711](https://github.com/PrestaShop/PrestaShop/pull/20711): Display more info when cli install fails. Thank you [@mvorisek](https://github.com/mvorisek)


## Code changes in the '1.7.7.x' branch


### Core
* [#20758](https://github.com/PrestaShop/PrestaShop/pull/20758): fix cumulative percentage behat test, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#20755](https://github.com/PrestaShop/PrestaShop/pull/20755): Fix free shipping cart rules not added/deleted in create order, by [@atomiix](https://github.com/atomiix)
* [#20729](https://github.com/PrestaShop/PrestaShop/pull/20729): Fix price width is too small on some devices by setting a min-width, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20684](https://github.com/PrestaShop/PrestaShop/pull/20684): Fix empty optional customization exception when creating BO order, by [@atomiix](https://github.com/atomiix)
* [#20145](https://github.com/PrestaShop/PrestaShop/pull/20145): Product management and specific prices new rules in Order, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#20759](https://github.com/PrestaShop/PrestaShop/pull/20759): Add test 'Bulk delete attributes', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20749](https://github.com/PrestaShop/PrestaShop/pull/20749): Add tests 'Filter features' and 'Filter feature values', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20735](https://github.com/PrestaShop/PrestaShop/pull/20735): Add test 'CRUD attributes and values', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20724](https://github.com/PrestaShop/PrestaShop/pull/20724): Add test  'Default pack stock management'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#20692](https://github.com/PrestaShop/PrestaShop/pull/20692): Add tests 'Filter attributes' and 'Filter attribute values', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20683](https://github.com/PrestaShop/PrestaShop/pull/20683): Fix faker data - Title's name should take at most 20 characters , by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#691](https://github.com/PrestaShop/docs/pull/691): Add link to `_legacy_link` description. Thank you [@likemusic](https://github.com/likemusic)
* [#690](https://github.com/PrestaShop/docs/pull/690): Allow installation of Hugo's mac os version via install script, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#689](https://github.com/PrestaShop/docs/pull/689): Fix some links, by [@matks](https://github.com/matks)
* [#686](https://github.com/PrestaShop/docs/pull/686): Add a page to explain the UIKit use, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#685](https://github.com/PrestaShop/docs/pull/685): Scrollable tables. Thank you [@likemusic](https://github.com/likemusic)
* [#684](https://github.com/PrestaShop/docs/pull/684): Add docker-compose.yml. Thank you [@likemusic](https://github.com/likemusic)
* [#682](https://github.com/PrestaShop/docs/pull/682): Fix add() definition according to source phpDoc. Thank you [@likemusic](https://github.com/likemusic)
* [#681](https://github.com/PrestaShop/docs/pull/681): Remove unnecessary spaces which lead to code tag. Thank you [@likemusic](https://github.com/likemusic)
* [#680](https://github.com/PrestaShop/docs/pull/680): Fix misprint. Thank you [@likemusic](https://github.com/likemusic)
* [#679](https://github.com/PrestaShop/docs/pull/679): Correct typo on getting started part. Thank you [@Farelion](https://github.com/Farelion)
* [#678](https://github.com/PrestaShop/docs/pull/678): Fix out of place question mark using. Thank you [@likemusic](https://github.com/likemusic)
* [#677](https://github.com/PrestaShop/docs/pull/677): Fix incorrect terms usage. Сlarify using `dump()`. Thank you [@likemusic](https://github.com/likemusic)
* [#676](https://github.com/PrestaShop/docs/pull/676): Fix server name from `Nginx` to `Apache`. Thank you [@likemusic](https://github.com/likemusic)
* [#675](https://github.com/PrestaShop/docs/pull/675): Fix path to download-links.png in localhost.md. Thank you [@likemusic](https://github.com/likemusic)
* [#672](https://github.com/PrestaShop/docs/pull/672): Fix hardcoded link, by [@matks](https://github.com/matks)
* [#669](https://github.com/PrestaShop/docs/pull/669): Mention we need rebases, not merges, for PRs, by [@matks](https://github.com/matks)


### Google Analytics module
* [#69](https://github.com/PrestaShop/ps_googleanalytics/pull/69): Improve README, by [@matks](https://github.com/matks)


### PrestonBot
* [#99](https://github.com/PrestaShop/prestonbot/pull/99): Improve wordings, by [@eternoendless](https://github.com/eternoendless)
* [#98](https://github.com/PrestaShop/prestonbot/pull/98): Allow to have dot in Fixed ticket section, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#97](https://github.com/PrestaShop/prestonbot/pull/97): Allows no related ticket when category is TE, by [@atomiix](https://github.com/atomiix)
* [#96](https://github.com/PrestaShop/prestonbot/pull/96): Add a comment when a PR has been validated (QA ✔) but no milestone is defined, by [@atomiix](https://github.com/atomiix)


### Wishlist block module
* [#82](https://github.com/PrestaShop/blockwishlist/pull/82): add combination field to stats grid. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#81](https://github.com/PrestaShop/blockwishlist/pull/81): add verification before adding product. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#80](https://github.com/PrestaShop/blockwishlist/pull/80): switch the request. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#79](https://github.com/PrestaShop/blockwishlist/pull/79): Add wl hook. Thank you [@pablopolyte](https://github.com/pablopolyte)


### PrestaShop Specifications
* [#131](https://github.com/PrestaShop/prestashop-specs/pull/131): Add specs for the payment link, by [@marionf](https://github.com/marionf)
* [#130](https://github.com/PrestaShop/prestashop-specs/pull/130): Add specs for free shipping cart rule, by [@marionf](https://github.com/marionf)
* [#129](https://github.com/PrestaShop/prestashop-specs/pull/129): Add specs for order message, by [@marionf](https://github.com/marionf)
* [#128](https://github.com/PrestaShop/prestashop-specs/pull/128): Add and update error messages, by [@marionf](https://github.com/marionf)
* [#126](https://github.com/PrestaShop/prestashop-specs/pull/126): Add specs for address edition, by [@marionf](https://github.com/marionf)


### Quality Assurance module
* [#3](https://github.com/PrestaShop/ps_qualityassurance/pull/3): Enable 'Configure' Link from Modules page, by [@matks](https://github.com/matks)


### Architecture Decision Records repository
* [#12](https://github.com/PrestaShop/ADR/pull/12): 0009 - Expose js core modules to the window object to provide an interface to every developers, by [@NeOMakinG](https://github.com/NeOMakinG)


### Email Alerts module
* [#49](https://github.com/PrestaShop/ps_emailalerts/pull/49): Adapt translation domains to the new translation system. Thank you [@dali-rajab](https://github.com/dali-rajab)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@likemusic](https://github.com/likemusic), [@matthieu-rolland](https://github.com/matthieu-rolland), [@matks](https://github.com/matks), [@boubkerbribri](https://github.com/boubkerbribri), [@atomiix](https://github.com/atomiix), [@NeOMakinG](https://github.com/NeOMakinG), [@Sinepel](https://github.com/Sinepel), [@eternoendless](https://github.com/eternoendless), [@PierreRambaud](https://github.com/PierreRambaud), [@pablopolyte](https://github.com/pablopolyte), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@awitkutarahil](https://github.com/awitkutarahil), [@mvorisek](https://github.com/mvorisek), [@marionf](https://github.com/marionf), [@Farelion](https://github.com/Farelion), [@zuk3975](https://github.com/zuk3975), [@jolelievre](https://github.com/jolelievre), [@dali-rajab](https://github.com/dali-rajab), [@olecorre](https://github.com/olecorre)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
