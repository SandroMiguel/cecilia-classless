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

| Variable                            | Description                                     | Default Value                                                          |
| ----------------------------------- | ----------------------------------------------- | ---------------------------------------------------------------------- |
| `--cecilia-sm-container-max-width`  | Maximum width for small containers.             | `540px`                                                                |
| `--cecilia-md-container-max-width`  | Maximum width for medium containers.            | `720px`                                                                |
| `--cecilia-lg-container-max-width`  | Maximum width for large containers.             | `960px`                                                                |
| `--cecilia-xl-container-max-width`  | Maximum width for extra large containers.       | `1140px`                                                               |
| `--cecilia-xxl-container-max-width` | Maximum width for extra extra large containers. | `1400px`                                                               |
| `--cecilia-font-family-base`        | Base font family.                               | `'ubuntu', 'roboto', 'arial', sans-serif'`                             |
| `--cecilia-font-family-code`        | Font family for code elements.                  | `'monospace', 'consolas', "Liberation Mono", "Courier New", 'courier'` |
| `--cecilia-font-size-base`          | Base font size for the document.                | `1rem`                                                                 |
| `--cecilia-font-weight-base`        | Base font weight for the document.              | `400`                                                                  |
| `--cecilia-line-height-base`        | Base line height for the document.              | `1.5`                                                                  |
| `--cecilia-h1-font-size`            | Font size for h1 headings.                      | `calc(var(--cecilia-font-size-base) * 2.5)`                            |
| `--cecilia-h2-font-size`            | Font size for h2 headings.                      | `calc(var(--cecilia-font-size-base) * 2)`                              |
| `--cecilia-h3-font-size`            | Font size for h3 headings.                      | `calc(var(--cecilia-font-size-base) * 1.75)`                           |
| `--cecilia-h4-font-size`            | Font size for h4 headings.                      | `calc(var(--cecilia-font-size-base) * 1.5)`                            |
| `--cecilia-h5-font-size`            | Font size for h5 headings.                      | `calc(var(--cecilia-font-size-base) * 1.25)`                           |
| `--cecilia-h6-font-size`            | Font size for h6 headings.                      | `calc(var(--cecilia-font-size-base) * 1.1)`                            |
| `--cecilia-headings-margin-bottom`  | Margin bottom for headings.                     | `0.6rem`                                                               |
| `--cecilia-headings-line-height`    | Line height for headings.                       | `1.2`                                                                  |
| `--cecilia-background-color`        | Default background color.                       | `#fff`                                                                 |
| `--cecilia-color-base`              | Base text color.                                | `#1f1f1f`                                                              |

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
