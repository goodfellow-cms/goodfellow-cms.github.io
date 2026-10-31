# goodfellow-cms.github.io

The root of the `goodfellow-cms.github.io` domain, published with GitHub Pages from `main`. [Goodfellow](https://github.com/goodfellow-cms/goodfellow-cms)'s documentation is a site of its own at [goodfellow-cms.github.io/goodfellow-cms/](https://goodfellow-cms.github.io/goodfellow-cms/), built from the main repository's `docs/` folder.

- `robots.txt` names the documentation's sitemap, since search engines read `robots.txt` only at a domain's root, never in a site's folder.
- `index.html` sends visitors who open the domain itself to the documentation. Before it does, it carries Google Search Console's and Bing Webmaster Tools' verification tags, which prove the organization owns the domain; removing them unverifies it.
- `404.html` sends visitors who open any other address on the domain to the same address in the documentation, such as `/docs/blocks` to `/goodfellow-cms/docs/blocks`, where the documentation's own "Page not found" shows if it has no such page. Addresses in the documentation's folder never reach it: GitHub Pages answers those with the documentation's own.
- `.nojekyll` publishes the files as they are.
