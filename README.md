# pure-react-types

`@types/react` without any `react-dom` types included (react `v19`, backwards compatability before hooks questionable)

`React.JSX.IntrinsicElements` are **empty** so this package is perfect for non-DOM react shenanigans.

## Installation

```sh
npm i --save-dev pure-react-types

pnpm add -D pure-react-types
```

Update your `tsconfig.json` so it can find the types:

```json
{
  "compilerOptions": {
    "types": ["pure-react-types"],
  },
}
```

Last patched `@types/react` version: `19.1.2`
