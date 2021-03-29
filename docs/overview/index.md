# MS Order API

Everything abour MS Order API and related components

## Features
- Payment
- payback
- payment status

write your documentation by adding more markdown (.md) files to this folder (/docs) or replace the content in this file.

## Tech References

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

## Installation

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Table of Contents

The Table of Contents on the right is generated automatically based on the hierarchy
of headings. Only use one H1 (`#` in Markdown) per file.

## Site navigation

For new pages to appear in the left hand navigation you need edit the `mkdocs.yml`
file in root of your repo. The navigation can also link out to other sites.

Alternatively, if there is no `nav` section in `mkdocs.yml`, a navigation section
will be created for you. However, you will not be able to use alternate titles for
pages, or include links to other sites.

Note that MkDocs uses `mkdocs.yml`, not `mkdocs.yaml`, although both appear to work.
See also <https://www.mkdocs.org/user-guide/configuration/>.

## Support

That's it. If you need support, reach out in [#docs-like-code](https://discord.com/channels/687207715902193673/714754240933003266) on Discord.
