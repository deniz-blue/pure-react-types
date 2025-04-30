# pure-react-types

`@types/react` without any `react-dom` types included

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
