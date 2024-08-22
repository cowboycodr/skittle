# create-svelte

A powerful fork of `create-svelte` with added features and options. Just run...

```bash
npm create skittle@latest
```

...and follow the prompts.

## API

You can also use `create-skittle` programmatically:

```js
import { create } from 'create-skittle';

await create('my-new-app', {
  name: 'my-new-app',
  template: 'default', // or 'skeleton' or 'skeletonlib'
  types: 'checkjs', // or 'typescript' or null;
  prettier: false,
  eslint: false,
  tailwindcss: false,
  playwright: false,
  vitest: false
});
```

`checkjs` means your project will use TypeScript to typecheck JavaScript via [JSDoc comments](https://www.typescriptlang.org/docs/handbook/jsdoc-supported-types.html).

## License

[MIT](../../LICENSE).
