# eslint-config

My eslint configuration

# Usage

```cmd
npm i @pygc/eslint-config --save-dev
```

@ `package.json`

```json5
{

  "scripts": {
    "check": "eslint *.js"
  },

  "eslintConfig": {
    "extends": "@pygc/eslint-config/index"
  }
}
```