# eslint-config-uatthaphon

This package uses ESLint to enforce My code style and provides a shared base configuration for our javascript projects.

## Install

### `yarn`

```bash
npm install eslint-config-uatthaphon eslint --dev
```

## Usage
Create a `.eslintrc` file in base of your project:

### For Node Projects

```javascript
{
    extends: 'uatthaphon'
}
```

### For Vue2 Projects

```javascript
{
    extends: 'uatthaphon/vue2'
}
```

## Enabling Prettier
Add `"prettier": "eslint-config-uatthaphon/prettier.config"` to your `package.json`.

## Contributing
You can make sure this module lints with itself using `npm run lint`.
