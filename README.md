# css-width-scale

Functional CSS for width-scale

## Filesize

| File | Size |
|------|------|
| `dist/width-scale.css` | 1385 bytes |
| `dist/width-scale.min.css` | 831 bytes (212 Gzipped) |

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
| `.wi1` | `width: 1rem;` |
| `.wi2` | `width: 2rem;` |
| `.wi3` | `width: 4rem;` |
| `.wi4` | `width: 8rem;` |
| `.wi5` | `width: 16rem;` |
| `.wi6` | `width: 32rem;` |
| `.wi7` | `width: 48rem;` |
| `.wi8` | `width: 64rem;` |
| `.wi9` | `width: 96rem;` |
| `.wi10` | `width: 128rem;` |
| `.wi1-s` | `width: 1rem;` |
| `.wi2-s` | `width: 2rem;` |
| `.wi3-s` | `width: 4rem;` |
| `.wi4-s` | `width: 8rem;` |
| `.wi5-s` | `width: 16rem;` |
| `.wi6-s` | `width: 32rem;` |
| `.wi7-s` | `width: 48rem;` |
| `.wi8-s` | `width: 64rem;` |
| `.wi9-s` | `width: 96rem;` |
| `.wi10-s` | `width: 128rem;` |
| `.wi1-m` | `width: 1rem;` |
| `.wi2-m` | `width: 2rem;` |
| `.wi3-m` | `width: 4rem;` |
| `.wi4-m` | `width: 8rem;` |
| `.wi5-m` | `width: 16rem;` |
| `.wi6-m` | `width: 32rem;` |
| `.wi7-m` | `width: 48rem;` |
| `.wi8-m` | `width: 64rem;` |
| `.wi9-m` | `width: 96rem;` |
| `.wi10-m` | `width: 128rem;` |
| `.wi1-l` | `width: 1rem;` |
| `.wi2-l` | `width: 2rem;` |
| `.wi3-l` | `width: 4rem;` |
| `.wi4-l` | `width: 8rem;` |
| `.wi5-l` | `width: 16rem;` |
| `.wi6-l` | `width: 32rem;` |
| `.wi7-l` | `width: 48rem;` |
| `.wi8-l` | `width: 64rem;` |
| `.wi9-l` | `width: 96rem;` |
| `.wi10-l` | `width: 128rem;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wi1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/width-scale.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/width-scale.css` — formatted
- `dist/width-scale.min.css` — minified

## License

MIT
