# Google Playbook Annotations to Markdown

[![Binder][binder]][binder-ipynb] [![GitHub](https://img.shields.io/github/license/hoishing/playbook2md)](https://opensource.org/licenses/MIT)

- convert ebook annotations(highlights and custom notes) of Google Playbook to markdown files
- one markdown file per book

## How to use

## Download Your Ebook Annotations

- export ebook annotations for Google Playbook through [Google Takeout](https://takeout.google.com)
- select json format
- download the exported annotations zip file

## Prepare Your Runtime Environment

- run online with [![Binder][binder]][binder-ipynb]
- or locally with python >= 3.9, no special dependency required

## Extract Annotations to Markdown

- set the following params in `playbook.ipynb`:
  - `vault`: folder path of exported markdown files
  - `takeout_zip`: path of the zip file downloaded from Google Takeout

- run all cells of `playbook.ipynb`
- markdown files should be generated inside the vault folder

[binder]: https://mybinder.org/badge_logo.svg
[binder-ipynb]: https://mybinder.org/v2/gh/hoishing/playbook2md/HEAD?labpath=playbook.ipynb
