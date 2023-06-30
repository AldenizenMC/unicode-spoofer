# Changelog

## 30-06-2023

- Renamed from "Unicodeify" to "Letter Swap"
- Eliminated the dependency on [Bulma](https://bulma.io/)
- Added replacement letter for `D`, `K`, `N`, `l`, and `y` [(see updated list here)](javascripts/letters.js)
- Modified the theme to eliminate the transitional phase from dark mode (default) to light mode upon website load
- Updated the navbar links by removing the leading "/" from the href values, allowing proper navigation within the GitHub Page
- Replaced custom-made copy to clipboard functionality with [clipboard.js](https://clipboardjs.com/)
- Modified footer
- Updated the textarea behavior to enable horizontal scrolling when the text overflows, instead of wrapping the text
- Adjusted the textarea placeholder's opacity to distinguish it from actual text content
- Added noscript tag on pages that require JavaScript