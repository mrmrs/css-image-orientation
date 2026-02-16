# css-image-orientation

Functional CSS for image-orientation

## Filesize

| File | Size |
|------|------|
| `dist/image-orientation.css` | 597 bytes |
| `dist/image-orientation.min.css` | 475 bytes (135 Gzipped) |

## Install

```sh
npm install css-image-orientation
```

## Usage

### Import

```css
@import "css-image-orientation";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-image-orientation/dist/image-orientation.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-image-orientation/dist/image-orientation.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.img-orientation-none` | `image-orientation: none;` |
| `.img-orientation` | `image-orientation: from-image;` |
| `.img-orientation-none-s` | `image-orientation: none;` |
| `.img-orientation-s` | `image-orientation: from-image;` |
| `.img-orientation-none-m` | `image-orientation: none;` |
| `.img-orientation-m` | `image-orientation: from-image;` |
| `.img-orientation-none-l` | `image-orientation: none;` |
| `.img-orientation-l` | `image-orientation: from-image;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.img-orientation-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/image-orientation.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/image-orientation.css` — formatted
- `dist/image-orientation.min.css` — minified

## License

MIT
