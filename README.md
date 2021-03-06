# Static Seed

[![Uses Mofo Standards](https://MozillaFoundation.github.io/mofo-standards/badge.svg)](https://github.com/MozillaFoundation/mofo-standards)

This is a seed project for creating static-generated sites with an architecture similar to [Women and Web Literacy](https://github.com/mozilla/womenandweb).

## Development

### Setup

**Requirements**: Node, npm, git.

Run the following terminal commands to get started:

- `git clone https://github.com/mozilla/CHANGE_TO_REPO_NAME.git`
- `cd CHANGE_TO_REPO_NAME`
- `npm start`

This will install all dependencies, build the code, start a server at [http://127.0.0.1:2040](http://127.0.0.1:2040), and launch it in your default browser.

### Stack

#### HTML

HTML is generated from [Pug](https://pugjs.org) templates (formerly known as Jade). Text content is pulled in from Markdown partials.

#### CSS

CSS is generated from [Sass](http://sass-lang.com/). The [Mofo Bootstrap](https://github.com/mozilla/mofo-bootstrap) theme is pulled in by default.

### File Structure

```
.
├── dest <- Compiled code generated from source. Don't edit!
├── scripts <- Scripts run by npm tasks
└── source <- Source code
    ├── images <- Image assets
    ├── index.pug <- Pug/Jade template for index page
    ├── markdown <- Markdown partials
    └── sass <- Sass code
```

### Deployment

TODO: Add the specifics for deployment.
