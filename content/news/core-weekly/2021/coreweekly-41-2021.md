---
layout: post
aliases: ["/news/coreweekly-41-2021"]
title:  "PrestaShop Core Weekly - Week 41 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-10-18
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 11th to Sunday 17th of October 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [70 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-10-11..2021-10-17) have been created in the project repositories;
- [52 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-10-11..2021-10-17), including [10 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-10-11..2021-10-17) on the core;
- [112 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-10-11..2021-10-17) in the project repositories;
- [100 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-10-11..2021-10-17), including [73 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-10-11..2021-10-17).
        


## Code changes in the 'develop' branch


### Core
* [#26251](https://github.com/PrestaShop/PrestaShop/pull/26251): Fixed call to `Order::getCurrentState()` method, by [@Progi1984](https://github.com/Progi1984)
* [#26189](https://github.com/PrestaShop/PrestaShop/pull/26189): Remove useless mod php5 check, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25843](https://github.com/PrestaShop/PrestaShop/pull/25843): Rework create-test-db command from tests-legacy to tests folder, by [@Progi1984](https://github.com/Progi1984)
* [#24394](https://github.com/PrestaShop/PrestaShop/pull/24394): Added support for WebP, by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#25869](https://github.com/PrestaShop/PrestaShop/pull/25869): Product quantity is now handled by delta modification, by [@jolelievre](https://github.com/jolelievre)


### Front office
* [#26194](https://github.com/PrestaShop/PrestaShop/pull/26194): Fix product brand in microdata. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25882](https://github.com/PrestaShop/PrestaShop/pull/25882): Respect country setting "Display tax label (e.g. "Tax incl.")" in cart and order confirmation page. Thank you [@tswfi](https://github.com/tswfi)
* [#25856](https://github.com/PrestaShop/PrestaShop/pull/25856): Subcategories template refacto. Thank you [@Oksydan](https://github.com/Oksydan)


### Installer
* [#26166](https://github.com/PrestaShop/PrestaShop/pull/26166): Update INSTALL.txt for PS 8, by [@matks](https://github.com/matks)
* [#26132](https://github.com/PrestaShop/PrestaShop/pull/26132): Add missing hooks actionCustomerLogout & displayCheckoutSummaryTop. Thank you [@okom3pom](https://github.com/okom3pom)


### Tests
* [#26265](https://github.com/PrestaShop/PrestaShop/pull/26265): Use nodejs 14 for JS routing update cron GitHub Action, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#26228](https://github.com/PrestaShop/PrestaShop/pull/26228): Fix message displayed when enabling fuzzy search, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#26209](https://github.com/PrestaShop/PrestaShop/pull/26209): Fix yamllint warnings and errors, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#26190](https://github.com/PrestaShop/PrestaShop/pull/26190): Functional tests - Refacto Shop Parameters > Traffic & SEO - Search tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#26185](https://github.com/PrestaShop/PrestaShop/pull/26185): Add unit test for B2BFeature, by [@matks](https://github.com/matks)
* [#26165](https://github.com/PrestaShop/PrestaShop/pull/26165): Functional Tests - Refacto Shop Parameters > Contact tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#26163](https://github.com/PrestaShop/PrestaShop/pull/26163): Functional Tests - Refacto  Shop Parameters > Customer Settings tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#26124](https://github.com/PrestaShop/PrestaShop/pull/26124): Functional tests - Refacto Shop Parameters > Product Settings tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.8.x' branch


### Back office
* [#26089](https://github.com/PrestaShop/PrestaShop/pull/26089): Allow multi-store changes on the Performance page, by [@kpodemski](https://github.com/kpodemski)
* [#25822](https://github.com/PrestaShop/PrestaShop/pull/25822): Fixed pagination in Customer - View Page, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#26225](https://github.com/PrestaShop/PrestaShop/pull/26225): Prevent bc breaks related to the shop logo, by [@kpodemski](https://github.com/kpodemski)


## Code changes in modules, themes & tools


### Auto Upgrade module
* [#427](https://github.com/PrestaShop/autoupgrade/pull/427): Added SQL for WebP Configuration, by [@Progi1984](https://github.com/Progi1984)
* [#425](https://github.com/PrestaShop/autoupgrade/pull/425): Fix wording, by [@marionf](https://github.com/marionf)
* [#419](https://github.com/PrestaShop/autoupgrade/pull/419): Edit the wording of the welcome part. Thank you [@okom3pom](https://github.com/okom3pom)


### Changes in developer documentation sources
* [#1190](https://github.com/PrestaShop/docs/pull/1190): Improve 1.7.x nginx template. Thank you [@juangiordana](https://github.com/juangiordana)
* [#1188](https://github.com/PrestaShop/docs/pull/1188): Fix wrong directory in CI when in pull request (backport #1186), by [@eternoendless](https://github.com/eternoendless)
* [#1187](https://github.com/PrestaShop/docs/pull/1187): Upgrade files are now in autoupgrade module, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#1186](https://github.com/PrestaShop/docs/pull/1186): Fix wrong directory in CI when in pull request, by [@eternoendless](https://github.com/eternoendless)
* [#1184](https://github.com/PrestaShop/docs/pull/1184): Override folder has to be writable. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#1180](https://github.com/PrestaShop/docs/pull/1180): Remove unused images related to Forge usage, by [@matks](https://github.com/matks)
* [#1179](https://github.com/PrestaShop/docs/pull/1179): Update PR process image, by [@matks](https://github.com/matks)
* [#1177](https://github.com/PrestaShop/docs/pull/1177): Refer to Symfony documentation 4.4 instead of 3.4, by [@matks](https://github.com/matks)
* [#1083](https://github.com/PrestaShop/docs/pull/1083): Add typescript informations in coding standards, by [@NeOMakinG](https://github.com/NeOMakinG)


### New 8.0.0 Front-office theme
* [#87](https://github.com/PrestaShop/theme-refacto/pull/87): Refacto footer into 4 columns and get rid of legacy classes. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#82](https://github.com/PrestaShop/theme-refacto/pull/82): Rework a lot of component in order to use bootstrap, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#80](https://github.com/PrestaShop/theme-refacto/pull/80): Product page accordions. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#79](https://github.com/PrestaShop/theme-refacto/pull/79): Restore scss custom import, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#78](https://github.com/PrestaShop/theme-refacto/pull/78): Add watch command without webpack dev server, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#77](https://github.com/PrestaShop/theme-refacto/pull/77): Adjust bootstrap product list theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#76](https://github.com/PrestaShop/theme-refacto/pull/76): Env stuff in readme. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#74](https://github.com/PrestaShop/theme-refacto/pull/74): Fix markup validity for header. Thank you [@micka-fdz](https://github.com/micka-fdz)
* [#73](https://github.com/PrestaShop/theme-refacto/pull/73): Use numeric values for font-weight. Thank you [@micka-fdz](https://github.com/micka-fdz)
* [#72](https://github.com/PrestaShop/theme-refacto/pull/72): Reorder import rules in scss files. Thank you [@micka-fdz](https://github.com/micka-fdz)
* [#71](https://github.com/PrestaShop/theme-refacto/pull/71): Update usage of $shop.logo var as it's now an array. Thank you [@PrestaEdit](https://github.com/PrestaEdit)
* [#69](https://github.com/PrestaShop/theme-refacto/pull/69): Fix product brand in microdata. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#67](https://github.com/PrestaShop/theme-refacto/pull/67): New webpack config . Thank you [@Oksydan](https://github.com/Oksydan)
* [#66](https://github.com/PrestaShop/theme-refacto/pull/66): Configure bootstrap variables and expose some css vars, by [@NeOMakinG](https://github.com/NeOMakinG)


### PrestaShop Specifications
* [#248](https://github.com/PrestaShop/prestashop-specs/pull/248): Updates behavior when switching context, by [@marionf](https://github.com/marionf)
* [#247](https://github.com/PrestaShop/prestashop-specs/pull/247): Cart Rules + Cataog Price Rules (images). Thank you [@SimonasB88](https://github.com/SimonasB88)
* [#245](https://github.com/PrestaShop/prestashop-specs/pull/245): Update specs for associated categories, by [@marionf](https://github.com/marionf)
* [#242](https://github.com/PrestaShop/prestashop-specs/pull/242): Use good url image for readme. Thank you [@okom3pom](https://github.com/okom3pom)


### Example modules
* [#81](https://github.com/PrestaShop/example-modules/pull/81): Typo fix, by [@PierreRambaud](https://github.com/PierreRambaud)


### Docker internal images
* [#36](https://github.com/PrestaShop/docker-internal-images/pull/36): Update service name from mysql to mariadb, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Customer reassurance block module
* [#292](https://github.com/PrestaShop/blockreassurance/pull/292): Bump webpack from 5.58.1 to 5.58.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#291](https://github.com/PrestaShop/blockreassurance/pull/291): Bump sass-loader from 12.1.0 to 12.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#290](https://github.com/PrestaShop/blockreassurance/pull/290): Bump eslint-plugin-import from 2.24.2 to 2.25.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#289](https://github.com/PrestaShop/blockreassurance/pull/289): Bump webpack from 5.58.0 to 5.58.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#288](https://github.com/PrestaShop/blockreassurance/pull/288): Bump css-loader from 6.3.0 to 6.4.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#267](https://github.com/PrestaShop/blockreassurance/pull/267): Remove heading capitalization. Thank you [@the-ge](https://github.com/the-ge)


### Faceted search module
* [#529](https://github.com/PrestaShop/ps_facetedsearch/pull/529): Bump webpack from 5.58.1 to 5.58.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#528](https://github.com/PrestaShop/ps_facetedsearch/pull/528): Bump eslint-plugin-import from 2.24.2 to 2.25.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#527](https://github.com/PrestaShop/ps_facetedsearch/pull/527): Bump sass-loader from 12.1.0 to 12.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#526](https://github.com/PrestaShop/ps_facetedsearch/pull/526): Bump webpack from 5.58.0 to 5.58.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#525](https://github.com/PrestaShop/ps_facetedsearch/pull/525): Bump css-loader from 6.3.0 to 6.4.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#141](https://github.com/PrestaShop/user-documentation-landing/pull/141): chore(deps-dev): bump sass from 1.42.1 to 1.43.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#140](https://github.com/PrestaShop/user-documentation-landing/pull/140): fix(deps): bump core-js from 3.18.2 to 3.18.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#139](https://github.com/PrestaShop/user-documentation-landing/pull/139): chore(deps-dev): bump babel-jest from 27.2.4 to 27.2.5. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#131](https://github.com/PrestaShop/welcome/pull/131): Bump eslint-plugin-import from 2.24.2 to 2.25.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Circuit Breaker
* [#44](https://github.com/PrestaShop/circuit-breaker/pull/44): Put php-dev-tools in require-dev, by [@atomiix](https://github.com/atomiix)


### TranslationTools Bundle
* [#101](https://github.com/PrestaShop/TranslationToolsBundle/pull/101): Put php-cs-fixer in require-dev, by [@atomiix](https://github.com/atomiix)


### Email Alerts module
* [#93](https://github.com/PrestaShop/ps_emailalerts/pull/93): Enable mail alerts subscription in quick view window. Thank you [@daresh](https://github.com/daresh)


### LocalizationFiles
* [#11](https://github.com/PrestaShop/LocalizationFiles/pull/11): Add localization pack for Monaco. Thank you [@micka-fdz](https://github.com/micka-fdz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@PierreRambaud](https://github.com/PierreRambaud), [@Progi1984](https://github.com/Progi1984), [@juangiordana](https://github.com/juangiordana), [@Hlavtox](https://github.com/Hlavtox), [@NeOMakinG](https://github.com/NeOMakinG), [@marionf](https://github.com/marionf), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@dependabot[bot]](https://github.com/apps/dependabot), [@eternoendless](https://github.com/eternoendless), [@SimonasB88](https://github.com/SimonasB88), [@boubkerbribri](https://github.com/boubkerbribri), [@jf-viguier](https://github.com/jf-viguier), [@kpodemski](https://github.com/kpodemski), [@micka-fdz](https://github.com/micka-fdz), [@atomiix](https://github.com/atomiix), [@PrestaEdit](https://github.com/PrestaEdit), [@matks](https://github.com/matks), [@sowbiba](https://github.com/sowbiba), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@okom3pom](https://github.com/okom3pom), [@Oksydan](https://github.com/Oksydan), [@daresh](https://github.com/daresh), [@tswfi](https://github.com/tswfi), [@jolelievre](https://github.com/jolelievre), [@the-ge](https://github.com/the-ge)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

