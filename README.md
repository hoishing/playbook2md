# Google Playbook Annotations to Markdown

- convert ebook annotations(highlights and custom notes) of Google Playbook to markdown files
- one markdown file per book

## download your ebook annotations

- export ebook annotations for Google Playbook through [Google Takeout](https://takeout.google.com)
- select json format
- download the exported annotations zip file

## extract annotations to markdown

- set the following params in `playbook.ipynb`:
  - `vault`: folder path of exported markdown files
  - `takeout_zip`: path of the zip file downloaded from Google Takeout

- run all cells of `playbook.ipynb`
- markdown files should be generated inside the vault folder
