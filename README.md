# ulauncher-docsearch

> Full text search on Documentation sites, powered by [Algolia](https://www.algolia.com/) Docsearch.

[![Ulauncher Extension](https://img.shields.io/badge/Ulauncher-Extension-green.svg?style=for-the-badge)](https://ext.ulauncher.io/-/github-brpaz-ulauncher-docsearch)
![License](https://img.shields.io/github/license/brpaz/ulauncher-docsearch.svg?style=for-the-badge)

![Algolia](images/search-by-algolia-light-background.svg)

## Motivation

Searching documentation is a constant need but not an easy task. Switch contexts between your code editor to the browser, remember the documentation site url and then find what you need. Many times, I kwew exactly what I want to find and that I have seen before, but simple cant find it again.

This extension, aims to make documentation search less painfull, allowing you to a full text search on popular documentation sites directly from directly from ulauncher.

## Features

This extension allows to easily search on popular documentation websites, that implements [Algolia DocSearch](https://community.algolia.com/docsearch/).

The following documentation sites are included by default in this extension:

-   Apollo GraphQL
-   Babel
-   Cypress
-   Echo
-   Eslint
-   Gatsby
-   GitHub
-   GitLab
-   GORM
-   Grafana
-   GraphQL
-   Gridsome
-   Helm
-   Jest
-   Laravel
-   Netlify
-   NuxtJS
-   Parcel
-   Prettier
-   Prisma
-   Prometheus
-   React
-   Scala
-   Strapi
-   Tailwind
-   Typescript
-   Vue
-   Vuepress
-   Vuetify
-   Vuex
-   Vue-Router
-   Webpack


## Requirements

- Ulauncher V5
- Python 3
  - algoliasearch>=2.0,<3.0 (install with pip3)

## Install

Open ulauncher preferences window -> extensions -> add extension and paste the following url:

```
https://github.com/brpaz/ulauncher-docsearch
```


## Usage

![demo](demo.gif)


Open Ulauncher and type ```docs```. A list of available documentation sites will appear. Select one and type your search keyword to search on that website.

Optionally some documentation also supports a custom keyword, to trigger it directly without having to type ```docs``` before.

For example, for Vue documentation, you can just type ```vue <query>```.

You can see the supported keywords in [manifest.json](manifest.json) file.


## Development

```
git clone https://github.com/brpaz/ulauncher-docsearch
make link
```

The `make link` command will symlink the cloned repo into the appropriate location on the ulauncher extensions folder.

To see your changes, stop ulauncher and run it from the command line with: `ulauncher -v`.

## Contributing

All contributions are welcome.

If you want to add new documentation, you can either do a PR so other users can benefit with it or adding it locally.

Please see the following guide to know how:

* [Add new documentation](docs/add-new-doc.md)


## Show your support

<a href="https://www.buymeacoffee.com/Z1Bu6asGV" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Credits

This project would never be possible without the awesome folks at [Algolia](https://www.algolia.com/) who build this search engine and all the websites that implemented it.

## License

Copywright @ 2019 [Bruno Paz](https://github.com/brpaz)

This project is [MIT](LLICENSE) Licensed.
