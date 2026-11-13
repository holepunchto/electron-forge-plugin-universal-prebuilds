# electron-forge-plugin-universal-prebuilds

Universal prebuild support for your Electron app.

```
npm i -D electron-forge-plugin-universal-prebuilds
```

## Requirements

- Electron Forge 8 (this package is ESM-only, matching Forge 8)
- Node.js >= 22.13.0

## Usage

```js
export default {
  // ...
  plugins: [
    {
      name: 'electron-forge-plugin-universal-prebuilds',
      config: {}
    }
  ]
}
```

## License

Apache-2.0
