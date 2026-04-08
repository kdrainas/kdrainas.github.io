# File and Directory Overview

- _data/navigation.yml: Relevant for navigation bar at the top of the website, and indicates which page-source is found where
- _pages: contains an md file for every page of the website
- _posts: Not relevant
- _site: html that is actually displayed, created automatically by jekyll from the sources
- assets: Put pictures and pdfs here.
- _config.yml: Side bar and some page info is in here.
- index.md: Not sure if relevant. Either this or _pages/about.md is read for the initial webpage.
- \<rest\>: don't touch.

# How to Push New Changes

1. Modify site content (likely _pages/\<sth\>.md)
2. Execute `bundle exec jekyll serve` and check in localhost (http://127.0.0.1:4000/) that everything looks good
3. Push