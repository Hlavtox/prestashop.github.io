---
layout: post
aliases: ["/news/coreweekly-week-50-2018"]
title:  "PrestaShop Core Weekly - Week 50 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-12-21 16:15:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 10th to Sunday 16th of December 2018.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Did you notice the new banner on the Core Weekly? It now matches the new theme of prestashop.com ;-)

Also, last week, a few 2018 records have been broken on PrestaShop project's repositories on GitHub:

- 78 pull request merged in one week, including
- 40 pull requests merged only for the Core, and
- 41 pull requests merged from a single contributor, @MathiasReker who is passionate about code lint 
- 80% of the PR were from contributors external to the PrestaShop company

It means two things:

 - You are an amazing team of contributors, contributing more and more with quality pull requests, easier to review and to merge
 - It helps to improve the maintainers productivity on code review and merge

How the end of the year could be better for an open source projet? Congratulations to all PrestaShop developers for this amazing year.


## A quick update about GitHub issues

Last week, [37 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-12-10..2018-12-16) have been created in PrestaShop's core repository, and [8 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-12-10..2018-12-16) have been closed.

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#10533](https://github.com/PrestaShop/PrestaShop/pull/10533): CO: add old product ID on actionProductAdd hook when we duplicate product. Thank you [@duGuillaume](https://github.com/duGuillaume)
* [#10975](https://github.com/PrestaShop/PrestaShop/pull/10975): Introduced a new function for Products.php for retrive a product ID given it reference. Thank you [@runningz](https://github.com/runningz)
* [#11635](https://github.com/PrestaShop/PrestaShop/pull/11635): improve use of protocol. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11643](https://github.com/PrestaShop/PrestaShop/pull/11643): Additional PHP Improvements. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11645](https://github.com/PrestaShop/PrestaShop/pull/11645): Fix discount computing to take combination into account, by [@jolelievre](https://github.com/jolelievre)
* [#11653](https://github.com/PrestaShop/PrestaShop/pull/11653): Allowed the override of  _PS_DEBUG_PROFILING_. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#11666](https://github.com/PrestaShop/PrestaShop/pull/11666): Fully qualified strict types. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11667](https://github.com/PrestaShop/PrestaShop/pull/11667): Heredoc to nowdoc. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11669](https://github.com/PrestaShop/PrestaShop/pull/11669): Improve error suppression. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11671](https://github.com/PrestaShop/PrestaShop/pull/11671): Use constant instead of function. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11672](https://github.com/PrestaShop/PrestaShop/pull/11672): Non printable character. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11678](https://github.com/PrestaShop/PrestaShop/pull/11678): Fix use of protocol. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11679](https://github.com/PrestaShop/PrestaShop/pull/11679): Fix issue with deleting a category with subcategories on Multistore. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11685](https://github.com/PrestaShop/PrestaShop/pull/11685): php-cs-fixer: Fix "non printable character". Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11689](https://github.com/PrestaShop/PrestaShop/pull/11689): Merge 1.7.5.x in develop, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11691](https://github.com/PrestaShop/PrestaShop/pull/11691): Fix bug on pdf logo path. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#11694](https://github.com/PrestaShop/PrestaShop/pull/11694): Align multiline comment. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11695](https://github.com/PrestaShop/PrestaShop/pull/11695): Array indentation. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11696](https://github.com/PrestaShop/PrestaShop/pull/11696): Combine consecutive issets. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11697](https://github.com/PrestaShop/PrestaShop/pull/11697): Combine consecutive unsets. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11699](https://github.com/PrestaShop/PrestaShop/pull/11699): Hash to slash comment. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11701](https://github.com/PrestaShop/PrestaShop/pull/11701): Use logical operators. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11703](https://github.com/PrestaShop/PrestaShop/pull/11703): Do not use short echo tags. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11704](https://github.com/PrestaShop/PrestaShop/pull/11704): Remove useless return. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11707](https://github.com/PrestaShop/PrestaShop/pull/11707): Do not use alias functions. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11708](https://github.com/PrestaShop/PrestaShop/pull/11708): Modernize types casting. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11709](https://github.com/PrestaShop/PrestaShop/pull/11709): Use echo instead of print. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11710](https://github.com/PrestaShop/PrestaShop/pull/11710): Include is not a function. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11711](https://github.com/PrestaShop/PrestaShop/pull/11711): Add missing braces. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11712](https://github.com/PrestaShop/PrestaShop/pull/11712): Normalize use of operators. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11714](https://github.com/PrestaShop/PrestaShop/pull/11714): Fix lineending. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11731](https://github.com/PrestaShop/PrestaShop/pull/11731): Fix typo. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11733](https://github.com/PrestaShop/PrestaShop/pull/11733): Add function type. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11734](https://github.com/PrestaShop/PrestaShop/pull/11734): Remove comma in single array. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11735](https://github.com/PrestaShop/PrestaShop/pull/11735): Elseif instead of else if. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11736](https://github.com/PrestaShop/PrestaShop/pull/11736): Remove unused imports. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11738](https://github.com/PrestaShop/PrestaShop/pull/11738): No PHP closing tag and no EOL. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11744](https://github.com/PrestaShop/PrestaShop/pull/11744): Fix PhpDoc Validate::isColor(). Thank you [@EdouardTack](https://github.com/EdouardTack)
* [#11747](https://github.com/PrestaShop/PrestaShop/pull/11747): Convert comments to php docs in some cases. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11757](https://github.com/PrestaShop/PrestaShop/pull/11757): Remove empty statement. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Back office

* [#11200](https://github.com/PrestaShop/PrestaShop/pull/11200): Addresses changes not impacted when creating an order from another order. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#11201](https://github.com/PrestaShop/PrestaShop/pull/11201): Addresses changes not impacted when creating an order from another order. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#11519](https://github.com/PrestaShop/PrestaShop/pull/11519): Migrate Customers KPIs and required fields configuration. Thank you [@sarjon](https://github.com/sarjon)
* [#11527](https://github.com/PrestaShop/PrestaShop/pull/11527): Migrate customer view actions. Thank you [@sarjon](https://github.com/sarjon)
* [#11732](https://github.com/PrestaShop/PrestaShop/pull/11732): Avoid using short bool. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11739](https://github.com/PrestaShop/PrestaShop/pull/11739): Remove blackslash. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11741](https://github.com/PrestaShop/PrestaShop/pull/11741): Use brackets for index brace. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Front office

* [#11614](https://github.com/PrestaShop/PrestaShop/pull/11614): Custom product flags using module. Thank you [@kpodemski](https://github.com/kpodemski)
* [#11656](https://github.com/PrestaShop/PrestaShop/pull/11656): Correctly display percentage in cart, by [@jolelievre](https://github.com/jolelievre)


### Tests

* [#11674](https://github.com/PrestaShop/PrestaShop/pull/11674): Simplify PHP unit construct. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11675](https://github.com/PrestaShop/PrestaShop/pull/11675): Simplify PHP unit expectations. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11676](https://github.com/PrestaShop/PrestaShop/pull/11676): Use camelcase instead of snakecase in functions. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11677](https://github.com/PrestaShop/PrestaShop/pull/11677): Fix wrong name. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11762](https://github.com/PrestaShop/PrestaShop/pull/11762): Add branch in nightly releases, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#11766](https://github.com/PrestaShop/PrestaShop/pull/11766): Create, edit, delete, exchange rate currency. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#11768](https://github.com/PrestaShop/PrestaShop/pull/11768): Import localization pack. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)


## Code changes in the '1.7.5.x' branch (for v1.7.5.0

### Front office

* [#11777](https://github.com/PrestaShop/PrestaShop/pull/11777): Do not perform updateProductRequest() AJAX call if no valid data input, by [@matks](https://github.com/matks)


### Tests

* [#11659](https://github.com/PrestaShop/PrestaShop/pull/11659): Update dependencies version. Thank you [@hadrich-hatem](https://github.com/hadrich-hatem)
* [#11690](https://github.com/PrestaShop/PrestaShop/pull/11690): Fix install_upgrade campaign. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)


## Code changes in modules, themes & tools

### Google Sitemap

* [#71](https://github.com/PrestaShop/gsitemap/pull/71): Minor improvements. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Products in the same category

* [#6](https://github.com/PrestaShop/ps_categoryproducts/pull/6): Wrong cache key used in ps_categoryproducts. Thank you [@Matt75](https://github.com/Matt75)
* [#8](https://github.com/PrestaShop/ps_categoryproducts/pull/8): Deploying v1.0.4 of ps_categoryproducts, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Link list

* [#57](https://github.com/PrestaShop/ps_linklist/pull/57): Fix update when table cms_block_page does not exist, by [@jolelievre](https://github.com/jolelievre)
* [#59](https://github.com/PrestaShop/ps_linklist/pull/59): Deploy v3.0.2 of ps_linklist, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### MBO

* [#76](https://github.com/PrestaShop/ps_mbo/pull/76): Character issue, by [@MrBaiame](https://github.com/MrBaiame)
* [#77](https://github.com/PrestaShop/ps_mbo/pull/77): Merge fixes to master, by [@jolelievre](https://github.com/jolelievre)
* [#78](https://github.com/PrestaShop/ps_mbo/pull/78): Update version to 1.1.1, by [@jolelievre](https://github.com/jolelievre)
* [#79](https://github.com/PrestaShop/ps_mbo/pull/79): Update version to 1.1.1, by [@jolelievre](https://github.com/jolelievre)


### Catalog evalutation

* [#10](https://github.com/PrestaShop/statscheckup/pull/10): Fix notice due to missing translation key. Thank you [@Matt75](https://github.com/Matt75)


### Visits and Visitors

* [#3](https://github.com/PrestaShop/statsvisits/pull/3): Fix error 500 on Export CSV. Thank you [@Matt75](https://github.com/Matt75)


### Visitors online

* [#2](https://github.com/PrestaShop/statslive/pull/2): getCustomersOnline(): fix SQL clauses to be able to use index. Thank you [@Kioob](https://github.com/Kioob)


### GDPR

* [#10](https://github.com/PrestaShop/psgdpr/pull/10): Add export feature + update translations + fix translation issue with csv and more, by [@Joukz](https://github.com/Joukz)


### PrestaFraud

* [#11](https://github.com/PrestaShop/prestafraud/pull/11): Replace Forge URL by GitHub issues, by [@eternoendless](https://github.com/eternoendless)


### Docker internal images

* [#19](https://github.com/PrestaShop/docker-internal-images/pull/19): Expose HTTPS port, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Changes in Documentation

* [#135](https://github.com/PrestaShop/docs/pull/135): Update to Grid docs. Thank you [@sarjon](https://github.com/sarjon)
* [#168](https://github.com/PrestaShop/docs/pull/168): Add a paragraph in 1.7.5 changes page about the _legacy_link, by [@jolelievre](https://github.com/jolelievre)
* [#172](https://github.com/PrestaShop/docs/pull/172): fixed changedCheckoutStep event name. Thank you [@adviva](https://github.com/adviva)
* [#173](https://github.com/PrestaShop/docs/pull/173): Update objectmodel.md. Thank you [@arischmod](https://github.com/arischmod)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @adviva, @ansar21mallouli, @arischmod, @duGuillaume, @hadrich-hatem, @jf-viguier, @Kioob, @kpodemski, @Matt75, @runningz, @sarjon, @SebBareyre! And a very special thank to @MathiasReker for this one!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
