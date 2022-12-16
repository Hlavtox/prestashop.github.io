---
layout: post
aliases: ["/news/coreweekly-38-2020"]
title:  "PrestaShop Core Weekly - Week 38 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-09-21
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 14th to Sunday 20th of September 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

PrestaShop project has reached a major open source milestone: [the role of maintainer has been opened](https://devdocs.prestashop.com/1.7/project/maintainers-guide/how-to-become-a-maintainer/).

For years only PrestaShop employees could become maintainers for the project. This is not true anymore. Involved contributors can now apply for the position if they want to help the project to go forward.

Some applications have already been submitted and will follow the voting process described in the rules.

In the meanwhile, there are no more 'todo' items in the [1.7.7 backlog](https://github.com/PrestaShop/PrestaShop/projects/7). Once only the column 'Done' contains items, the Release Candidate 1 will be built and published. And if no issues are found in this version... then [PrestaShop 1.7.7.0 will be out](https://github.com/PrestaShop/PrestaShop/issues/18647)!

## Releases

* [Contactform](https://github.com/PrestaShop/contactform): [v4.3.0](https://github.com/PrestaShop/contactform/releases/tag/v4.3.0)
* [Ps_customtext](https://github.com/PrestaShop/ps_customtext): [v4.1.1](https://github.com/PrestaShop/ps_customtext/releases/tag/v4.1.1)
* [Ps_customersignin](https://github.com/PrestaShop/ps_customersignin): [v2.0.3](https://github.com/PrestaShop/ps_customersignin/releases/tag/v2.0.3)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [81 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-09-14..2020-09-20) have been created in the project repositories;
- [52 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-09-14..2020-09-20), including [13 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-09-14..2020-09-20) on the core;
- [72 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-09-14..2020-09-20) in the project repositories;
- [98 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-09-14..2020-09-20), including [76 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-09-14..2020-09-20).



## Code changes in the 'develop' branch


### Core
* [#20990](https://github.com/PrestaShop/PrestaShop/pull/20990): Fix autoload for composer 2.0 to be compliant with PSR-4, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20969](https://github.com/PrestaShop/PrestaShop/pull/20969): Remove useless comments. Thank you [@PululuK](https://github.com/PululuK)
* [#20891](https://github.com/PrestaShop/PrestaShop/pull/20891): Update Mobiledetect library. Thank you [@PululuK](https://github.com/PululuK)
* [#18985](https://github.com/PrestaShop/PrestaShop/pull/18985): Allow deprecation notices to be caught nicely even in dev mode, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office
* [#21060](https://github.com/PrestaShop/PrestaShop/pull/21060): Fix get scalar value from VO in recently merged deleter services. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21053](https://github.com/PrestaShop/PrestaShop/pull/21053): Introduce CannotBulkDeleteCustomizationFieldException. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20998](https://github.com/PrestaShop/PrestaShop/pull/20998): Use php FILTER_VALIDATE_DOMAIN filter in MediaServerConfiguration's validateConfiguration method, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#20965](https://github.com/PrestaShop/PrestaShop/pull/20965): Remove undefined 2nd argument passed to scrollToPreviousPaginationBar(). Thank you [@davidglezz](https://github.com/davidglezz)
* [#20940](https://github.com/PrestaShop/PrestaShop/pull/20940): Check if SSL is enabled for smarty $base_url. Thank you [@okom3pom](https://github.com/okom3pom)
* [#20926](https://github.com/PrestaShop/PrestaShop/pull/20926): Addons url with good language when exist. Thank you [@okom3pom](https://github.com/okom3pom)
* [#20828](https://github.com/PrestaShop/PrestaShop/pull/20828): Introduce ManufacturerIdInterface for ValueObjects, by [@jolelievre](https://github.com/jolelievre)
* [#20805](https://github.com/PrestaShop/PrestaShop/pull/20805): Add DeleteProductCommand and BulkDeleteProductCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20688](https://github.com/PrestaShop/PrestaShop/pull/20688): Show profile icon on mobile and hide see my shop text, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20549](https://github.com/PrestaShop/PrestaShop/pull/20549): Add RemoveAllCustomizationFieldsFromProductCommand And Introduce AbstractObjectModelPersister. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20413](https://github.com/PrestaShop/PrestaShop/pull/20413): Use SymfonyContainer::getInstance() instead of ContainerBuilder::getContainer('admin'), by [@atomiix](https://github.com/atomiix)


### Installer
* [#19757](https://github.com/PrestaShop/PrestaShop/pull/19757): Add a CLI option for fixtures, by [@Progi1984](https://github.com/Progi1984)


### Merge
* [#20983](https://github.com/PrestaShop/PrestaShop/pull/20983): Merge 177x into develop 14/09/2020, by [@jolelievre](https://github.com/jolelievre)


## Code changes in the '1.7.7.x' branch


### Core
* [#20992](https://github.com/PrestaShop/PrestaShop/pull/20992): Update live polyfill in BO, FO core theme, and remove it from FO classic theme, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#20960](https://github.com/PrestaShop/PrestaShop/pull/20960): Fix bulk actions in Carriers page, by [@atomiix](https://github.com/atomiix)
* [#20936](https://github.com/PrestaShop/PrestaShop/pull/20936): Fix navbar scroll on mobile display, by [@sowbiba](https://github.com/sowbiba)
* [#20911](https://github.com/PrestaShop/PrestaShop/pull/20911): Fix glyph.png asset path. Thank you [@okom3pom](https://github.com/okom3pom)
* [#20902](https://github.com/PrestaShop/PrestaShop/pull/20902): Keep order detail from being updated in BO > Order detail page, when product doesn't exist anymore, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Tests
* [#21056](https://github.com/PrestaShop/PrestaShop/pull/21056): Fix tests errors in nightly 18-09-20, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21043](https://github.com/PrestaShop/PrestaShop/pull/21043): Fix test context in 'Sort and pagination image settings'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21040](https://github.com/PrestaShop/PrestaShop/pull/21040): Add test 'Sort Stores', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21029](https://github.com/PrestaShop/PrestaShop/pull/21029): Delete force install playwright on docker, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20997](https://github.com/PrestaShop/PrestaShop/pull/20997): Add test 'Sort and pagination image settings'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#20988](https://github.com/PrestaShop/PrestaShop/pull/20988): Fix 'CRUD Cart Rule' Test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20961](https://github.com/PrestaShop/PrestaShop/pull/20961): Add test 'Filter, quick edit and bulk actions cart rules', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20932](https://github.com/PrestaShop/PrestaShop/pull/20932): Add test 'Bulk actions states', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20847](https://github.com/PrestaShop/PrestaShop/pull/20847): Add test 'Configure contact details'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Faceted search module
* [#212](https://github.com/PrestaShop/ps_facetedsearch/pull/212): Bump webpack from 4.44.1 to 4.44.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#211](https://github.com/PrestaShop/ps_facetedsearch/pull/211): Bump mini-css-extract-plugin from 0.11.1 to 0.11.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#736](https://github.com/PrestaShop/docs/pull/736): How to become a maintainer: Add a link for creating the issue, by [@ttoine](https://github.com/ttoine)
* [#735](https://github.com/PrestaShop/docs/pull/735): Fix doc  List of hooks. Thank you [@PululuK](https://github.com/PululuK)
* [#734](https://github.com/PrestaShop/docs/pull/734): missing translation. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#732](https://github.com/PrestaShop/docs/pull/732): Missing translation. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#731](https://github.com/PrestaShop/docs/pull/731): Align columns Webservices Tables, by [@Progi1984](https://github.com/Progi1984)
* [#730](https://github.com/PrestaShop/docs/pull/730): Remove duplicate. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#729](https://github.com/PrestaShop/docs/pull/729): Fixes writing mistake, bad pattern name. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#728](https://github.com/PrestaShop/docs/pull/728): Typo fix in admin controllers. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#727](https://github.com/PrestaShop/docs/pull/727): Writing mistake admin controllers page. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#726](https://github.com/PrestaShop/docs/pull/726): Introducing new webservice documentation resources, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#723](https://github.com/PrestaShop/docs/pull/723): Correcting trans() calls in module's controllers. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#722](https://github.com/PrestaShop/docs/pull/722): missing $ symbol. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#716](https://github.com/PrestaShop/docs/pull/716): Explain the Migration strategy and roadmap, by [@matks](https://github.com/matks)


### Buy button lite module
* [#42](https://github.com/PrestaShop/ps_buybuttonlite/pull/42): Bump lodash from 4.17.15 to 4.17.20 in /app. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#41](https://github.com/PrestaShop/ps_buybuttonlite/pull/41): Bump http-proxy from 1.17.0 to 1.18.1 in /app. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#40](https://github.com/PrestaShop/ps_buybuttonlite/pull/40): Bump lodash.mergewith from 4.6.1 to 4.6.2 in /app. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#39](https://github.com/PrestaShop/ps_buybuttonlite/pull/39): Bump node-sass from 4.9.3 to 4.13.1 in /app. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### jQuery Live Polyfill library
* [#5](https://github.com/PrestaShop/jquery.live-polyfill/pull/5): Update version, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#4](https://github.com/PrestaShop/jquery.live-polyfill/pull/4): update minified dist file, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#3](https://github.com/PrestaShop/jquery.live-polyfill/pull/3): Remove usage of migrateWarn function, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### PrestaShop contributors website
* [#23](https://github.com/PrestaShop/TopContributors/pull/23): Add contributors anchor link. Thank you [@PululuK](https://github.com/PululuK)


### Contact Form module
* [#51](https://github.com/PrestaShop/contactform/pull/51): Bump version, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#50](https://github.com/PrestaShop/contactform/pull/50): Release 4.3.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#49](https://github.com/PrestaShop/contactform/pull/49): Changed way to get the order id into $var_list array. Thank you [@jordiweblidera](https://github.com/jordiweblidera)


### Check payment module
* [#39](https://github.com/PrestaShop/ps_checkpayment/pull/39): Updated dev branch from master changes, by [@Progi1984](https://github.com/Progi1984)
* [#38](https://github.com/PrestaShop/ps_checkpayment/pull/38): Fixed CI and update dev from master, by [@Progi1984](https://github.com/Progi1984)


### Custom text module
* [#44](https://github.com/PrestaShop/ps_customtext/pull/44): Release 4.1.1, by [@Progi1984](https://github.com/Progi1984)
* [#43](https://github.com/PrestaShop/ps_customtext/pull/43): Improve project & Bump version to 4.1.1, by [@Progi1984](https://github.com/Progi1984)


### Customer "Sign in" link module
* [#25](https://github.com/PrestaShop/ps_customersignin/pull/25): Release 2.0.3, by [@Progi1984](https://github.com/Progi1984)
* [#24](https://github.com/PrestaShop/ps_customersignin/pull/24): Improve project & Bump version to 2.0.3, by [@Progi1984](https://github.com/Progi1984)


### Shopping cart module
* [#67](https://github.com/PrestaShop/ps_shoppingcart/pull/67): Fixed CI & Bump version to 2.0.4 , by [@Progi1984](https://github.com/Progi1984)


### Example modules
* [#27](https://github.com/PrestaShop/example-modules/pull/27): Improve README, by [@matks](https://github.com/matks)


### Issues Bot
* [#9](https://github.com/PrestaShop/issuebot/pull/9): Bump node-fetch from 2.6.0 to 2.6.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#75](https://github.com/PrestaShop/welcome/pull/75): Bump imports-loader from 0.6.5 to 0.8.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#74](https://github.com/PrestaShop/welcome/pull/74): Bump style-loader from 0.13.2 to 0.23.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#73](https://github.com/PrestaShop/welcome/pull/73): Bump exports-loader from 0.6.4 to 0.7.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Google Analytics module
* [#73](https://github.com/PrestaShop/ps_googleanalytics/pull/73): Avoid force hooking of ps_featuredproducts on displayHome hook, by [@matks](https://github.com/matks)
* [#72](https://github.com/PrestaShop/ps_googleanalytics/pull/72): Add Configuration option to disable Back Office tracking, by [@matks](https://github.com/matks)
* [#68](https://github.com/PrestaShop/ps_googleanalytics/pull/68): Handle NOW correctly when creating order and register in SQL, by [@matks](https://github.com/matks)
* [#67](https://github.com/PrestaShop/ps_googleanalytics/pull/67): Fix logic, avoid double pageview for BO pages, by [@matks](https://github.com/matks)
* [#59](https://github.com/PrestaShop/ps_googleanalytics/pull/59): Avoid array to string error on homepage with cart. Thank you [@Guisardo](https://github.com/Guisardo)


### Prestashop UI Kit
* [#102](https://github.com/PrestaShop/prestashop-ui-kit/pull/102): Use local version of fonts in case of offline use, by [@NeOMakinG](https://github.com/NeOMakinG)


### Product Comments module
* [#65](https://github.com/PrestaShop/productcomments/pull/65): Fix line breaks of comments not existing anymore on FO, by [@NeOMakinG](https://github.com/NeOMakinG)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@zuk3975](https://github.com/zuk3975), [@boubkerbribri](https://github.com/boubkerbribri), [@dependabot[bot]](https://github.com/apps/dependabot), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@ttoine](https://github.com/ttoine), [@matthieu-rolland](https://github.com/matthieu-rolland), [@PululuK](https://github.com/PululuK), [@PierreRambaud](https://github.com/PierreRambaud), [@moncef-essid](https://github.com/moncef-essid), [@Progi1984](https://github.com/Progi1984), [@jolelievre](https://github.com/jolelievre), [@davidglezz](https://github.com/davidglezz), [@atomiix](https://github.com/atomiix), [@matks](https://github.com/matks), [@okom3pom](https://github.com/okom3pom), [@sowbiba](https://github.com/sowbiba), [@jordiweblidera](https://github.com/jordiweblidera), [@NeOMakinG](https://github.com/NeOMakinG), [@Guisardo](https://github.com/Guisardo), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
