# Symfony Flex Recipes

## Deprecated

Use https://github.com/shopware/recipes instead

This repository is hosting Symfony Flex Recipes for Shopware 6.

## Install

- Require `symfony/flex` in your project

- Add custom endpoint to your composer.json

```json
"extra": {
  "symfony": {
      "allow-contrib": true,
      "endpoint": [
        "https://api.github.com/repos/FriendsOfShopware/recipes/contents/index.json?ref=flex/main"
    ]
  }
}
```
