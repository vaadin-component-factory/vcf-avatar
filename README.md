[![Build Status](https://travis-ci.org/vaadin/vcf-avatar.svg?branch=master)](https://travis-ci.org/vaadin/vcf-avatar)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;vcf-avatar&gt;

[Live Demo ↗](https://incubator.app.fi/vcf-avatar-demo/index.html)

[&lt;vcf-avatar&gt;](https://vaadin.com/directory/component/vcf-avatar) is a Web Component displaying user's avatar, his name or a placeholder icon.

```html
  <vcf-avatar abbr="BJ" name="Ben Jones" image="https://unsplash.it/500/500?random">
  </vcf-avatar>
```

[<img src="https://raw.githubusercontent.com/vaadin/vcf-avatar/master/screenshot.png" width="200" alt="Screenshot of vcf-avatar">](https://vaadin.com/directory/component/vcf-avatar)


## Installation

The Vaadin component factory components are distributed as Bower packages.

### Polymer 2 and HTML Imports compatible version

Install `vcf-avatar`:

```sh
bower i vaadin/vcf-avatar --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/vcf-avatar/vcf-avatar.html">
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/vcf-avatar.html`

  Unstyled component.

- `theme/lumo/vcf-avatar.html`

  Component with Lumo theme.

- `vcf-avatar.html`

  Alias for theme/lumo/vcf-avatar.html


## Running demos and tests in browser

1. Fork the `vcf-avatar` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `vcf-avatar` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/vcf-avatar/demo
  - http://127.0.0.1:8080/components/vcf-avatar/test


## Running tests from the command line

1. When in the `vcf-avatar` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
