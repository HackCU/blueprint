
<br>
<p align="center">
  <img alt="HackCU IV" src="https://github.com/HackCU/splash-page/blob/master/img/hackcu_black.png" width="200"/>
</p>
<br>

💡HackCU internal (and open sourced) blueprints. Documentation on how to organize events and more at HackCU.

# Run project

Needs: Ruby

## Local 

1. `git clone https://github.com/hackcu/blueprint && cd blueprint`
2. `gem install jekyll && gem install jemoji`
3. `jekyll serve --watch`

## Deploy

1. Push changes to master
2. There's no `2`

Deployment is done automatically by [GitHub pages](https://pages.github.com/). You don't need to do anything else than pushing to master.

# Development

## Add new page

1. Add Markdown or HTML file under directory `_pages`
2. Start with the following snippet (edit title and description at your will)

```liquid
---
layout: base
title: HackCU blueprint
description: This is a blueprint to learn how to organize HackCU
---
```

## Want to contribute?

Please read our [Code of Conduct](.github/CODE_OF_CONDUCT.md), then follow these [guidelines](.github/CONTRIBUTING.md)
