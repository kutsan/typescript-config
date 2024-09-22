# @kutsan/typescript-config

## Usage

Install the config package:

```sh
npm install @kutsan/typescript-config --save-dev
```

Use it in your `tsconfig.json` file:

Change the `<target>` to `react`, `react-native` or `node` depending on your project:

```json
{
  "extends": "@kutsan/typescript-config/<target>.json"
}
```
