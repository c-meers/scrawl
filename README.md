![Scrawl Title](https://cdn.cmeers.com/scrawl.png)

This is a handwritten font - it isn't character-complete but has about everything you'd need to write text to communicate.

The family currently includes:

- Regular
- Bold

---

## Installation

### macOS

1. Open the `.otf` file
2. Click **Install Font**

The font will be available in Font Book and all applications.

### Windows

1. Right-click the `.otf` file
2. Select **Install** (or **Install for all users**)

### Linux

Copy the `.otf` files to:

```terminal
~/.local/share/fonts/
```

Then run:

```bash
fc-cache -f -v
```

## Web usage

WOFF2 files are provided for web use.

Example font-face declarations:

```css
@font-face {
font-family: "Scrawl";
src: url("Scrawl-Regular.woff2") format("woff2");
font-weight: 400;
font-style: normal;
}

@font-face {
font-family: "Scrawl";
src: url("Scrawl-Bold.woff2") format("woff2");
font-weight: 700;
font-style: normal;
}
```

## Files

`fonts/otf/`
Primary distribution for desktop use

`fonts/woff2/`
Web distribution

`specimens/`
Visual examples of the typeface

## License

Scrawl is licensed for non-commercial use only.

See the LICENSE file for full terms.

## Author

Designed by Clement Meers.
