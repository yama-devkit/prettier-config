# Prettier configuration

An opinionated code formatter that supports many languages.

## Installation

Install the shared prettier configuration by running the following command:

```sh
npm install --save-dev prettier @kiabi-lab/prettier-config
```

## Usage

Open your `package.json` file and add the following line at root:

```json title="package.json"
{
    "prettier": "@kiabi-lab/prettier-config"
}
```

Delete your previous prettier configuration file (generally named `.prettierrc`) and then run the
following command to format your code:

```sh
npx prettier --write .
```

Or simply run the following command to check:

```sh
npx prettier --check .
```

## About

This configuration use the following parameters:

| Name          | Value |
| :------------ | :---- |
| printWidth    | 120   |
| semi          | true  |
| singleQuote   | true  |
| tabWidth      | 4     |
| trailingComma | all   |

And the following plugins:

- [css-order](https://github.com/Siilwyn/prettier-plugin-css-order)
- [organize-attributes](https://github.com/NiklasPor/prettier-plugin-organize-attributes)
- [organize-imports](https://github.com/simonhaenisch/prettier-plugin-organize-imports)
