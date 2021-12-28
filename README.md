# DevOpsDays Los Angeles Website

The site is built with [Hugo](https://gohugo.io/) and themed with [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## Local Development

### Requirements

- [Hugo](https://github.com/gohugoio/hugo)
- [Pre-commit](https://github.com/pre-commit/pre-commit)
- [Docker](https://www.docker.com/)

### Enviroment

Setup repository locally:

```sh
git clone --recurse-submodules git@github.com:DevOpsDaysLA/website.git
pre-commit install
```

Serve locally:

```sh
hugo serve
```

Update theme:

```sh
git submodule update --remote
```
