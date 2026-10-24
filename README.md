# decision-models usage example

Offline catalog of OpenRouter decision models (Jev, GPT-6 Luna Decisions, and others), kept separate from text and gateway catalogs.

This consuming application demonstrates **look up models in the bundled offline catalog** using the published npm package, pinned to `0.2.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- List decision-oriented models separately from general text-generation catalogs.
- Retrieve a decision-model record for a dispatcher configuration screen.

## Links

- [npm package](https://www.npmjs.com/package/decision-models)
- [Implementation monorepo](https://github.com/x12i/ai-profiles)
- [Reviewed package source](https://github.com/x12i/ai-profiles/tree/8efd4dc11dfaacab2ceef9f030a4a3fa7da00800/packages/decision-models)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
