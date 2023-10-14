# Tailwind CSS + Alpine JS Starter Theme

Build from a strong base

---

# Getting started

### Requirements

- [NPM](https://www.npmjs.com/package/npm) (6.0.0 or higher)
- [Node.js](https://nodejs.org/en/download/) (16.0.0 or higher)
- [Shopify CLI](https://shopify.dev/docs/themes/tools/cli/install) (3.0.0 or higher)

### Installing

1. Run `npm install` to install dependencies
2. Run `npm run dev` to create a development preview
3. Run `npm run build` to build production ready assets

### Command Referance

| Task Name       | Description             |
| :-------------- | :---------------------- |
| `npm run dev`   | Run development preview |
| `npm run build` | Build prodution assets  |
| `npm run test`  | Run tests               |

---

# Making changes

### Development previews

Use `npm run dev` to setup a development preview that refreshes your CSS and JavaScript as you make changes. This is the best way to implement more in-depth changes. You should also consider implementing the [GitHub integration](https://shopify.dev/docs/themes/tools/github) into your workflow.

### Naming coventions

This starter uses a naming convention to help keep things organized. We use the following prefixes to help identify the files in our `/snippet` folder.

- `components__`: Components are reusable pieces of code that can be used in multiple places. Most of our components are used in multiple places throughout the theme.
- `theme__`: Theme files are only ever used in the `theme.liquid` file. These are global snippets that appear on every page of your theme.
- `script__`: Script files contain small snippets of JavaScript that are used throughout the theme.
- `article__`, `collection__`, `product__`: Article, collection and product files are used in their respective templates only.
- `header__`: Header files are used to within the header of your theme.

Section files follow a similar naming convention.

- Section files prefixed with a keyword and a double underscore are only used in their respecitve template files. E.g. `collection__banner.liquid` is only used in the `collection.liquid` file.

### Tips and tricks

- Use the `theme__styles.liquid` file to update or edit theme-wide CSS variables.