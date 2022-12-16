---
layout: post
aliases: ["/news/coreweekly-29-2021"]
title:  "PrestaShop Core Weekly - Week 29 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-07-27
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 19th to Sunday 25th of July 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

In case you missed it, _we moved the next Public OSS Demo session date_ to [**Wednesday, August 4, 2021 at 4pm CEST**](https://www.youtube.com/watch?v=pE6lVtdsIhE). We noticed that 2pm CEST was a little early in the morning for people watching us live from the Americas, so we decided that future sessions will start two hours later — at 4pm. We hope this will encourage more of our community to watch the demo live and discuss with us :smile:

Also we are really proud to announce that [PrestaShop Core is compatible with PHP 8.0](https://github.com/PrestaShop/PrestaShop/pull/25296) in the `develop` branch thanks to [@atomiix](https://github.com/atomiix). The full project is not entirely compliant with PHP 8 yet (some modules need dependencies updates) but this is a major milestone for PrestaShop, just in time to greet [the first beta of PHP 8.1](https://www.php.net/archive/2021.php#2021-07-22-1) that was released on July 22!


## Releases

* [TranslationToolsBundle](https://github.com/PrestaShop/TranslationToolsBundle): [v5.0.0](https://github.com/PrestaShop/TranslationToolsBundle/releases/tag/v5.0.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [37 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-07-19..2021-07-25) have been created in the project repositories;
- [43 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-07-19..2021-07-25), including [9 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-07-19..2021-07-25) on the core;
- [47 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-07-19..2021-07-25) in the project repositories;
- [78 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-07-19..2021-07-25), including [65 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-07-19..2021-07-25).



## Code changes in the 'develop' branch


### Core
* [#25410](https://github.com/PrestaShop/PrestaShop/pull/25410): Make sure order variable exists and also return the order_list variable in actionValidateOrderAfter hook, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25391](https://github.com/PrestaShop/PrestaShop/pull/25391): Fixed PHPDoc, by [@Progi1984](https://github.com/Progi1984)
* [#25296](https://github.com/PrestaShop/PrestaShop/pull/25296): Make PrestaShop compatible with PHP 8.0, by [@atomiix](https://github.com/atomiix)
* [#25212](https://github.com/PrestaShop/PrestaShop/pull/25212): Fixed typo `Country.php`. Thank you [@Arnaud104](https://github.com/Arnaud104)
* [#23798](https://github.com/PrestaShop/PrestaShop/pull/23798): Replace ProductInterface occurences by RedirectType. Thank you [@Sinepel](https://github.com/Sinepel)


### Back office
* [#25295](https://github.com/PrestaShop/PrestaShop/pull/25295): Allow enable/disable selection for customers in Customer Groups, by [@Progi1984](https://github.com/Progi1984)
* [#25169](https://github.com/PrestaShop/PrestaShop/pull/25169): Cart rule category selection : display categories in a hierarchical way. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Front office
* [#25210](https://github.com/PrestaShop/PrestaShop/pull/25210): Add download link when an order have 2 product type virtual and normal. Thank you [@okom3pom](https://github.com/okom3pom)


### Tests
* [#25411](https://github.com/PrestaShop/PrestaShop/pull/25411): Use only one file for sanity, remove sanity-80.yml, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25403](https://github.com/PrestaShop/PrestaShop/pull/25403): Fixed Unit Tests, by [@Progi1984](https://github.com/Progi1984)
* [#25325](https://github.com/PrestaShop/PrestaShop/pull/25325): Allow GitHub UI tests to run on branch push, by [@matks](https://github.com/matks)


## Code changes in the '1.7.8.x' branch


### Back office
* [#25364](https://github.com/PrestaShop/PrestaShop/pull/25364): Fix inputs prefilling bug when a combination is added to an order, by [@jolelievre](https://github.com/jolelievre)
* [#25038](https://github.com/PrestaShop/PrestaShop/pull/25038): Fix TinyMCE max length computing in BO, by [@jolelievre](https://github.com/jolelievre)
* [#24620](https://github.com/PrestaShop/PrestaShop/pull/24620): No email check in  BO > Advanced Parameters > Logs page. Thank you [@okom3pom](https://github.com/okom3pom)


### Front office
* [#25316](https://github.com/PrestaShop/PrestaShop/pull/25316): Fix blocking add to cart button. Thank you [@kpodemski](https://github.com/kpodemski)


### Tests
* [#25365](https://github.com/PrestaShop/PrestaShop/pull/25365): Re-enable Behat test about product duplicate translation, by [@matks](https://github.com/matks)
* [#25341](https://github.com/PrestaShop/PrestaShop/pull/25341): Functional tests - Refacto modules and design tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25320](https://github.com/PrestaShop/PrestaShop/pull/25320): Fix languages test install, by [@jolelievre](https://github.com/jolelievre)
* [#25259](https://github.com/PrestaShop/PrestaShop/pull/25259): Functional tests - Refacto attributes and features tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25250](https://github.com/PrestaShop/PrestaShop/pull/25250): Functional tests - Refacto monitoring tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25249](https://github.com/PrestaShop/PrestaShop/pull/25249): Create more order statuses to allow pagination, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25233](https://github.com/PrestaShop/PrestaShop/pull/25233): Functional tests - Refacto categories tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25219](https://github.com/PrestaShop/PrestaShop/pull/25219): Functional tests - Refacto products tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25201](https://github.com/PrestaShop/PrestaShop/pull/25201): Functional tests - (Refacto) Delete 'uppercaseFirstCharacter()' method. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25171](https://github.com/PrestaShop/PrestaShop/pull/25171): Functional tests - Refacto login tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25167](https://github.com/PrestaShop/PrestaShop/pull/25167): Functional tests - CRUD cart rule with/without code. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25150](https://github.com/PrestaShop/PrestaShop/pull/25150): Fix pagination condition on shopping cart test, by [@boubkerbribri](https://github.com/boubkerbribri)



## Code changes in the '1.7.7.x' branch


### Back office
* [#25378](https://github.com/PrestaShop/PrestaShop/pull/25378): Order Product Search: Limit only if the search phrase length is greater than 2 characters and HTTP Code Error become a 400, by [@Progi1984](https://github.com/Progi1984)
* [#25375](https://github.com/PrestaShop/PrestaShop/pull/25375): In Order view, set the lang of the order for order messages, by [@Progi1984](https://github.com/Progi1984)
* [#25326](https://github.com/PrestaShop/PrestaShop/pull/25326): Create empty Customer when the customer or the guest has been deleted, by [@PierreRambaud](https://github.com/PierreRambaud)


### Installer
* [#25306](https://github.com/PrestaShop/PrestaShop/pull/25306): Fix 1.7.7.2 upgrade. Thank you [@Seb33300](https://github.com/Seb33300)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#1092](https://github.com/PrestaShop/docs/pull/1092): Moved some overrides to the theme , by [@Progi1984](https://github.com/Progi1984)
* [#1091](https://github.com/PrestaShop/docs/pull/1091): Extract theme to a specific repository, by [@Progi1984](https://github.com/Progi1984)
* [#1087](https://github.com/PrestaShop/docs/pull/1087): Fix broken hooks list, by [@eternoendless](https://github.com/eternoendless)
* [#1086](https://github.com/PrestaShop/docs/pull/1086): Update module configuration page tutorial, by [@eternoendless](https://github.com/eternoendless)
* [#1082](https://github.com/PrestaShop/docs/pull/1082): Expand HelperForm documentation, by [@eternoendless](https://github.com/eternoendless)


### Customer reassurance block module
* [#243](https://github.com/PrestaShop/blockreassurance/pull/243): Bump webpack from 5.45.1 to 5.46.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#242](https://github.com/PrestaShop/blockreassurance/pull/242): Bump @babel/core from 7.14.6 to 7.14.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#241](https://github.com/PrestaShop/blockreassurance/pull/241): Bump style-loader from 3.1.0 to 3.2.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#240](https://github.com/PrestaShop/blockreassurance/pull/240): Bump css-loader from 6.1.0 to 6.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#239](https://github.com/PrestaShop/blockreassurance/pull/239): Bump css-loader from 6.0.0 to 6.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#238](https://github.com/PrestaShop/blockreassurance/pull/238): Bump webpack from 5.44.0 to 5.45.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#476](https://github.com/PrestaShop/ps_facetedsearch/pull/476): Bump webpack from 5.45.1 to 5.46.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#475](https://github.com/PrestaShop/ps_facetedsearch/pull/475): Bump @babel/cli from 7.14.5 to 7.14.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#474](https://github.com/PrestaShop/ps_facetedsearch/pull/474): Bump @babel/core from 7.14.6 to 7.14.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#473](https://github.com/PrestaShop/ps_facetedsearch/pull/473): Bump @babel/preset-env from 7.14.7 to 7.14.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#472](https://github.com/PrestaShop/ps_facetedsearch/pull/472): Bump css-loader from 6.1.0 to 6.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#471](https://github.com/PrestaShop/ps_facetedsearch/pull/471): Bump css-loader from 6.0.0 to 6.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#470](https://github.com/PrestaShop/ps_facetedsearch/pull/470): Bump webpack from 5.44.0 to 5.45.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Contextual Help Api
* [#3](https://github.com/PrestaShop/contextual-help-api/pull/3): Update license headers and install extension http, by [@sowbiba](https://github.com/sowbiba)
* [#1](https://github.com/PrestaShop/contextual-help-api/pull/1): Initial commit - Functional App, by [@sowbiba](https://github.com/sowbiba)


### Core Weekly Generator tool
* [#91](https://github.com/PrestaShop/core-weekly-generator/pull/91): Handle years that start with different week numbers, by [@matks](https://github.com/matks)


### User documentation landing page
* [#94](https://github.com/PrestaShop/user-documentation-landing/pull/94): fix(deps): bump actions/setup-node from 2.2.0 to 2.3.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#93](https://github.com/PrestaShop/user-documentation-landing/pull/93): chore(deps-dev): bump eslint from 7.30.0 to 7.31.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### stylelint configuration
* [#19](https://github.com/PrestaShop/stylelint-config/pull/19): Bump stylelint-config-twbs-bootstrap from 2.2.2 to 2.2.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#18](https://github.com/PrestaShop/stylelint-config/pull/18): Bump stylelint-config-twbs-bootstrap from 2.2.1 to 2.2.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Links list module
* [#131](https://github.com/PrestaShop/ps_linklist/pull/131): Make ps_linklist compatible with twig 3, by [@atomiix](https://github.com/atomiix)


### TranslationTools Bundle
* [#94](https://github.com/PrestaShop/TranslationToolsBundle/pull/94): Twig compatibility (v1, v2 & v3), by [@atomiix](https://github.com/atomiix)


### Contact Form module
* [#56](https://github.com/PrestaShop/contactform/pull/56): Added WebP as authorized extension in Attachment, by [@Progi1984](https://github.com/Progi1984)


### Social Follow module
* [#26](https://github.com/PrestaShop/ps_socialfollow/pull/26): Introduce localized links. Thank you [@lmeyer1](https://github.com/lmeyer1)


### Customer "Sign in" link module
* [#40](https://github.com/PrestaShop/ps_customersignin/pull/40): Deprecate variable for logged in customer. Thank you [@Hlavtox](https://github.com/Hlavtox)


### Wishlist block module
* [#114](https://github.com/PrestaShop/blockwishlist/pull/114): Facilitate customizations of the module, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#109](https://github.com/PrestaShop/blockwishlist/pull/109): Javascript bundles optimization. Thank you [@Oksydan](https://github.com/Oksydan)


### Auto Upgrade module
* [#369](https://github.com/PrestaShop/autoupgrade/pull/369): Avoid drop of some tables like guests, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@PierreRambaud](https://github.com/PierreRambaud), [@dependabot[bot]](https://github.com/apps/dependabot), [@sowbiba](https://github.com/sowbiba), [@matks](https://github.com/matks), [@atomiix](https://github.com/atomiix), [@eternoendless](https://github.com/eternoendless), [@jolelievre](https://github.com/jolelievre), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@kpodemski](https://github.com/kpodemski), [@Seb33300](https://github.com/Seb33300), [@boubkerbribri](https://github.com/boubkerbribri), [@Arnaud104](https://github.com/Arnaud104), [@okom3pom](https://github.com/okom3pom), [@lmeyer1](https://github.com/lmeyer1), [@jf-viguier](https://github.com/jf-viguier), [@Hlavtox](https://github.com/Hlavtox), [@NeOMakinG](https://github.com/NeOMakinG), [@Oksydan](https://github.com/Oksydan), [@Sinepel](https://github.com/Sinepel), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
