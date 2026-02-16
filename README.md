# css-width-scale

Functional CSS for width-scale

## Filesize

| File | Size |
|------|------|
| `dist/width-scale.css` | 1577 bytes |
| `dist/width-scale.min.css` | 915 bytes (240 Gzipped) |

## Install

```sh
npm install css-width-scale
```

## Usage

### Import

```css
@import "css-width-scale";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-width-scale/dist/width-scale.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-width-scale/dist/width-scale.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.w1` | `width: 1px;` |
| `.w2` | `width: 2px;` |
| `.w3` | `width: 4px;` |
| `.w4` | `width: 8px;` |
| `.w5` | `width: 16px;` |
| `.w6` | `width: 32px;` |
| `.w7` | `width: 64px;` |
| `.w8` | `width: 128px;` |
| `.w9` | `width: 256px;` |
| `.w10` | `width: 512px;` |
| `.w11` | `width: 1024px;` |
| `.w12` | `width: 2048px;` |
| `.w1-s` | `width: 1px;` |
| `.w2-s` | `width: 2px;` |
| `.w3-s` | `width: 4px;` |
| `.w4-s` | `width: 8px;` |
| `.w5-s` | `width: 16px;` |
| `.w6-s` | `width: 32px;` |
| `.w7-s` | `width: 64px;` |
| `.w8-s` | `width: 128px;` |
| `.w9-s` | `width: 256px;` |
| `.w10-s` | `width: 512px;` |
| `.w11-s` | `width: 1024px;` |
| `.w12-s` | `width: 2048px;` |
| `.w1-m` | `width: 1px;` |
| `.w2-m` | `width: 2px;` |
| `.w3-m` | `width: 4px;` |
| `.w4-m` | `width: 8px;` |
| `.w5-m` | `width: 16px;` |
| `.w6-m` | `width: 32px;` |
| `.w7-m` | `width: 64px;` |
| `.w8-m` | `width: 128px;` |
| `.w9-m` | `width: 256px;` |
| `.w10-m` | `width: 512px;` |
| `.w11-m` | `width: 1024px;` |
| `.w12-m` | `width: 2048px;` |
| `.w1-l` | `width: 1px;` |
| `.w2-l` | `width: 2px;` |
| `.w3-l` | `width: 4px;` |
| `.w4-l` | `width: 8px;` |
| `.w5-l` | `width: 16px;` |
| `.w6-l` | `width: 32px;` |
| `.w7-l` | `width: 64px;` |
| `.w8-l` | `width: 128px;` |
| `.w9-l` | `width: 256px;` |
| `.w10-l` | `width: 512px;` |
| `.w11-l` | `width: 1024px;` |
| `.w12-l` | `width: 2048px;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.w1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/width-scale.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/width-scale.css` — formatted
- `dist/width-scale.min.css` — minified

## License

MIT
