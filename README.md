# eslint-config

My eslint configuration

# Usage

@ `package.json`

```json5
{
  // ...
  "scripts": {
    // ...
    "check": "eslint *.js"
  },

  // ...
  "devDependencies": {
    // ...
    "@pygc/eslint-config": "0.0.1",
  },

  "eslintConfig": {
    "extends": "@pygc/eslint-config/index"
  }
}
```