# Reach Studios ESLint Config

This package contains the ESLint config for the development team at [Reach Studios](https://reachstudios.co.uk/).

It is based on the [Airbnb ESLint config](https://www.npmjs.com/package/eslint-config-airbnb).

## Usage

This package currently exposes a single configuration

```
npm install @reachstudios/eslint-config
```

Then add the following to your `.eslintrc`

```
{
  ...
  "extends": "@reachstudios" 
  ...
}
```

## Dependencies

Due to the dependency on Airbnb currently this config is currently tied to `eslint@^8`.
