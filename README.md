![Cecilia Classless](docs/assets/logo-cecilia-classless.svg)

# Welcome to Cecilia Classless

![npm](https://img.shields.io/npm/v/cecilia-classless?color=%230374B4)
![gzip size](https://img.badgesize.io/SandroMiguel/cecilia-classless/master/dist/cecilia-classless.min.css?compression=gzip&color=blue)
[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

[View demo](https://sandromiguel.github.io/cecilia-classless) | [Download](https://github.com/SandroMiguel/cecilia-classless/releases/latest)

Cecilia Classless is a CSS framework equipped with a set of CSS rules that style DOM elements based on their HTML tag names. This implies that you don't need to append classes to HTML elements for them to be styled by the framework.

## Features

Cecilia Classless offers the following key features:

-   **Element-Centric Styling:** Styles elements based on their HTML tag names, eliminating the need for additional classes.
-   **Simplified Prototyping:** Perfect for rapidly creating a basic layout for website prototypes.
-   **Customizable Defaults:** Easily adjust default values by overriding CSS variables for tailored designs.
-   **Lightweight:** Keeps your projects lightweight by providing only essential and classless styles.

## Getting Started

To get started with Cecilia Classless, follow these simple steps:

1. Download Cecilia Classless.
2. Link the `cecilia-classless.css` or `cecilia-classless.min.css` file to your HTML.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>My Website</title>
  <link rel="stylesheet" href="cecilia-classless.css">
</head>
<body>
  <h1>My Website</h1>
  <p>This is a prototype of my website.</p>
</body>
</html>
```

## Customizing Default Values

The `cecilia-classless.css` file includes a set of default CSS variables that define various aspects of the framework. To customize these values, simply override these variables in your own stylesheet.

Here's an example of how you can replace the default values:

```css
/* Import Cecilia-Classless */
@import 'cecilia-classless.css';

/* Override default values */
:root {
    --cecilia-font-family-base: 'Open Sans', sans-serif;
    --cecilia-font-size-base: 16px;
    /* Add more custom variable overrides here */
}
```

## Credits

-   [Normalize.css](https://necolas.github.io/normalize.css/): Browser style reset used by Cecilia Classless.

## Contributing

Want to contribute? All contributions are welcome. Please read the [contributing guide](CONTRIBUTING.md).

## Questions

If you have questions tweet me at [@sandro_m_m](https://twitter.com/sandro_m_m) or [open an issue](../../issues/new).

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
