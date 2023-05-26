# mdBook Quickstart 🦀 📙
> Starter template for an online book or docs site made with Markdown and mdBook

> Copied from : https://github.com/MichaelCurrin/mdbook-quickstart, all credit due to author.

<!-- Badges generated with https://michaelcurrin.github.io/badge-generator/ -->

[![GH Pages Deploy](https://github.com/MichaelCurrin/mdbook-quickstart/workflows/GH%20Pages%20Deploy/badge.svg)](https://github.com/rpadmanabhan/test-handbook-docs/actions/workflows/main.yml?query=workflow:"GH+Pages+Deploy")
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![dependency - mdbook](https://img.shields.io/badge/dependency-mdbook-blue)](https://rust-lang.github.io/mdBook/)

[![Hosted with GH Pages](https://img.shields.io/badge/Hosted_with-GitHub_Pages-blue?logo=github&logoColor=white)](https://pages.github.com/)
[![Made with GH Actions](https://img.shields.io/badge/CI-GitHub_Actions-blue?logo=github-actions&logoColor=white)](https://github.com/features/actions)

## Requirements
* [Rust](https://www.rust-lang.org/tools/install)
* [mdBook](https://rust-lang.github.io/mdBook/guide/installation.html)

## Setup
```sh
# install hooks
make hooks
# dependencies
# Install Rust
make install
```

## Sample usage

Start a dev server:

```sh
$ make serve
```

Deploy to GitHub Pages:

Simply make changes under src/ and push to this repo and wait for the GitHub action build to complete. Deployed here : 

[![View site - GH Pages](https://img.shields.io/badge/View_site-GH_Pages-blue?style=for-the-badge)](https://rpadmanabhan.github.io/test-handbook-docs/index.html)

 

## License

Released under [MIT](/LICENSE), credit : [@MichaelCurrin](https://github.com/MichaelCurrin).
