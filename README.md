# apartmentocean-guides
The content site uses Jekyll

## Run the site locally
### Install Ruby, Bundle, Jekyll
more details: https://jekyllrb.com/docs/installation/macos/

### After install, run the code below to start the local server
```
bundle exec jekyll serve
```

## Add a new page

Add the following YAML frontmatter to the top of the file
```
---
layout: default
title: "PAGE TITLE"
---
```
The site is using **Just the docs theme**. More details for adding content and making format changes: https://jekyllthemes.io/theme/just-the-docs

## Write new articles
Create tutorial_name.md in the root to add new articles

## Deploy the content to Heroku
```
git push heroku master
```
