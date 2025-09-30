# template-sveltekit-package

You probably don't need this template and should just run `npx sv create`.

This is a [SvelteKit](https://svelte.dev/docs/kit/introduction) package project which I use as a [GitHub template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

## Keeping dependencies up-to-date

Before updating the dependencies in this template, delete `eslint.config.js` because it will not be regenerated if it exists already. Then run `npx sv create` to regenerate a Svelte library project into the existing directory.

### Where would you like your project to be created?

Hit enter to use the current directory.

### Directory not empty. Continue?

Yes.

### Which template would you like?

Svelte library.

### Add type checking with TypeScript?

Yes, using TypeScript syntax.

### What would you like to add to your project?

- [x] `prettier`
- [x] `eslint`
- [x] `vitest`
- [x] `devtools-json`

### vitest: What do you want to use vitest for?

- [x] unit testing
- [ ] component testing

### Which package manager do you want to install dependencies with?

`pnpm`

### Wrap it up

- Revert `README.md`.
- Run `pnpm dev` to test if the app still launches.

## Debugging

Just launch the application in the
[JavaScript Debug Terminal](https://code.visualstudio.com/docs/editor/debugging#_launch-javascript-debug-terminal).
