---
layout: post
aliases: ["/news/coreweekly-15-2021"]
title:  "PrestaShop Core Weekly - Week 15 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-04-21
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 12th to Sunday 18th of April 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

We are immensely proud to announce that PrestaShop 1.7.8.0 is feature frozen!!! 🍾️ 🎉️ ☃️

This means that the development of this version has now entered the [stabilization phase](https://devdocs.prestashop.com/1.7/project/release/patch-release-lifecycle/#feature-freeze). 

A quick look at the work done so far on 1.7.8:

- [436 GitHub issues have been fixed](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+milestone%3A1.7.8.0+is%3Aclosed+label%3AFixed)
- [1232 Pull Requests have been merged](https://github.com/PrestaShop/PrestaShop/pulls?utf8=%E2%9C%93&q=is%3Apr+milestone%3A1.7.8.0+is%3Amerged)

The last weeks have been intense for all PrestaShop teams but we are very happy about the result... and we hope you will love it too.

The `1.7.8.x` branch has been created and any new changes submitted in the `develop` branch will be milestoned for 1.7.9 .

### What are the next steps?

Following the freeze, the QA team will perform a large test campaign to explore the 1.7.8.0 and evaluate how much stabilization it needs.

This test campaign will tell us how 'mature' the `1.7.8.x` branch, and give us indications about when the Beta period could start.


## Releases

* [Prestashop-ui-kit](https://github.com/PrestaShop/prestashop-ui-kit): [v1.2.3](https://github.com/PrestaShop/prestashop-ui-kit/releases/tag/v1.2.3)
* [php-dev-tools](https://github.com/PrestaShop/php-dev-tools): [v4.0](https://github.com/PrestaShop/php-dev-tools/releases/tag/v4.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [56 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-04-12..2021-04-18) have been created in the project repositories;
- [73 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-04-12..2021-04-18), including [23 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-04-12..2021-04-18) on the core;
- [105 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-04-12..2021-04-18) in the project repositories;
- [110 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-04-12..2021-04-18), including [95 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-04-12..2021-04-18).


## Code changes in the 'develop' branch (for version 1.7.8.0)


### Core
* [#24055](https://github.com/PrestaShop/PrestaShop/pull/24055): Updated JS Routing file. Thank you [@github-actions[bot]](https://github.com/apps/github-actions)
* [#24053](https://github.com/PrestaShop/PrestaShop/pull/24053): Fix file license headers, by [@matks](https://github.com/matks)
* [#23960](https://github.com/PrestaShop/PrestaShop/pull/23960): Add webservice/ dir to phpstan. Thank you [@mvorisek](https://github.com/mvorisek)
* [#23617](https://github.com/PrestaShop/PrestaShop/pull/23617): Added blockwishlist module & Removed archived modules, by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#24056](https://github.com/PrestaShop/PrestaShop/pull/24056): Handle combination suppliers in product page v2, by [@jolelievre](https://github.com/jolelievre)
* [#24049](https://github.com/PrestaShop/PrestaShop/pull/24049): Export translation catalogues, by [@sowbiba](https://github.com/sowbiba)
* [#24045](https://github.com/PrestaShop/PrestaShop/pull/24045): Register translation wordings for Feature Flag, by [@matks](https://github.com/matks)
* [#24042](https://github.com/PrestaShop/PrestaShop/pull/24042): Improve multistore dropdown behavior, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#24040](https://github.com/PrestaShop/PrestaShop/pull/24040): Update prestakit to v1.2.3, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#24038](https://github.com/PrestaShop/PrestaShop/pull/24038): Implement Product Page V2 flag behavior, by [@matks](https://github.com/matks)
* [#24037](https://github.com/PrestaShop/PrestaShop/pull/24037): Load Product Page V2 Feature flag at install, by [@matks](https://github.com/matks)
* [#24032](https://github.com/PrestaShop/PrestaShop/pull/24032): Add multistore info messages, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#24028](https://github.com/PrestaShop/PrestaShop/pull/24028): Fixed wording domains in multistore dropdown template, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#24013](https://github.com/PrestaShop/PrestaShop/pull/24013): Add images to combinations list. Thank you [@zuk3975](https://github.com/zuk3975)
* [#24009](https://github.com/PrestaShop/PrestaShop/pull/24009): Use object mapping in multistore-header js, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#24005](https://github.com/PrestaShop/PrestaShop/pull/24005): Fix order details product pagination not showing, by [@atomiix](https://github.com/atomiix)
* [#23995](https://github.com/PrestaShop/PrestaShop/pull/23995): Rename currency column into name, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#23968](https://github.com/PrestaShop/PrestaShop/pull/23968): Display module's multistore compatibility in description, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#23956](https://github.com/PrestaShop/PrestaShop/pull/23956): Combination form part 2 in new Product Page, by [@jolelievre](https://github.com/jolelievre)
* [#23940](https://github.com/PrestaShop/PrestaShop/pull/23940): Disable add new customer button in all shops or in a group context, by [@matks](https://github.com/matks)
* [#23927](https://github.com/PrestaShop/PrestaShop/pull/23927): Display multishop header for translations page and lock it to all shops context, by [@sowbiba](https://github.com/sowbiba)
* [#23871](https://github.com/PrestaShop/PrestaShop/pull/23871): Improve product dropzone code quality, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23857](https://github.com/PrestaShop/PrestaShop/pull/23857): Change signature of TranslationFinder::getTranslationFilesFromPath to accept null pattern, by [@sowbiba](https://github.com/sowbiba)
* [#23788](https://github.com/PrestaShop/PrestaShop/pull/23788): Add combinations filters to product page v2, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23703](https://github.com/PrestaShop/PrestaShop/pull/23703): New BO page Experimental Feature, by [@matks](https://github.com/matks)
* [#23696](https://github.com/PrestaShop/PrestaShop/pull/23696): Use new components on translation BO interface, by [@sowbiba](https://github.com/sowbiba)
* [#23350](https://github.com/PrestaShop/PrestaShop/pull/23350): Integrate virtual product file upload in product form. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21924](https://github.com/PrestaShop/PrestaShop/pull/21924): Simplified contact form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#21737](https://github.com/PrestaShop/PrestaShop/pull/21737): Added support for Addons API stability channel, by [@Progi1984](https://github.com/Progi1984)
* [#18082](https://github.com/PrestaShop/PrestaShop/pull/18082): Make BO menu translatable, by [@eternoendless](https://github.com/eternoendless)


### Front office
* [#24014](https://github.com/PrestaShop/PrestaShop/pull/24014): Update "node-sass" dep from 4.13.1 to 4.14.1. Thank you [@mvorisek](https://github.com/mvorisek)
* [#24012](https://github.com/PrestaShop/PrestaShop/pull/24012): Remove touchstart even on TouchSpin on FO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23776](https://github.com/PrestaShop/PrestaShop/pull/23776): Enable to back to shop in admin login page. Thank you [@PululuK](https://github.com/PululuK)


### Tests
* [#24091](https://github.com/PrestaShop/PrestaShop/pull/24091): Fix nightly tests 16-06-2021, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#24087](https://github.com/PrestaShop/PrestaShop/pull/24087): Added unit test on Validate and Behat test on WSKey Management, by [@Progi1984](https://github.com/Progi1984)
* [#24075](https://github.com/PrestaShop/PrestaShop/pull/24075): Update js documentation for base pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#24046](https://github.com/PrestaShop/PrestaShop/pull/24046): Functional tests - Add test change customer service message status. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24024](https://github.com/PrestaShop/PrestaShop/pull/24024): Add new test "subscribe newsletter" . Thank you [@SD1982](https://github.com/SD1982)
* [#24016](https://github.com/PrestaShop/PrestaShop/pull/24016): Functional tests - Add test to verify login BO. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24006](https://github.com/PrestaShop/PrestaShop/pull/24006): Functional tests - Add missing test to filter orders by date. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24004](https://github.com/PrestaShop/PrestaShop/pull/24004): Functional tests - Add missing test to sort orders by date. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23994](https://github.com/PrestaShop/PrestaShop/pull/23994): Fix step 'Go back to BO' on maintenance test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23965](https://github.com/PrestaShop/PrestaShop/pull/23965): Fix nightly tests 09-04-2021, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23947](https://github.com/PrestaShop/PrestaShop/pull/23947): Upgrade playwright to v1.8.1, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Core
* [#24017](https://github.com/PrestaShop/PrestaShop/pull/24017): Update SHOP_LOGO_* configuration when changing shop logo, by [@atomiix](https://github.com/atomiix)


### Back office
* [#23819](https://github.com/PrestaShop/PrestaShop/pull/23819): Open tracking url in a new tab and add the link to the order preview, by [@atomiix](https://github.com/atomiix)


### Tests
* [#24086](https://github.com/PrestaShop/PrestaShop/pull/24086): Delete dashboad UI test. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24030](https://github.com/PrestaShop/PrestaShop/pull/24030): Fix nightly - Separate enable and disable demo mode iteration. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### PHP Developer Tools
* [#57](https://github.com/PrestaShop/php-dev-tools/pull/57): Update dependencies to be compliant with PHP 7.2.5+, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#52](https://github.com/PrestaShop/php-dev-tools/pull/52): Fix wrong filepath. Thank you [@SebSept](https://github.com/SebSept)


### PrestaShop Specifications
* [#217](https://github.com/PrestaShop/prestashop-specs/pull/217): Fix links in specs, by [@marionf](https://github.com/marionf)
* [#216](https://github.com/PrestaShop/prestashop-specs/pull/216): Some improvements on export translations specification, by [@sowbiba](https://github.com/sowbiba)
* [#214](https://github.com/PrestaShop/prestashop-specs/pull/214): Move everything to content/1.7, by [@eternoendless](https://github.com/eternoendless)


### User documentation landing page
* [#48](https://github.com/PrestaShop/user-documentation-landing/pull/48): chore(deps-dev): bump eslint-plugin-prettier from 3.3.1 to 3.4.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#47](https://github.com/PrestaShop/user-documentation-landing/pull/47): chore(deps-dev): bump eslint-config-prettier from 8.1.0 to 8.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#46](https://github.com/PrestaShop/user-documentation-landing/pull/46): fix(deps): bump actions/cache from v2.1.4 to v2.1.5. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#45](https://github.com/PrestaShop/user-documentation-landing/pull/45): chore(deps-dev): bump eslint from 7.23.0 to 7.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer reassurance block module
* [#173](https://github.com/PrestaShop/blockreassurance/pull/173): Bump webpack from 5.32.0 to 5.33.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#172](https://github.com/PrestaShop/blockreassurance/pull/172): Bump webpack from 5.31.2 to 5.32.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#171](https://github.com/PrestaShop/blockreassurance/pull/171): Update CI badge, by [@matks](https://github.com/matks)
* [#170](https://github.com/PrestaShop/blockreassurance/pull/170): Bump webpack from 5.31.0 to 5.31.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#169](https://github.com/PrestaShop/blockreassurance/pull/169): Bump css-loader from 5.2.0 to 5.2.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#400](https://github.com/PrestaShop/ps_facetedsearch/pull/400): Bump webpack from 5.32.0 to 5.33.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#399](https://github.com/PrestaShop/ps_facetedsearch/pull/399): Bump webpack from 5.31.2 to 5.32.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#398](https://github.com/PrestaShop/ps_facetedsearch/pull/398): Bump webpack from 5.31.0 to 5.31.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#397](https://github.com/PrestaShop/ps_facetedsearch/pull/397): Bump css-loader from 5.2.0 to 5.2.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Prestashop UI Kit
* [#151](https://github.com/PrestaShop/prestashop-ui-kit/pull/151): Release 1.2.3, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#150](https://github.com/PrestaShop/prestashop-ui-kit/pull/150): Update material icon font, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#149](https://github.com/PrestaShop/prestashop-ui-kit/pull/149): Update minor version, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#148](https://github.com/PrestaShop/prestashop-ui-kit/pull/148): Add release CI to publish on npm, by [@NeOMakinG](https://github.com/NeOMakinG)


### Eslint configuration
* [#6](https://github.com/PrestaShop/eslint-config/pull/6): Add release CI on NPM, by [@NeOMakinG](https://github.com/NeOMakinG)


### Changes in developer documentation
* [#933](https://github.com/PrestaShop/docs/pull/933): Move How to Release a native PrestaShop module in maintainer guide, by [@matks](https://github.com/matks)
* [#932](https://github.com/PrestaShop/docs/pull/932): Indicate min hugo version, by [@matks](https://github.com/matks)
* [#931](https://github.com/PrestaShop/docs/pull/931): Update CI badge, by [@matks](https://github.com/matks)
* [#929](https://github.com/PrestaShop/docs/pull/929): Improve how to report issue guide, by [@eternoendless](https://github.com/eternoendless)
* [#928](https://github.com/PrestaShop/docs/pull/928): Add image FAQ. Thank you [@okom3pom](https://github.com/okom3pom)
* [#927](https://github.com/PrestaShop/docs/pull/927): Introduce chapter about the integration of VueJS in an existing module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#925](https://github.com/PrestaShop/docs/pull/925): Improve Tab documentation, by [@eternoendless](https://github.com/eternoendless)
* [#924](https://github.com/PrestaShop/docs/pull/924): Fix `module class name` typo. Thank you [@PululuK](https://github.com/PululuK)
* [#923](https://github.com/PrestaShop/docs/pull/923): Add `Module widget concept` Concret Code Exemple. Thank you [@PululuK](https://github.com/PululuK)


### Decimal
* [#17](https://github.com/PrestaShop/decimal/pull/17): Update CI badge, by [@matks](https://github.com/matks)


### PrestaShop on Docker
* [#21](https://github.com/PrestaShop/docker-ci/pull/21): Update CI badge, by [@matks](https://github.com/matks)


### Circuit breaker
* [#41](https://github.com/PrestaShop/circuit-breaker/pull/41): Update CI badge, by [@matks](https://github.com/matks)


### Links list module
* [#116](https://github.com/PrestaShop/ps_linklist/pull/116): Fix "Link widget" menu item not translated automatically, by [@eternoendless](https://github.com/eternoendless)


### Check payment module
* [#48](https://github.com/PrestaShop/ps_checkpayment/pull/48): Do not display warning if module disabled. Thank you [@okom3pom](https://github.com/okom3pom)


### Wire payment module
* [#62](https://github.com/PrestaShop/ps_wirepayment/pull/62): Do not display warning if module disabled. Thank you [@okom3pom](https://github.com/okom3pom)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@PierreRambaud](https://github.com/PierreRambaud), [@boubkerbribri](https://github.com/boubkerbribri), [@marionf](https://github.com/marionf), [@Progi1984](https://github.com/Progi1984), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@dependabot[bot]](https://github.com/apps/dependabot), [@sowbiba](https://github.com/sowbiba), [@matks](https://github.com/matks), [@jolelievre](https://github.com/jolelievre), [@github-actions[bot]](https://github.com/apps/github-actions), [@SebSept](https://github.com/SebSept), [@matthieu-rolland](https://github.com/matthieu-rolland), [@NeOMakinG](https://github.com/NeOMakinG), [@eternoendless](https://github.com/eternoendless), [@SD1982](https://github.com/SD1982), [@atomiix](https://github.com/atomiix), [@mvorisek](https://github.com/mvorisek), [@zuk3975](https://github.com/zuk3975), [@okom3pom](https://github.com/okom3pom), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@PululuK](https://github.com/PululuK), [@JevgenijVisockij](https://github.com/JevgenijVisockij)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
