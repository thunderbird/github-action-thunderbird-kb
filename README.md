# github-action-thunderbird-kb
github action to get all the Thunderbird SUMO Knowledge Base Articles

## 2025-10-19 2. test get-all-products-kb-articles-list.rb
* The following works :-) and produces details-allproducts-kb-title-slug-all-articles.csv which is currently a 13 megabyte file.

```bash
bundler exec get-kb-article-detailed-list.rb allproducts-kb-title-slug-all-articles.csv
```

## 2025-10-19 1. test get-all-products-kb-articles-list.rb

* The following works :-) and produces allproducts-kb-title-slug-all-articles.csv

```bash
bundler exec get-all-products-kb-articles-list.rb
```
