# Assets

This folder is dedicated to hosting all the assets used across the project. It includes images, fonts, icons, and other static resources.

## Structure

```bash
assets/
├── images/
│   ├── logo.png
│   ├── banner.jpg
│   └── icons/
│       ├── icon-1.svg
│       └── icon-2.svg
├── fonts/
│   ├── NunitoSans-Regular.woff2
│   ├── NunitoSans-Bold.woff2
│   └── NunitoSans-Italic.woff2
└── README.md
```

## Usage

### Images

To use an image in your project, reference it with the relative path:

```html
<img src="/assets/images/logo.png" alt="Logo" />
```

### Fonts

To include a font in your CSS, use the @font-face rule:

```css
@font-face {
  font-family: "Nunito Sans";
  src: url("/assets/fonts/NunitoSans-Regular.woff2") format("woff2");
  font-weight: normal;
  font-style: normal;
}
```

### Icons

To use an icon, reference it with the relative path:

```html
<img src="/assets/images/icons/icon-1.svg" alt="Icon 1" />
```

## License

All assets are licensed under the MIT License. See the LICENSE file for more details.

## Author

@DinhThienPhuc
