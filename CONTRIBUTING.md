# Contributing to Cecilia Classless

Thank you for considering contributing to Cecilia Classless! We welcome contributions from everyone.

### Getting Started

1. Fork the repository and clone it locally.
2. Install dependencies by running `yarn install`.
3. Make your changes or add new features.
4. Test your changes to ensure they work as expected.
5. Commit your changes and push them to your fork.
6. Submit a pull request with a clear description of your changes.

## Development Environment

To set up your development environment, you'll need:

-   Node.js and npm installed on your machine.
-   Your favorite code editor.

## Customizing Variables

Cecilia Classless offers a set of customizable CSS variables to allow for easy theming and customization. To customize default values, override the desired CSS variables in your own stylesheet. Here are some key variables you can customize:

```css
/* Import Cecilia-Classless */
@import 'cecilia-classless.css';

/* Override default values */
:root {
    --cecilia-color-base: #1f1f1f;
    --cecilia-primary-color: #007bff;
    --cecilia-secondary-color: #6c757d;
    /* Add more custom variable overrides here */
}
```

## Theming

Cecilia Classless uses a default theme that is compiled when specific variables for a custom theme are not defined. To customize the theme, simply define the desired CSS variables in your own stylesheet. Here's an example of how to create a custom theme:

```css
/* Custom theme */
:root {
    --color-base: #ffffff; /* Base text color */
    --background-color: #1f1f1f; /* Default background color */
    /* Add more custom variable overrides for your theme */
}
```
