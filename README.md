# Markdown-to-Confluence

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/artis3n/markdown-to-confluence)](https://github.com/artis3n/markdown-to-confluence/releases)
![GitHub last commit](https://img.shields.io/github/last-commit/artis3n/markdown-to-confluence)
![GitHub](https://img.shields.io/github/license/artis3n/markdown-to-confluence)
[![GitHub followers](https://img.shields.io/github/followers/artis3n?style=social)](https://github.com/artis3n/)
[![Twitter Follow](https://img.shields.io/twitter/follow/artis3n?style=social)](https://twitter.com/Artis3n)

## :exclamation: IN DEVELOPMENT! I do not recommend using at this time

This GitHub Action converts GitHub-flavored Markdown in a repository into a series of pages on a Confluence wiki.

This action will recursively retrieve all markdown files and recreate their hierarchy as Confluence pages.

The Action will use the README.md of the repository as the root page titled with the name of the repository unless the `source_dir` input parameter is specified.
The `source_dir` is a relative path inside the repository to the location of the Markdown files that you wish to render in Confluence.
See below for more details and how to configure this action.

# Requirements

You must supply a `confluence_url`, 
