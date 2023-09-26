# Hugo UI ShortCode

Base ShortCodes for Hugo.

## Install

```sh
git submodule add 'https://github.com/pkgstore/hugo-ui-shortcode.git' 'themes/ui-shortcode'
```

## Update

```sh
git submodule update --remote --merge
```

## Uninstall

```sh
m='ui-shortcode'; git submodule deinit -f "themes/${m}"; git rm -r --cached "themes/${m}"; rm -rf ".git/modules/themes/${m}"; rm -rf "themes/${m}"
```
