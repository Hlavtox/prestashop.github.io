---
layout: post
aliases: ["/news/coreweekly-10-2021"]
title:  "PrestaShop Core Weekly - Week 10 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-03-15
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 8th to Sunday 14th of March 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [Blockwishlist](https://github.com/PrestaShop/blockwishlist): [v2.0.0](https://github.com/PrestaShop/blockwishlist/releases/tag/v2.0.0)
* [php-dev-tools](https://github.com/PrestaShop/php-dev-tools): [v3.15](https://github.com/PrestaShop/php-dev-tools/releases/tag/v3.15)
* [phpstan-prestashop](https://github.com/PrestaShop/phpstan-prestashop): [1.1.1](https://github.com/PrestaShop/phpstan-prestashop/releases/tag/1.1.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [49 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-03-08..2021-03-14) have been created in the project repositories;
- [60 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-03-08..2021-03-14), including [14 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-03-08..2021-03-14) on the core;
- [103 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-03-08..2021-03-14) in the project repositories;
- [128 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-03-08..2021-03-14), including [91 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-03-08..2021-03-14).



## Code changes in the 'develop' branch


### Core
* [#23525](https://github.com/PrestaShop/PrestaShop/pull/23525): Problem with PHP7.4 with Customer::getCurrentCountry and Tab management, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#23608](https://github.com/PrestaShop/PrestaShop/pull/23608): Fix shadow of right sidebar on responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23602](https://github.com/PrestaShop/PrestaShop/pull/23602): Product shortcuts, by [@jolelievre](https://github.com/jolelievre)
* [#23568](https://github.com/PrestaShop/PrestaShop/pull/23568): Fix logout and hover colors on profile pan responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23541](https://github.com/PrestaShop/PrestaShop/pull/23541): BO / Cart rule / neutralize titles. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#23527](https://github.com/PrestaShop/PrestaShop/pull/23527): BO / Cart rule / Improve product selection. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#23502](https://github.com/PrestaShop/PrestaShop/pull/23502): Harmonize wordings of notifications pan, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23499](https://github.com/PrestaShop/PrestaShop/pull/23499): Fix renderStock signature changed on 1.7.7 on create order page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23483](https://github.com/PrestaShop/PrestaShop/pull/23483): Fix payment module list responsive in the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23475](https://github.com/PrestaShop/PrestaShop/pull/23475): Introduce javascript pagination component for combinations. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23371](https://github.com/PrestaShop/PrestaShop/pull/23371): Improve accessibility in the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23296](https://github.com/PrestaShop/PrestaShop/pull/23296): Add ProviderDefinition and complete Factory, by [@sowbiba](https://github.com/sowbiba)
* [#23137](https://github.com/PrestaShop/PrestaShop/pull/23137): Trigger change() on attribute_priceTE when clicking save button to handle broken localization packs.. Thank you [@Prestaworks](https://github.com/Prestaworks)
* [#23127](https://github.com/PrestaShop/PrestaShop/pull/23127): Simplify 'Add a theme' form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#22438](https://github.com/PrestaShop/PrestaShop/pull/22438): Make root category of a shop non editable, by [@sowbiba](https://github.com/sowbiba)
* [#18396](https://github.com/PrestaShop/PrestaShop/pull/18396): Import source files of the UIKit instead of dist files to use prestakit variables, by [@NeOMakinG](https://github.com/NeOMakinG)


### Front office
* [#23169](https://github.com/PrestaShop/PrestaShop/pull/23169): Fixes issue with cms category ordering in sitemap. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Installer
* [#23566](https://github.com/PrestaShop/PrestaShop/pull/23566): Use correct protocol in install.txt. Thank you [@okom3pom](https://github.com/okom3pom)


### Tests
* [#23622](https://github.com/PrestaShop/PrestaShop/pull/23622): Fix click on behavior input on Add product page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23611](https://github.com/PrestaShop/PrestaShop/pull/23611): Fix nightly 11-03-2020. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23597](https://github.com/PrestaShop/PrestaShop/pull/23597): Disable again PHPStan PrestaShop extension 1.1.1, by [@matks](https://github.com/matks)
* [#23594](https://github.com/PrestaShop/PrestaShop/pull/23594): Add missing functions on develop to fix the nightly, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23590](https://github.com/PrestaShop/PrestaShop/pull/23590): Update phpstan-prestashop to 1.1.1, restore the usage of the extension, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch


### Tests
* [#23624](https://github.com/PrestaShop/PrestaShop/pull/23624): Fix wait after choosing combination, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23614](https://github.com/PrestaShop/PrestaShop/pull/23614): Add test 'Quick edit and bulk actions shop URLs'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23585](https://github.com/PrestaShop/PrestaShop/pull/23585): Fix nightly 09/03/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23554](https://github.com/PrestaShop/PrestaShop/pull/23554): Click on logo link on checkout page to go to home page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23542](https://github.com/PrestaShop/PrestaShop/pull/23542): Add test 'Check product details in product page FO'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#888](https://github.com/PrestaShop/docs/pull/888): Harmonize project name. Thank you [@okom3pom](https://github.com/okom3pom)
* [#887](https://github.com/PrestaShop/docs/pull/887): Fix http to https doc.prestashop.com link. Thank you [@okom3pom](https://github.com/okom3pom)
* [#885](https://github.com/PrestaShop/docs/pull/885): Fix link to https://validator.prestashop.com/. Thank you [@okom3pom](https://github.com/okom3pom)
* [#882](https://github.com/PrestaShop/docs/pull/882): Fix some typo and reword few sentences. Thank you [@ent47](https://github.com/ent47)
* [#881](https://github.com/PrestaShop/docs/pull/881): Bump elliptic from 6.5.3 to 6.5.4 in `/src/themes/hugo-theme-learn/_src`. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#879](https://github.com/PrestaShop/docs/pull/879): Add HtmlColumn documentation. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#878](https://github.com/PrestaShop/docs/pull/878): Expand the release instructions and put them inside the maintainer's guide, by [@eternoendless](https://github.com/eternoendless)


### TranslationTools Bundle
* [#84](https://github.com/PrestaShop/TranslationToolsBundle/pull/84): Migrated from Travis CI to Github Actions & Added PHPCSFixer, by [@Progi1984](https://github.com/Progi1984)


### Docker internal images
* [#35](https://github.com/PrestaShop/docker-internal-images/pull/35): Migrated Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### PrestaShop on Docker
* [#20](https://github.com/PrestaShop/docker-ci/pull/20): Migrated Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### GDPR module
* [#139](https://github.com/PrestaShop/psgdpr/pull/139): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Links list module
* [#115](https://github.com/PrestaShop/ps_linklist/pull/115): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Search Bar module
* [#34](https://github.com/PrestaShop/ps_searchbar/pull/34): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Category tree links module
* [#51](https://github.com/PrestaShop/ps_categorytree/pull/51): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Shopping cart module
* [#76](https://github.com/PrestaShop/ps_shoppingcart/pull/76): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Simple HTML table display module
* [#21](https://github.com/PrestaShop/gridhtml/pull/21): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Dashboard Trends module
* [#43](https://github.com/PrestaShop/dashtrends/pull/43): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer "Sign in" link module
* [#34](https://github.com/PrestaShop/ps_customersignin/pull/34): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Custom text module
* [#60](https://github.com/PrestaShop/ps_customtext/pull/60): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#370](https://github.com/PrestaShop/ps_facetedsearch/pull/370): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#368](https://github.com/PrestaShop/ps_facetedsearch/pull/368): Bump version to 3.7.1, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#367](https://github.com/PrestaShop/ps_facetedsearch/pull/367): Bump css-loader from 5.1.1 to 5.1.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#366](https://github.com/PrestaShop/ps_facetedsearch/pull/366): Bump @babel/preset-env from 7.13.9 to 7.13.10. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#365](https://github.com/PrestaShop/ps_facetedsearch/pull/365): Bump webpack from 5.24.3 to 5.24.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#364](https://github.com/PrestaShop/ps_facetedsearch/pull/364): Bump @babel/core from 7.13.8 to 7.13.10. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#363](https://github.com/PrestaShop/ps_facetedsearch/pull/363): Bump @babel/cli from 7.13.0 to 7.13.10. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#362](https://github.com/PrestaShop/ps_facetedsearch/pull/362): Bump @babel/node from 7.13.0 to 7.13.10. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#361](https://github.com/PrestaShop/ps_facetedsearch/pull/361): Bump mocha from 8.3.0 to 8.3.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#102](https://github.com/PrestaShop/welcome/pull/102): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Check payment module
* [#47](https://github.com/PrestaShop/ps_checkpayment/pull/47): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Product Comments module
* [#99](https://github.com/PrestaShop/productcomments/pull/99): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Theme customization module
* [#42](https://github.com/PrestaShop/ps_themecusto/pull/42): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Order Notifications on the Favicon module
* [#28](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/28): Bump prestashop/php-dev-tools from 3.14 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PHP Developer Tools
* [#50](https://github.com/PrestaShop/php-dev-tools/pull/50): Avoid specific version of php-cs-fixer, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Customer reassurance block module
* [#146](https://github.com/PrestaShop/blockreassurance/pull/146): Bump css-loader from 5.1.1 to 5.1.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#144](https://github.com/PrestaShop/blockreassurance/pull/144): Bump webpack from 5.24.3 to 5.24.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#143](https://github.com/PrestaShop/blockreassurance/pull/143): Bump @babel/core from 7.13.8 to 7.13.10. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#38](https://github.com/PrestaShop/user-documentation-landing/pull/38): fix(deps): bump nuxt from 2.15.2 to 2.15.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#37](https://github.com/PrestaShop/user-documentation-landing/pull/37): chore(deps-dev): bump @nuxtjs/eslint-config from 3.1.0 to 6.0.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Email Alerts module
* [#78](https://github.com/PrestaShop/ps_emailalerts/pull/78): Bump version to 2.2.2. Thank you [@tswfi](https://github.com/tswfi)


### Core Weekly Generator tool
* [#77](https://github.com/PrestaShop/core-weekly-generator/pull/77): Bump elliptic from 6.5.3 to 6.5.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop PHPStan extension
* [#19](https://github.com/PrestaShop/phpstan-prestashop/pull/19): Fix configuration file - mismatch parameters, by [@matks](https://github.com/matks)
* [#18](https://github.com/PrestaShop/phpstan-prestashop/pull/18): Exclude class methods with inheritdoc for Type rules, by [@matks](https://github.com/matks)
* [#17](https://github.com/PrestaShop/phpstan-prestashop/pull/17): Exclude for rules magic methods, by [@matks](https://github.com/matks)
* [#16](https://github.com/PrestaShop/phpstan-prestashop/pull/16): Add interface test usecases, by [@matks](https://github.com/matks)


### Wishlist block module
* [#106](https://github.com/PrestaShop/blockwishlist/pull/106): Bump lodash from 4.17.15 to 4.17.21. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#104](https://github.com/PrestaShop/blockwishlist/pull/104): Bump ini from 1.3.5 to 1.3.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#101](https://github.com/PrestaShop/blockwishlist/pull/101): Release 2.0.0, by [@Progi1984](https://github.com/Progi1984)


### Buy button lite module
* [#46](https://github.com/PrestaShop/ps_buybuttonlite/pull/46): Bump elliptic from 6.4.1 to 6.5.4 in /app. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Prestashop UI Kit
* [#142](https://github.com/PrestaShop/prestashop-ui-kit/pull/142): Bump elliptic from 6.5.3 to 6.5.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#140](https://github.com/PrestaShop/prestashop-ui-kit/pull/140): Fix modal max height on exception for example, by [@NeOMakinG](https://github.com/NeOMakinG)


### Auto Upgrade module
* [#386](https://github.com/PrestaShop/autoupgrade/pull/386): Add more nightly tests and re-enable 1.6 migration test, by [@atomiix](https://github.com/atomiix)


### PrestaShop Specifications
* [#206](https://github.com/PrestaShop/prestashop-specs/pull/206): Add multistore specs for maintenance page, by [@marionf](https://github.com/marionf)
* [#204](https://github.com/PrestaShop/prestashop-specs/pull/204): Multistore - Add specs for add/edit employees, by [@marionf](https://github.com/marionf)
* [#203](https://github.com/PrestaShop/prestashop-specs/pull/203): Multistore specify behavior when unchecking a box, by [@marionf](https://github.com/marionf)


## PrestaShop user documentation

### PrestaShop user documentation (FR)
* [#2](https://github.com/PrestaShop/user-documentation-fr/pull/2): Delete duplicates following Gitbook synchronisation . Thank you [@Julievrz](https://github.com/Julievrz)

### PrestaShop user documentation (ES)
* [#1](https://github.com/PrestaShop/user-documentation-es/pull/1): Delete duplicate content following GitBook synchronization. Thank you [@Julievrz](https://github.com/Julievrz)

### PrestaShop user documentation (Farsi)
* [#1](https://github.com/PrestaShop/user-documentation-fa/pull/1): Delete duplicate content after GitBook/Github synchronization failed. Thank you [@Julievrz](https://github.com/Julievrz)

### PrestaShop user documentation (Dutch)
* [#1](https://github.com/PrestaShop/user-documentation-nl/pull/1): Delete duplicate content in the Dutch user documentation. Thank you [@Julievrz](https://github.com/Julievrz)

### PrestaShop user documentation (Italian)
* [#1](https://github.com/PrestaShop/user-documentation-it/pull/1): Delete duplicate content. Thank you [@Julievrz](https://github.com/Julievrz)


## Where to start contributing?

What about [adding a button to remove supplier or brand logos](https://github.com/PrestaShop/PrestaShop/issues/20857) in the Back Office page ? This is a feature request submitted six months ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@okom3pom](https://github.com/okom3pom), [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@matks](https://github.com/matks), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@NeOMakinG](https://github.com/NeOMakinG), [@PierreRambaud](https://github.com/PierreRambaud), [@jolelievre](https://github.com/jolelievre), [@tswfi](https://github.com/tswfi), [@Julievrz](https://github.com/Julievrz), [@ent47](https://github.com/ent47), [@sowbiba](https://github.com/sowbiba), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@eternoendless](https://github.com/eternoendless), [@jf-viguier](https://github.com/jf-viguier), [@atomiix](https://github.com/atomiix), [@zuk3975](https://github.com/zuk3975), [@marionf](https://github.com/marionf), [@Prestaworks](https://github.com/Prestaworks)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
