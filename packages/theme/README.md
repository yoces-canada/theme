# @yoces/theme

[Theme UI](https://theme-ui.com) theme for [Yoces](https://yoces.ca)

```bash
yarn add @yoces/theme
# npm i @yoces/theme
```

Check out theme: [**theme.hackclub.com**](https://theme.hackclub.com)

## Usage

```js
import { ThemeProvider } from 'theme-ui'
import theme from '@yoces/theme'

export default ({ children }) => (
  <ThemeProvider theme={theme}>{children}</ThemeProvider>
)
```

### Fonts

This package also bundles 3 CSS files that include Hack Club’s webfonts:
`reg.css`, `reg-bold.css`, & `reg-ital-bold.css`.
To use, just import straight from the package:

```js
import '@yoces/theme/fonts/reg-bold.css'
```

(In a Next.js project, [place](https://nextjs.org/docs/basic-features/built-in-css-support) in the `pages/_app.js` file.)

MIT License
