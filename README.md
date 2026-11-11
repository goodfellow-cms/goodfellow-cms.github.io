# goodfellow-cms.github.io

The root of the `goodfellow-cms.github.io` domain, published with GitHub Pages from `main`. [Goodfellow CMS](https://github.com/goodfellow-cms/goodfellow-cms)'s documentation moved to [goodfellowcms.com](https://goodfellowcms.com/), so this domain only sends people there, in two pages:

- `index.html` sends visitors who open the domain itself to goodfellowcms.com. Before it does, it carries Google Search Console's and Bing Webmaster Tools' verification tags, which prove the organization owns the domain; removing them unverifies it.
- `404.html` sends visitors who open any other address on the domain to the same address at goodfellowcms.com, such as `/docs/blocks` to `https://goodfellowcms.com/docs/blocks`, where the documentation's own "Page not found" shows if it has no such page. Addresses under `/goodfellow-cms/`, where the documentation used to be, never reach it: GitHub Pages answers those with the main repository's own two pages, which do the same without that folder.
- `.nojekyll` publishes the files as they are.

The documentation's `robots.txt` and `llms.txt` are at goodfellowcms.com's root now, written by its own build.
