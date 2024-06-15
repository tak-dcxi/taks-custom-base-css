# TAK's Custom Base.css

## Overview

TAK's Custom Base.css is a CSS library designed to normalize styles and ensure consistency across different browsers. This stylesheet is based on [Normalize.css](https://necolas.github.io/normalize.css/) and has been customized by [TAK](https://www.tak-dcxi.com/).

## Key Features

- Ensures as much consistency as possible across browsers.
- Prevents the need to reset user agent styles.
- Removes default margins and padding.
- Uses the `:where()` pseudo-class to reduce specificity conflicts.
- Applies `box-sizing: border-box` to all elements so padding and borders are included in element dimensions.
- Utilizes a common sans-serif font stack for broader cross-platform compatibility.
- Enhances readability by adjusting line spacing and underlines.
- Adds transparent borders where necessary to accommodate forced color modes.
- Supports modern elements and attributes like `dialog`, `search`, `[popover]`, and `[hidden="until-found"]`.
- Prevents VoiceOver in Safari from recognizing list elements with `list-style: none` as a list by using `list-style-type: ""` to hide them.

## Installation

```bash
npm install --save taks-custom-base.css
```

## Usage

Place this CSS file in the appropriate location in your project and add a link to it in the `<head>` section of your HTML file.

```html
<link rel="stylesheet" href="path/to/taks-custom-normalize.css" />
```

## License

This project is released under the MIT License. For more details, refer to the GitHub repository.

## How to Contribute

If you are interested in contributing to this project, please do so through pull requests or issues on GitHub. We look forward to your contributions as part of our community.