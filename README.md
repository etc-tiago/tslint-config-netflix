# TSLint Config Netflix

[![NetflixOSS Lifecycle](https://img.shields.io/osslifecycle/Netflix/tslint-config-netflix.svg)]()

Shared [TSLint configuration](https://palantir.github.io/tslint/usage/configuration/) for TypeScript at Netflix

Details of the rules are listed [here](https://palantir.github.io/tslint/rules/).

## Installation

```sh
npm install @netflix/tslint-config --save-dev # npm
yarn add -D @netflix/tslint-config # alternatively, using yarn
```

## Usage

In `tslint.json`:

```json
{
  "extends": "@netflix/tslint-config"
}
```

### You can also add your own [configurations and rules](https://palantir.github.io/tslint/2016/03/31/sharable-configurations-rules.html)
```json
{
  "extends": ["@netflix/tslint-config", "tslint-config-prettier"],
  "rules": {
      "no-any": true
  }
}
```