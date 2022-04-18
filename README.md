# minstyle.io

> A simple & Lightweight CSS Framework, including dark mode.

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![npm version](https://badge.fury.io/js/minstyle.io.svg)](https://badge.fury.io/js/minstyle.io)

![minstyle.io](https://nsa40.casimages.com/img/2019/12/02//191202090524519052.png)

## Informations

minstyle.io is a simple and light open source CSS framework. It integrates a set of pre-designed HTML elements, allowing the rapid and simple development of interfaces for all devices.

> minstyle.io is entirely designed in CSS (SCSS), no javascript library is developed or required.

The **architecture of the framework is based on the concatenation of classes**. For example, the `ms-btn` classe allows to get the default design of a button, the `ms-primary` classe allows to change background-color, and the `ms-rounded` classe allows to round the button angles.

The framework is based on 4 colors: primary `.ms-primary` and secondary `ms-secondary` being the main colors of the design.
The action colors, `.ms-action` and `.ms-action2`, allow you to highlight the elements calling for an action, or define a complementary color to the first two.

Since V2, it is possible to customize the 4 colors via the [framework generator](https://generator.minstyle.io/).

Each component of the framework is compatible with the dark mode. A dedicated page explains how it works.

## Version

minstyle.io V2.0.1

## Get Started

The sources code are available for download in `dist/` folder. To integrate it in your project, you just need to add the following tag between your <head> tags, after downloading the .css file.

```html
<link rel="stylesheet" href="css/minstyle.io.css">
```

> The `/dist/css/minstyle.io.min.css` file is a compressed version of the framework, it will be faster to load.

The `/dist/css` folder contains all compiled CSS files. If you want to modify the framework sources, the `/css/scss` folder contains all the SASS files. The `/css/scss/minstyle.io.scss` file contains the variables (colors, shape, etc...) used on the whole framework.

## jsdelivr

For greater simplicity, you could add the `link` tag, importing sources from a CDN.

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/minstyle.io@2.0.1/dist/css/minstyle.io.min.css">
```

## npm

minstyle.io is also available under [npm](https://www.npmjs.com/package/minstyle.io).

```bash
npm i minstyle.io
```

## Yarn

minstyle.io is also available under [yarn](https://yarnpkg.com/en/package/minstyle.io).

```bash
yarn add minstyle.io
```

## Dark mode

minstyle.io integrates the management of the dark mode. Read how to install [dark-mode-switcher](https://github.com/Airmime/dark-mode-switcher).

## How to use ?

Full documentation is available on [minstyle.io](https://minstyle.io).

#### Get started

- [Installation](https://minstyle.io/docs/get-started/installation)

#### Layout

- [Color](https://minstyle.io/docs/Layout/colors)
- [Dark Mode](https://minstyle.io/docs/Layout/dark)
- [Footer](https://minstyle.io/docs/Layout/footer)
- [Generator](https://minstyle.io/docs/Layout/generator)
- [Grid](https://minstyle.io/docs/Layout/grid)

#### Content

- [Blockquote](https://minstyle.io/docs/contents/blockquote)
- [Forms](https://minstyle.io/docs/contents/forms)
- [Icons](https://minstyle.io/docs/contents/icons)
- [Table](https://minstyle.io/docs/contents/table)
- [Titles](https://minstyle.io/docs/contents/titles)
- [Typography](https://minstyle.io/docs/contents/typography)

#### Elements

- [Alerts](https://minstyle.io/docs/elements/alert)
- [Breadcrumb](https://minstyle.io/docs/elements/breadcrumb)
- [Button](https://minstyle.io/docs/elements/button)
- [Button Group](https://minstyle.io/docs/elements/button-group)
- [Dropdown](https://minstyle.io/docs/elements/dropdown)
- [Label](https://minstyle.io/docs/elements/label)
- [Loading](https://minstyle.io/docs/elements/loading)
- [Pagination](https://minstyle.io/docs/elements/pagination)
- [Progress-bar](https://minstyle.io/docs/elements/progress-bar)

#### Components

- [Article](https://minstyle.io/docs/components/article)
- [Avatar](https://minstyle.io/docs/components/avatar)
- [Browser](https://minstyle.io/docs/components/browser)
- [Card](https://minstyle.io/docs/components/card)
- [Hero](https://minstyle.io/docs/components/Hero)
- [Menu](https://minstyle.io/docs/components/menu)
- [Tab](https://minstyle.io/docs/components/tab)
- [User](https://minstyle.io/docs/components/user)

#### Helpers

- [Colors](https://minstyle.io/docs/helpers/colors)
- [Display](https://minstyle.io/docs/helpers/display)
- [Flexbox](https://minstyle.io/docs/helpers/flexbox)
- [Position](https://minstyle.io/docs/helpers/position)
- [Shadow](https://minstyle.io/docs/helpers/shadow)
- [Shape](https://minstyle.io/docs/helpers/shape)

## License

Designed by [Rémi MARION](https://remi-marion.fr). Licensed under [MIT License](https://github.com/Airmime/minstyle.io/blob/master/LICENSE).

## Links

- [Website / Documentation](https://minstyle.io/)
- [Website Repository](https://github.com/Airmime/minstyle.io-Website)
